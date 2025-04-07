# Integrating Lab Equipment with ElectricLab

When you begin using ElectricLab with your lab equipment, follow the steps below to set up and connect balances and other devices.

## Prepare the Adapters

Equipment that outputs data, such as lab balances, connect to ElectricLab using an adapter device.

First, determine whether you plan to connect adapters to the internet using wifi or ethernet at your pharmacy. If you plan to use wifi, provide Pharmetika with the SSID and password so we can provision the adapters prior to shipping.

Next, determine whether to connect adapters to balances using USB cords or RS232 cords, and purchase the cords of your choice. We recommend placing adapters outside of a fume hood to minimize powder accumulation inside the adapters. Additionally, locate your adapters so that both the power and USB or RS232 cords can maintain secure, tight connections. &#x20;

Plug the USB cable into the USB port on the adapter without plugging in any other USB devices at the same time. Then, connect the other end to the balance's USB or RS-232 port. If you are connecting with ethernet, be sure the network cable is plugged in.

It is imperative that the 2D barcode on the adapter remain intact and adhered to the device.  You will need to use this barcode for equipment setup and any troubleshooting.

## Add Equipment to ElectricLab

1. In ElectricLab, go to Configuration > Configure Equipment.&#x20;
2. To add a new equipment device, click the **Add New** button in the upper right hand corner. If you already have an existing equipment entry you want to use, expand the entry for your balance.
3. In the **Description** field, enter a description of the designated balance.&#x20;
4. In the **Location** field, enter a description of the balance’s location.
5. In the **Equipment Type** field, select Balance.
6. In the **Variance (%)** section, set the desired variance for the scale.&#x20;
7. Click **Save** to save the equipment entry.
8. Click **Print** to the label for the equipment.
9. Affix the label to the balance.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcpNtT6Gn0XMpD3giTFpcVbzTu3NGFITFIjFa-1nlRmJ9obO4smrNcq19iQwV1iZ8uLjpWj0ryTeDjSBF2IN3zVOI9PyeuBkjGO_D02ckvOVJgVLUkrm2PYadqzgdF_89Z_qsIU9g?key=bRniQrmO2qFSBddi-ZwMtIL2" alt="A new equipment record is shown after creation."><figcaption><p>If you don't already have an equipment record for the device, create a new record.</p></figcaption></figure>

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdDueIg8d6CfPmAypG9bg1HnJfO5HdqWlyzkCN-viSmRVfyQzBY7y9BjMUXZ0-Lr6zt7_o6-b2Y05XdX0amc9wviAu_L2DdcFJGEA5BVqJoUGsT9_KZ5EuVgQxkSwyrLrg9EZSO?key=c4R9UCwhSEC89wzPsj5Vf7kw" alt="An existing equipment record is shown expanded."><figcaption><p>To select an existing equipment record, expand the record by clicking the arrows next to the device name.</p></figcaption></figure>

## Using Adapters

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfNQT1CRTgA_lcoUCCRv-qnDISxfOPsV-zeD1S60eSWU0jjTIBzgLqvycIM7seiWq2YwW9wAq0iopGa0zkVfX2eInJywfCsiHIpsfr8C4RmxNoIDbyzXHXDawH2DnXYpeccE3ql7A?key=c4R9UCwhSEC89wzPsj5Vf7kw" alt=""><figcaption></figcaption></figure>

1. Remove the screws on the sides of the adapter. We recommend using a small standard screwdriver.
2. Place the adapter into the balance's RS-232 port.
3. Replace the screws to secure the adapter to the balance. Make sure it's secured snugly, but not excessively tightly.
4. Connect the cord into the adapter.
5. Tighten the screws on the cord.

## Balance Settings

Next, configure the balance serial and output settings according to the manufacturer’s instructions. Set the balance to continuous auto-print mode and update the following communication settings if using the RS-232 port:

| Setting      | Recommended Input                                                                                     |
| ------------ | ----------------------------------------------------------------------------------------------------- |
| Baud rate    | 9200 or 9600, depending on your needs. Make sure the AirConsole settings match whatever you set here. |
| Data         | 8 Bits, No Parity, 1 Stop Bit                                                                         |
| Parity       | \<none>                                                                                               |
| Flow control | \<none>                                                                                               |

