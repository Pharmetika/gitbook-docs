# Fills

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-25 at 4.23.25 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Voidable Range (Days)

This setting will set the max days to allow voiding of prescription fills from the dispensing queue based on date filled, ex: 90 days from the date filled into the dispensing queue. After the set voidable range day, the filled prescription may not be voided in the dispensing queue. &#x20;

### Default Date Ready By (hours)

This allows pharmacies to set a default “Default Date Ready By (hours)”. This feature streamlines the workflow by eliminating the need to manually select a “Ready By” date during prescription entry or on the fill page. The system will automatically set the “Ready By” date based on the entered timeframe. For example, if 48 hours is set, the system will default the “Ready By” date to two days from the fill date.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 2.21.40 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### Lockout dispensing queue by patient

Prevents users from opening all tasks in the dispense queue for the same patient. When a user opens a dispensing task for a patient with multiple dispensing tasks, all dispensing tasks will be locked while the user completes the dispensing tasks for that patient. This setting will only apply to the dispensing queue.&#x20;

{% hint style="info" %}
<img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 2.48.12 PM.png" alt="" data-size="original"> An icon will appear next to the locked task, hover over the icon to view the user currently in the task.&#x20;
{% endhint %}

### Lockout dispensing queue by Order

Prevents users from opening all tasks in the dispensing queue for all prescriptions and patients associated with an order. When a user opens a dispensing task for a patient within an order, all dispensing tasks will be locked for that specific order number while the user completes all dispensing tasks in the order. This setting will only apply to the dispensing queue.

### Always display prescriber fill note

If checked, this setting will always display the prescriber fill note in the dispensing queue. This note can be updated on the provider profile under “Display when filling notes”.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 3.10.01 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Enable Take Photo for Dispensing Button

If checked, this setting will display the Take Photo button at dispensing to capture images.&#x20;

{% hint style="info" %}
Review [Capturing Product Images During Dispensing](../../../pharmacy/dispensing/capturing-product-images-during-dispensing.md)
{% endhint %}

### Require supervising RPH for technicians to dispense

Requires technicians to set their supervising pharmacists when working in the dispensing queue. If a pharmacist's username is not selected prior to a technician dispensing, the technician will receive the following error "No Supervising Pharmacist Selected".&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 3.19.21 PM.png" alt="" width="339"><figcaption></figcaption></figure>

The supervising pharmacist's username is chosen at login and remains assigned for the entire time the technician is logged in. Upon logging out and back in, the supervising pharmacist will need to be selected again.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-12-03 at 3.15.25 PM.png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Screenshot 2024-12-03 at 3.15.39 PM.png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="info" %}
Setting supervising pharmacists is important for dispensing technicians if the pharmacy has the technicians rotating stations. The supervising pharmacist will show on the prescription label.&#x20;
{% endhint %}

### Require 'bill to' on fills

Requires “bill to patient” or “bill to organization” on all fills before filling. The bill to party "Patient" will be selected by default.&#x20;

### Unset 'bill to' by default

The user will be required to select a “Bill To” option before filling. The bill to party "Cash" will be selected by default. The user will then need to select to bill to patient or bill to organization.&#x20;

### Suppress $0 warnings for products with a price plan set

Removes the warning when filling prescriptions for a product that has a price plan attached set to $0.

### Prompt to print a monograph on the first fill of a prescription

Prompts the user to print the monograph for the product dispensed when filling for the first time. Must be attached to medications on the Product page in the “monograph link” section.&#x20;

### Allow reconciling order from verify screen

When the last dispensed item is verified by a pharmacist and scanned into order reconciliation for the order, a ‘Reconcile Order’ button will appear on the screen. After clicking this button, it will complete order reconciliation for the order and send it to the pre-selected hand-off method from the order. Another pop-up will appear to invoice and charge the credit card in the order if needed.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 3.45.48 PM.png" alt="" width="309"><figcaption></figcaption></figure>
