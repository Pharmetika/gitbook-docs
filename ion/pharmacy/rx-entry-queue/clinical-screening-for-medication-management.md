# Clinical Screening for Medication Management

## Synopsis

Clinical screening is a real-time tool that screens prescriptions to identify potential medication-related issues, such as interactions, allergies, or intolerances. It helps reduce the risk of adverse drug events by providing alerts. Additionally, it logs all accepted issues and corresponding pharmacist notes to ensure compliance with regulatory standards, enhancing patient safety and improving the overall verification process.

**The clinical screening offers a range of services, including:**

* Drug-Food Interactions
* Drug-Allergy Interactions\*
* Drug-Drug Interactions
* Drug Pricing
* Drug Compendia
* Patient Education Handouts/Monographs
* Auxiliary labels for trade products
* Allergies
* Trade Product Physical Descriptions, not images
* Inactive Ingredient Screening\*\*

**Some exclusions:**

* Duplicate Therapy\*\*\*
* Drug-Disease Interactions
* Pregnancy and Lactation

\*Pharmacies will select severity for clinical screening.

\*\*Inactive ingredients with no NDC such as **color additives** (e.g., FD\&C color additives) and products containing **latex** which are sometimes found in medical products . It is necessary to review the package insert and manually screen the prospective drug. However, for compounds the listed NDCs will be screened. For example, if a patient has a dairy allergy listed and the compound contains lactose, a warning will appear on the clinical screening check.

\*\*\*In compounding there may be many duplicate therapy warnings even when both therapies are appropriate. Sometimes, providers send a new prescription for each refill, which can also trigger a duplicate therapy warning.

## Managing Clinical Screening Settings

Navigate to Utilities > System Configuration > System Settings > Clinical Screening Options

{% hint style="info" %}
NOTE: Upon deployment, clinical settings will be disabled by default and should be activated based on the preferences of the pharmacy.
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-10 at 9.25.41 AM.png" alt=""><figcaption></figcaption></figure>

### Enabling Clinical Screening During Prescription Entry Verification

When clinical screening is turned off during prescription entry, the pharmacist will not receive pop-up alerts or hard stops for any DUR issues. However, the pharmacist can manually review DURs by clicking the "Show DURs" button located in the top right corner (refer to the image below) and selecting the "DUR Performed" checkbox as necessary.

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-10 at 9.29.56 AM.png" alt="" width="316"><figcaption></figcaption></figure>

### Enabling Clinical Screening During Prescription Fill

When this setting is unchecked, an orange button labeled "Click to view unaccepted DURs" will appear on the fill entry after clicking the Fill button. There will be no pop-up alerts or hard stops during the process, meaning the pharmacist can manually check for unaccepted DURs without any automatic interruptions.

<figure><img src="../../.gitbook/assets/image (558) (1).png" alt="" width="563"><figcaption></figcaption></figure>

### Enabling Inactive Ingredient Screening for Trade Products

Select "Screen Inactive Ingredients" to activate the screening process for inactive ingredients in trade products.

### Setting Up Clinical Screening Severity Levels

This configuration allows pharmacists to prioritize which Drug Utilization Review (DUR) alerts will display during prescription verification and filling based on severity selected. Customizing the visibility of these severity levels helps pharmacies streamline their workflow, enhance efficiency, and ensure compliance with their specific operational needs.

When you select a severity level, it will display all issues of that level and those more severe. For instance, choosing level 3 will show alerts for severity levels 3, 2, and 1.

#### The following table displays the professional values and descriptions:

<table data-full-width="false"><thead><tr><th width="112">Severity</th><th width="185">Severity Description</th><th width="235">Severity Level Implications</th><th>Color &#x26; Exceptions</th></tr></thead><tbody><tr><td>1</td><td>Contraindicated Drug Combination</td><td>This drug combination is contraindicated and generally should not be dispensed or administered to the same patient.</td><td>Red</td></tr><tr><td>2</td><td>Severe Interaction</td><td>Action is required to reduce risk of severe adverse interaction.</td><td>Tan</td></tr><tr><td>3</td><td>Moderate Interaction</td><td>Assess risk to patient and act as needed.</td><td>Gray; Food Related Severity 2 Interactions</td></tr><tr><td>9</td><td>Undetermined Severity–Alternative Therapy Interaction</td><td>Assess risk to patient and act as needed.</td><td></td></tr></tbody></table>