Update the following settings for both RS-232 and USB ports:



| Setting              | Recommended Input                                                                                                                                                                           |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Auto-print           | About once per second works best, although some balances are automatically set to 1.6 seconds.                                                                                              |
| On stable            | Configure this setting to meet your preferences. Depending on your balance, users might need to click Print when they zero the balance if you configure the balance to only send on stable. |
| Print content        | Only print gross values (for example, 12.000 kg)                                                                                                                                            |
| Print layout: format | Multi                                                                                                                                                                                       |
| Print layout: feed   | Line                                                                                                                                                                                        |

## Vendor-Specific Configuration Information

The following table suggests vendor-specific setting recommendations and direct you to futher vendor-provided information. Contact your balance vendor if you have specific questions about that vendor's products.



| Vendor                       | Reference Material                                                                                                                                                                       | Specific Recommendations                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A\&D Scales: EJ Series       | [https://weighing.andonline.com/sites/default/files/documents/EJ%20Instruction%20Manual.pdf](https://weighing.andonline.com/sites/default/files/documents/EJ%20Instruction%20Manual.pdf) | <p>Func -> Prt -> 0 (note there is also Pnt which is "," vs ".")</p><p>Func -> PUse -> 0</p><p>Func -> bps -> 2</p><p>Func -> bPtr -> 2</p>                                                                                                                                                                                                                                                                                                                         |
| A\&D Scales: HR-A Series     |    [https://weighing.andonline.com/wp-content/uploads/2024/01/HR-A\_HR-AZ\_Manual\_02.pdf](https://weighing.andonline.com/wp-content/uploads/2024/01/HR-A_HR-AZ_Manual_02.pdf)           | <p>Func -> Prt -> 0 (note there is also Pnt which is "," vs ".")</p><p>Func -> PUse -> 0</p><p>Func -> bps -> 2</p><p>Func -> bPtr -> 2</p>                                                                                                                                                                                                                                                                                                                         |
| Mettler-Toledo Scales        | [https://www.mt.com/us/en/home/library/technical-documentation.html](https://www.mt.com/us/en/home/library/technical-documentation.html)                                                 | None                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| OHAUS Scales: Explorer       | [https://dmx.ohaus.com/WorkArea/showcontent.aspx?id=28112](https://dmx.ohaus.com/WorkArea/showcontent.aspx?id=28112)                                                                     | <p>Menu -> Communication-> RS-232:</p><p>Device Settings:</p><p>Baud: 19200</p><p>Transmission: 8 NONE 1</p><p>Handshake: NONE</p><p>Print Settings:</p><p>Auto-print: Interval (1 second) [could also use On Stable*]</p><p>Some scales may not ask for interval, can set auto-print to continuous</p><p>Print Content: only print result values: "12.000 kg" [Some scales may not ask for value]</p><p>Print Layout: </p><p>Format: MULTI</p><p>Feed:  4 LINE</p> |
| OHAUS Scales: Adventurer     | [https://www.qc-services.com/pdf/AX.pdf](https://www.qc-services.com/pdf/AX.pdf)                                                                                                         | <p>Communication -> RS232 Standard<br>- baud rate: 9600<br>- transmission: 8-NONE-1<br>- handshake: NONE<br><br>Communication -> Print Settings<br>- numeric value only:  ON<br>- print options: PC<br>Communication -> Auto Print<br>- auto print: interval 1s or continuous<br>Communication -> Print Content<br>- result: on<br>- everything else: off<br>Communication -> Format<br>- format: multi line</p>                                                    |
| OHAUS Scales: Pioneer        | [https://dmx.ohaus.com/WorkArea/showcontent.aspx?id=4294989455](https://dmx.ohaus.com/WorkArea/showcontent.aspx?id=4294989455)                                                           | <p>Menu ></p><ul><li><p>RS232:</p><ul><li>Baud = 9600 or 19200</li><li>Transmission = 8-NO-1</li><li>Handshake = None</li></ul></li></ul><ul><li><p>Print Settings: Everything set to OFF except the below</p><ul><li>Print To = PC</li><li><p>Auto Print = On</p><ul><li>Interval = 1s</li><li>Continuous</li></ul></li><li>Result = On</li><li>Line Feed = 4 Line</li></ul></li></ul>                                                                             |
| OHAUS Scales: Scout          | [http://www.scalemanuals.com/ohausmanuals/scout-stx-manual.pdf](http://www.scalemanuals.com/ohausmanuals/scout-stx-manual.pdf)                                                           | <p>Menu ></p><ul><li><p>RS232:</p><ul><li>Baud = 9600 or 19200</li><li>Transmission = 8-NO-1</li><li>Handshake = None</li></ul></li></ul><ul><li><p>Print Settings: Everything set to OFF except the below</p><ul><li>Print To = PC</li><li><p>Auto Print = On</p><ul><li>Interval = 1s</li><li>Continuous</li></ul></li><li>Result = On</li><li>Line Feed = 4 Line</li></ul></li></ul>                                                                             |
| TOMS                         |                                                                                                                                                                                          | <p>A - 1 (19200)</p><p>B - 0 </p><p>C - 0</p><p>D - 0</p><p>E - 0 (2 or ?)</p><p>F - 0</p>                                                                                                                                                                                                                                                                                                                                                                          |
|  Denver Instrument: Pinnacle | [https://www.manualslib.com/manual/1396711/Denver-Instrument-P-114.html?page=4#manual](https://www.manualslib.com/manual/1396711/Denver-Instrument-P-114.html?page=4#manual)             | <p>Menu ></p><ul><li><p>Print</p><ul><li><p>Mode</p><ul><li>Interval > user definable = 1</li></ul></li><li>Format = Type 4</li></ul></li><li><p>System</p><ul><li><p>RS232</p><ul><li>Baud Rate = 9600</li><li>Data bits/Parity/Stop bit = 8 N 1</li><li>Handshake = None</li></ul></li></ul></li></ul>                                                                                                                                                            |

## Balance Troubleshooting

<table><thead><tr><th width="248.73046875">Problem</th><th width="249">Cause</th><th>Solution</th></tr></thead><tbody><tr><td>The balance prints the numbers twice.</td><td><p>Some balances have multiple output settings: Result, Gross, and Net.</p><p><br>This issue can also occur when a balance doesn't send a new line character after the result.</p></td><td><ol><li>Turn off Gross and Net settings. Turn the Result setting on.</li><li>Ensure the Format setting is set to Muti and the Feed setting is set to Line.</li></ol></td></tr><tr><td>A “Connecting to transmitter” message appears.</td><td>The transmitter is not online.</td><td><ol><li>Power cycle the transmitter.</li><li>If the device uses wi-fi, ensure wi-fi credentials are entered correctly.</li></ol></td></tr><tr><td>A “Connecting to balance” message appears.</td><td>The transmitter is online, but it isn’t receiving data from the balance.</td><td><ol><li>Ensure the balance configuration is correct.</li><li>Try adding or removing null modem adapters between the cable and balance.</li><li>Try unplugging all cables and only plug the power cable back in.</li></ol></td></tr><tr><td>A "Device not found /dev/ttyUSB0" message appears.</td><td>Incorrect cable is in use, or the USB port isn't working.</td><td>Verify that the correct cable is being used, or try an alternate USB port.</td></tr><tr><td>A transmitter won't connect to a balance.</td><td>The DNS server can't resolve a domain name.</td><td><p>Work with your DNS server administrator to verify that all of the following domain names can resolve:</p><ul><li>ion.static-pharmetika.com</li><li>api.paysimple.com</li><li>app.atlas.so</li><li>cdn.jsdelivr.net</li><li>cdn.lrkt-in.com</li><li>cdn.mouseflow.com</li><li>firestore.googleapis.com</li><li>firestore.pharmetika.com</li><li>firestore.electriclab.app</li><li>r.lrkt-in.com</li><li>securetoken.googleapis.com</li><li>securetoken.pharmetika.com</li><li>securetoken.firebaseio.com</li><li>www.googleapis.com</li></ul></td></tr></tbody></table>



