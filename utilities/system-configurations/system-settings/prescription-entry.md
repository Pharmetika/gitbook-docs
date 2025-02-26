# Prescription Entry

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-25 at 4.10.21 PM.png" alt=""><figcaption></figcaption></figure>

### Prevent verifying Rxs with expired DEA Number

Will prevent verification of the prescription entry when the provider’s DEA is expired.

### Prevent verifying Rxs with expired State License

Will prevent verification of the prescription entry when the provider's license is expired.

### Display Full Formula Description

Will display the Formula name from ElectricLab along with the Label Description name when searching for products in prescription entry.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 2.02.17 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Require reason for compounding

Require all prescriptions for compounded products to have a Reason for Compounding to verify the prescription entry. The reasons will be in a drop down menu on the prescription entry.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 2.03.49 PM.png" alt="" width="375"><figcaption></figcaption></figure>

### Disable fill upon verification

Will hide the fill upon verification checkbox from prescription entry.&#x20;

### Enable transfer upon verification

Will enable the transfer upon verification checkbox from prescription entry.&#x20;

### Require workflow selection

Require all prescriptions to have a workflow selected to verify the prescription entry.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2024-11-26 at 2.07.21 PM.png" alt="" width="350"><figcaption></figcaption></figure>

{% hint style="info" %}
Review [Configuring Custom Workflow](../workflows/configuring-custom-workflow/) on how to create and attach custom workflows.
{% endhint %}

### Dispense Queue Rows Retrieved

Set # of rows retrievable in the dispensing queue.

{% hint style="info" %}
The system will default to 5000 rows. If there are more dispensing rows than the set number of rows retrievable, the system will display the set number of tasks by priority level, then by oldest to newest.&#x20;
{% endhint %}

### After Prescription Entry Verification

Select “Go to patient profile”, “Go to prescription entry queue”, or “Go to Dashboard”&#x20;

Once a prescription is verified by a pharmacist in prescription entry verification, the system will open up the selected destination.&#x20;

### Default Days Supply

Set the default day supply, Ex: 30 days. This set day supply will display on prescription entry.

### Default Rx Entry Queue Date Range (Days)

Set the default date range for the prescription entry queue. They system will default to 7 days automatically.&#x20;
