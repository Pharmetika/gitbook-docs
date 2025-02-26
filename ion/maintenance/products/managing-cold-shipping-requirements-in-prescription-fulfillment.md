# Managing Cold Shipping Requirements in Prescription Fulfillment

Users can designate a product as “Requires Cold Shipping” and align it with a handoff method that mandates cold packing to minimize discrepancies during prescription processing. When both settings are activated, the system ensures alignment. For example, if a product is marked for cold shipping but the selected handoff method does not match, the system will generate a **hard stop** during the fill process. The user must adjust the handoff method to meet the cold-shipping requirements before proceeding to complete the fill, ensuring all necessary shipping protocols are followed.

**Note:** The hard stop due to a mismatch applies exclusively to products marked as requiring cold pack shipping.

## Configuring Cold Pack Shipping Requirements for Products

* Navigate to the **Product** page and locate the desired product. In the Product Options section, check the box labeled "Require Cold Pack Shipping" and then click **Save** to confirm the changes.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcJGjkPBN8LVt-OEqeSp32OYV2gRMN0B0O6fRkarLq0GetmKZnhTBnFbB_6lrk01bWWA9AT5TZA5JF1D8qse0SPRmnol12FKevWZXuQgpOiIkG-fo0OdfSdW6OudkxLkyf3jNnd6bbeYvRxl-5C4hGABome?key=B7SPq71ZAfZ9fNSxLWqaQw" alt="" width="563"><figcaption></figcaption></figure>

* Open the **Maintenance** section and open the **Hand-Off Method** page. Locate the shipping method intended for cold packing, then check the "Allow Cold Pack Items" option. Finally, click **Save** to apply the changes.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf58TAws-gOMQrV8q7ZqF8ykcN1qXCEBWx2_KRGkHArkm2UKxyiGiBX4BwriEPKeqeiy6kgG6f4cxLtpSLLIQIIiWokJQIjMFKONSI1yqI2MLKbRK53SPGsKUDyCJ88PsYOM_fI6X9gkwsuARqrgh7eXGWH?key=B7SPq71ZAfZ9fNSxLWqaQw" alt="" width="563"><figcaption></figcaption></figure>

## Example of a Mismatch&#x20;

On the screen, we can see a product that requires cold pack shipping, indicated by the snowflake and thermostat icon. However, the selected handoff method, **FedEx Express Saver**, does not have the "Cold Pack Shipping" option enabled.&#x20;

A warning appears below the Fill button, stating, **"Product Requires Cold Pack Shipping Options"**, and the Fill button is disabled. Once the correct handoff method is selected, the warning will disappear, and the Fill button will become enabled, allowing the process to continue smoothly.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcMhEr0PUg1Mt-c-FK_PuZ_iT1cRGUHTFRM3pAvUQcbECmd6rL5u1EvssP0ve5QGYgSAY51FiekpWYnN6cHopUlet8fvrmJW7LbmsaYl78w-yhvRupSLjB4Hlay4IkUkWy9burIkucEnovEEWhkfgMqK2zx?key=B7SPq71ZAfZ9fNSxLWqaQw" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The handoff drop-down list will automatically disable delivery methods that aren’t configured for cold pack products, ensuring a quick and accurate selection process.
{% endhint %}
