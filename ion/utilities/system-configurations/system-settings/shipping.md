# Shipping

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-25 at 3.41.35 PM.png" alt=""><figcaption></figcaption></figure>

### Require Signature When Shipping C2s

This will default the shipment to require a signature when sending out a CII prescription.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 1.41.14 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Require Adult Signature When Shipping C2s

This will default the shipment to require a signature from someone 18 years or older when sending out a CII prescription.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 1.40.41 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Insurance required When Shipping Over

Set a minimum price to require insurance for high dollar shipments. During shipping, the user will be notified if insurance is not added for packages with contents exceeding the minimum price.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 1.43.29 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Automatically print prescription manifest after creating shipment

This will default to automatically print the prescription manifest after creating the shipment, the manifest includes all prescriptions filled for the patient.

*   #### Print for orders only

    This will default to automatically print only the orders manifest after creating a shipment. In order for this configuration to work, the pharmacy must select to automatically print the prescription manifest after creating a shipment, then select to only automatically print for orders only.

{% hint style="info" %}
The setting “automatically print shipping label after creating shipment” must be selected to automatically print prescription and order manifests. A local printer must be chosen in [Local Settings](../../local-settings.md) if the printer is connected via USB or transmitter to automatically print. If the printer is connected via [BrowserPrint](../../../supplemental-guides/installing-browserprint/), a local printer does not need to be selected to automatically print.
{% endhint %}

### Use legacy prescription manifest

This will set the pharmacy to print Legacy Prescription Manifests. Legacy manifests are an older version of the manifest that has been updated to the Modern manifest. Please select the manifest style based on the pharmacy’s preference.&#x20;

Legacy Manifest

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-25 at 3.54.36 PM.png" alt="" width="563"><figcaption></figcaption></figure>

Modern Manifest

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-25 at 3.53.06 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Show pricing on prescription manifest

When selected, the pricing for each prescription filled for the patient will display along with any discounts, tax, and shipping charges. The total price of the order will be calculated along with the balance due if the full payment has not been collected.&#x20;

{% hint style="info" %}
If the patient pays their provider and not the pharmacy directly the pharmacy should not check this setting to display. The price will show on all manifest regardless of the Bill To assigned.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-25 at 3.57.34 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Automatically print shipping label after creating shipment

This will default to automatically print the shipping label once the shipment is created.&#x20;

{% hint style="info" %}
The setting “automatically print shipping label after creating shipment” must be selected to automatically print prescription and order manifests. A local printer must be chosen in [Local Settings](../../local-settings.md) if the printer is connected via USB or transmitter to automatically print. If the printer is connected via [BrowserPrint](../../../supplemental-guides/installing-browserprint/), a local printer does not need to be selected to automatically print.
{% endhint %}

### Display link to payments after creating shipment

A link to the patient/organization payment page will display in the shipment window after the shipment is created regardless if there’s an amount due or not.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-25 at 4.01.17 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Bill for shipping upon label creation

A charge item will be added to the assigned payee's payment summary page once a shipment is created.

* **Shipping cost**
  * Select “Use actual shipping cost” or “Use handoff method price”
    * If “use actual shipping cost” is selected, the shipping cost will reflect the actual price of shipping.
    * If “use handoff method price” is selected, the shipping cost will reflect the handoff price set by the pharmacy in Handoff Methods.

{% hint style="info" %}
When selecting to bill for shipping upon label creation, the shipping cost selection must be chosen.
{% endhint %}

### Bill for shipping on non-order items

To allow users to add shipping charges for shipments that aren’t part of an order, select the **Bill For Shipping On Non-Order Items** checkbox. Then, choose one of the following:

* Select the **Non-Order Items: Apply to Organizations** checkbox to apply this setting to shipments billed to organizations.
* Select the **Non-Order Items: Apply to Patients** checkbox to apply this setting to shipments billed to patients.
* Select both checkboxes to apply this setting to all shipments that don’t use an order.

When a new shipping charge is created for an item that doesn’t use an order, the system associates the charge with the item using a unique identifier. You can match shipping charges to items by running the Transaction Itemized Report and matching the row with a value in the **Shipment Identifier** column with a row using the identical value in the **Payment Transaction Shipment Identifier** column. Note that transactions don’t appear on the Fill Report, so you can’t use that report for this reconciliation process.

### Create $0 shipping charges

A shipping charge of $0 is created as a placeholder for if the pharmacy wants to manually enter a different shipping price after the shipping label has been created.