## Initiating Clinical Screening on Prescription Entry

The “Show DUR” button will be disabled until a drug/product and a patient have been selected on the Prescription Entry page. When the button is enabled, both pharmacy technicians and pharmacists will have view-only access, the pharmacist can review the prescription details and associated issues without taking any action at this step.

<figure><img src="../../.gitbook/assets/image (551).png" alt=""><figcaption><p>"Show DURs" button is disabled</p></figcaption></figure>

Once the pharmacist marks the prescription as verified at PV1 (Pharmacist Prescription Data Entry Verification) on the Prescription Entry or Prescription Verification page, the same screen will reappear, but this time the DUR will have actionable items. They will be able to record notes, address the flagged issues, and accept them, ensuring proper approval and documentation before completing the prescription verification.

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-07 at 12.24.16 PM.png" alt=""><figcaption></figcaption></figure>

### DUR Results Overview

**New Medications:** The drug/product currently being reviewed or prescribed.

**Active Medications:** Includes medications the patient is currently using, both those being filled and already dispensed from ION.

**Allergies and Intolerances:** Recorded in the patient’s profile, reflecting any known reactions.

**Alerts:** Drug allergies, drug-drug, and drug-food interactions flagged by FDB, with messages such as “No Drug Allergies found” or interaction warnings.

**Issues:** A list of potential interactions or allergic/intolerance reactions that need attention.

### **Recording Notes and Accepting All Issues**

The pharmacist can record notes from DUR interventions, which will be saved after clicking Accept All. These notes will be recorded and available to review from the Edit Entry page once the prescription has been verified and assigned a prescription number.

To review the PV1 (Pharmacist Prescription Data Entry Verification) DUR approval notes, navigate to the Patient Summary page > expand the drug/product entry > click **Edit Entry** > Click the **Click to view accepted DURs** button

<figure><img src="../../.gitbook/assets/image (560) (1).png" alt=""><figcaption></figcaption></figure>

### Managing Clinical Screening During Prescription Entry Verification

After the DUR pop-up appears, if the DURs are not approved and the screen is closed, an orange button labeled "Click to view unaccepted DURs" will appear in the action section. Clicking this button allows review and acceptance of the DURs. Once accepted, the button turns blue and changes to "View accepted DURs," confirming the prescription is ready for verification.

<figure><img src="../../.gitbook/assets/image (561) (1).png" alt=""><figcaption><p>Pending DUR acceptance and prescription verification</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (562) (1).png" alt=""><figcaption><p>Accepted DURs</p></figcaption></figure>

If further information is required or the DURs are not accepted, place the prescription back into the pending status (e.g., clarification status) and follow the pharmacy process for notifying the provider.

## Manually Screening Exclusions

The exclusion list, including drug-disease interactions, duplicate therapy, and pregnancy or lactation status, can be reviewed at the _bottom_ of the Prescription Entry, Verification, or Fill page, provided this information has been recorded in the patient profile at the time of PV1. By reviewing this information, pharmacists can adjust prescriptions and address potential risks before dispensing, with the pharmacy intervening as needed to provide support or alternative treatments.

<figure><img src="../../.gitbook/assets/image (556) (1).png" alt=""><figcaption></figcaption></figure>

**NOTE:** Syringes will be included on the list to check for potential issues. This involves manually reviewing the manufacturer package inserts for latex, which can sometimes be present in syringe components or packaging, to ensure the safety of patients with latex allergies.

<figure><img src="../../.gitbook/assets/image (557) (1).png" alt=""><figcaption></figcaption></figure>

## Clinical Screening at Prescription Filling and for Refills

If potential drug interactions or allergy/intolerance reactions are detected, a clinical screening pop-up will appear after clicking Fill. A pharmacist must be logged in and click **Accept All** to complete the fill. This ensures that only an authorized pharmacist can review and address any issues before finalizing the prescription.

Any recorded notes will be visible on the Fill Entry page under Fill History.

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-07 at 12.27.51 PM.png" alt=""><figcaption></figcaption></figure>

To view the DUR note from the Fill page, click the blue **Click to view accepted DURs** button.

{% hint style="info" %}
Clinical screening notes are specific to each fill. To ensure the correct note is reviewed, check the fill number.
{% endhint %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-10-07 at 12.28.18 PM.png" alt=""><figcaption></figcaption></figure>
