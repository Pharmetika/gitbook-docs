# Provider Portal

<figure><img src="../../../.gitbook/assets/Screenshot 2024-12-04 at 2.12.16 PM.png" alt=""><figcaption></figcaption></figure>

### Enable EPCS for new providers by default

When a provider portal is created the providers menu option to request an EPCS 2FA token will automatically be enabled when checked off.&#x20;

{% hint style="info" %}
Practitioners using the provider portal to submit controlled substances will be required to use an EPCS 2FA token.&#x20;
{% endhint %}

### Display Information Form

When selected, the prescription information form will be displayed in the provider portal.

This form may be used by patients or providers to apply for insurance reimbursement.

{% hint style="info" %}
Some pharmacies may use this for providers to submit for workers compensation or personal injury claims.
{% endhint %}

### Allow Setting Priority on Medication Requests

The provider will be able to select the priority of the incoming medication request. This request will display in the prescription entry queue with the priority the provider selected.&#x20;

### Allow Setting Bill to on Medication Requests

The provider will be required to select “Bill to Patient” or “Bill to Organization” on all prescriptions.&#x20;

### Allow Setting Reason for Compounding on Medication Request

The provider will be able to select the reason for compounding on prescriptions.&#x20;

### Hide Inventory Availability

Will hide the inventory availability for the medication requested on the RxPad. If inventory availability is not hidden, “Compounding Required” or "Inventory Available" will display on the RxPad when providers are submitting prescriptions.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot 2024-12-02 at 12.09.21 PM.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Screenshot 2024-12-02 at 12.10.01 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Display Product Pricing

When prescribing, the provider will see the product pricing on the RxPad after selecting the Medication, Dose and Quantity.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-12-02 at 12.11.15 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Handoff Methods

The pharmacy can choose to not display handoff methods, use pharmacy system handoff methods, or generic handoff methods.&#x20;

* Require handoff method
  * The provider will be required to select a handoff methods when sending prescriptions.&#x20;

{% hint style="info" %}
Pharmacy system handoff methods are created by the pharmacy. When the option to use these methods is enabled, a checkbox will appear within the handoff methods section, allowing them to be displayed in the portal.

&#x20;                                      <img src="../../../.gitbook/assets/Screenshot 2024-12-02 at 12.16.56 PM.png" alt="" data-size="original">
{% endhint %}

### Prescription requirement settings

When these settings are enabled, the patient profile must meet the specified criteria for the provider to successfully send a prescription through the portal. If any required information is incomplete when attempting to submit a prescription, an error message will appear, detailing the reason for the missing requirement.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-12-02 at 12.20.47 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Limit Visibility of Patient Rx History to Prescriptions from Provider's Clinic

When selected, the providers in the portal will only be shown prescription history that was sent from the providers clinic.

{% hint style="warning" %}
The Cures Act defines information blocking as a practice that interferes with the access, exchange, or use of electronic health information (EHI). The Cures Act's information blocking regulations went into effect in April 2021 and apply to providers and health IT developers. Use of this feature may violate these regulations and should be carefully considered. By enabling this feature the pharmacy agrees to be liable for any penalties, damages, or consequences as a result of information blocking.
{% endhint %}
