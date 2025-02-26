# Adding Shipment Costs Without Generating an Order Invoice

“Commit and Create Charges” is a way to lock in an order to determine shipping fees (including surcharges) based on the items in the order without generating an invoice. These charges are then applied to the appropriate bill-to party, whether a patient or organization, on the payment page. This will create a charge line item under unbilled items. The shipping cost can be adjusted if items with surcharges are added or removed, or if there is a change in the final shipping or handoff method, such as switching carriers or service levels.

To lock in an order and add shipping fees to the corresponding party’s payment page, follow the steps below.

Create an order by adding the patient’s prescriptions, selecting a handoff method, choosing a bill-to party (patient by default), setting the “Date for Order”, and clicking Submit Order.

\


<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeIQQXvihhL7Dbesv6291OSk5YONqSMRHs6wwoTQ_dx0Qs28ts7jDXXC33IrR_zULL2yv1Z5Lwrb7Gm-lnwm_EqALNyUJj7hW7eeIKG44R7e7dzKt4saaQKuU50eNI5DMzyBu41WKgbtVTFAd59UdrwjjM?key=MARqdIxD-aqncLLvL2IYYGVs" alt=""><figcaption></figcaption></figure>

Once saved, additional action buttons will appear at the bottom to confirm the order has been successfully created.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeGXxWoE80dQUjRGBVq7LI_kZspZimMn2llFYcG7y3PtMf5G7TtgZKWTrsdWQM_W0VB6zHbjvNn9FB_WBqXhld0Z_sh6cqa9A8N7_cLW01f0GZh41mR5Q7QciN1NRhJSqW76NnGZULpEDVKFVUZc5ENV0Sa?key=MARqdIxD-aqncLLvL2IYYGVs" alt=""><figcaption></figcaption></figure>

Clicking Submit Order will save the order, allowing shipping costs to be calculated based on the handoff method and items included. The Commit and Create Charges button will then be enabled for selection.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcANyxmZXY3jx4rtulE_9DYGf5f_7in9jZWnGDhknnV94HmTIL2OkiWYyqpGaiFwpc0xI4wUEFqs9UirJLkERn-IkHS6EnVi3VDWGMEFjQHwrL_waBaKrTnw7VgqMNbXB-D-iLyCU49liEKodYsvDJEbD3l?key=MARqdIxD-aqncLLvL2IYYGVs" alt=""><figcaption></figcaption></figure>

In this example, the shipping method “FedEx Express Saver” is listed at $12.50. However, on the patient’s payment page, the line charge shows $17.75. This difference is due to a surcharge for cold pack shipping applied to one of the items in the order.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcJTzqHl3fFVRDkLmG3F-_iTy4c54O7StRdqwKzM9i96vvGv3gVf5XBb6cEicxagftiX8RH8-9754w5xIUpQneW3AJjfhq8dOWiX_bmpWR8Gdu7TNG3I261fSMye06WA45bO1--gpivNHcQv2CdpNihTQI6?key=MARqdIxD-aqncLLvL2IYYGVs" alt=""><figcaption></figcaption></figure>

To confirm which item has cold pack shipping, check the product page under Product Options. Here, you’ll see Diltiazem 1% Ointment marked for cold pack shipping.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXet_oFDLYSYfWE5-ykFlgv9SDNAWXjN0ACV_yah0r3rBfdHMxjwJiUzlEjjAHLYPXYGkBBRjr_dn4FYrjzNKX-dzXbj7BOgxH1GU2vOnMyQ5jw24-smgTzS7KtQxMYHu6t1QMMNuI9LEo2ATh8ogai7Cafu?key=MARqdIxD-aqncLLvL2IYYGVs" alt=""><figcaption></figcaption></figure>

Next, we can see that the handoff method “FedEx Express Saver” includes a $5.25 surcharge for products requiring cold pack shipping. Combining the base rate of $12.50 for FedEx Express Saver with the $5.25 cold pack surcharge brings the total to $17.75.

<figure><img src="../../.gitbook/assets/Screenshot 2024-11-04 at 1.38.49 PM.png" alt="" width="563"><figcaption></figcaption></figure>

If products with surcharges are added to the order after the shipping cost has been paid, the additional surcharges can still be added as a line item and will be labeled “Shipping Remainder Charge” before completing the order. To add the additional surcharge(s), add the product and simply click the **Commit and Create Charges** button. However, if the shipping cost has not yet been paid, it will update automatically with the most recent changes after clicking **Commit and Create Charges**.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfE4QvMwStLrLhAGQa1ud4Lgizuj74jmlIavQeaPsVaU-IQBogbSydshwiGiNOttfV-BNODjI5PGRNU3dkRohing8LTjfxOFTE0hlW_cTIukEiiTpBQwDHnbZvlTpuQE2NU3Dven5E3fTuM92L7-3dN8LS8?key=MARqdIxD-aqncLLvL2IYYGVs" alt=""><figcaption></figcaption></figure>

If the initial charge has already been paid and a subsequent adjustment reduces the shipment cost, requiring a store credit or reimbursement, click [here ](../../patient/payments/applying-payment-credit.md)to learn more about applying a payment credit.
