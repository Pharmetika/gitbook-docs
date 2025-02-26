# Payments

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-02 at 11.36.07 AM.png" alt=""><figcaption></figcaption></figure>

### Unbilled items

Select “Use estimated tax”, “Use calculated tax”, or “Exclude tax”.

* Estimated tax will be the tax displayed when “Use Estimated Tax” is selected in the Tax Settings.
  * See Tax Settings for tax by state. Each state that requires the use of estimate tax will need to be configured under the tax settings.&#x20;
* Calculated tax will be the tax calculated by Avalara AvaTax.
  * If the pharmacy chooses to enable sales tax with Avalara AvaTax, the pharmacy must signup with Avalara then provide Pharmetika with the API information.&#x20;

### Price Rounding

Select “To Nearest Dollar”, “To Nearest $0.50”, “To Nearest $0.25”, or “No Rounding”. &#x20;

* When selected, the price of each item will round to the desired rounding amount during filling.&#x20;

{% hint style="info" %}
If a prescription has been filled before updating the price rounding setting, the price will not reflect the change. This will only be updated for future fills.&#x20;
{% endhint %}

### Hide compound components on prescription info sheet

When selected, the prescription details including the Description, NDC, Quantity, Units, and AWP will be hidden on the prescription information sheet.&#x20;

The prescription information sheet can be found on the prescription dispense entry then selecting the information form.&#x20;

### Always display organization billing status on Rx history

When selected, the organization billing status will display on the patient summary page.

The organization icon will display next to the prescription number and the organization name will display when hovering over the icon.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-02 at 11.43.07 AM.png" alt="" width="198"><figcaption></figcaption></figure>

### Disable Payment Functionality for Clinic/Company Patient Profiles

For patient profile marked as Is Clinic/Company, the option to add a payment source on file will be disabled if this setting is checked off.&#x20;

### Default Payment Method Options

Will display additional payment method options when invoices are marked as paid.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-02 at 11.44.29 AM.png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="info" %}
Cash, office payment, and other will automatically be payment system options. Review [Creating Custom Payment Stations](../../../../patient/payments/creating-custom-payment-stations.md) on how to use these payment systems in workflow.
{% endhint %}
