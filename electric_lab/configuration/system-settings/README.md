# System Settings

<figure><img src="../../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

### Formulas

* **Number of Reviewers Required:** The default number of reviewers is set to 1, but pharmacies can change it to require two lab pharmacist reviewers if needed. Any changes to a formula will require approval from a pharmacist. If one pharmacist creates a formula, a second pharmacist must approve it.
* **Enable Unit Dose Label:** This will enable the config section on the master formulation page that will allow users to customize the unit dose label.

### Lots

* **Decimal Rounding Places:** Adjust this setting to your pharmacy's desired decimal rounding place.
* **Allow Beyond Use Date Modification:** Allows users to change BUD to a day less than the calculated BUD during the create lot/pharmacist check lot step.
* **Allow Technicians to Scrap Lots:** This will allow technician to discard lots, which will also discard all ingredients weighed for said lot.
* **Disallow Manual Measurements in Tasks:** This applies to record weight tasks types. When allowed, it allows technicians to manually enter the weight on the scale/balance.
* **Disallow Editing Formula Task Data in Review:** When allowed, tasks that are marked to record a weight/measurement will not be editable when the batch lot is in **Ready for Review** status.
* **Balance Timestamp Must be Within 10 Seconds:** After placing weight on balance, allows the recording to be required to be made within ten seconds.
* **First Measurement for Lot Must Be Zero:** Requires users to record 0 before recording ingredient weight.
* **Liquid Measurement Variance (%):** The tolerance threshold acceptable to pharmacy in percent±.
* **Warn When Scanning Lots With BUD Less than Stability Span:** When enabled, a warning will pop up telling the technician that the ingredient scanned has a BUD less than stability span, and will ask if they want to continue. The stability span will adjust accordingly to match.

### Labels

* **Include GS1 QR Code on Formula Lots:** This code can include the NDC, lot number, and expiration date. Hospital-use only.&#x20;
* **Include GS1 QR Code on Ingredient Lots:** This code can include the NDC, lot number, and expiration date.  Hospital-use only.
* **Include Formula ID:** Allows the pharmacy to disable their unique ID on batch labels.
* **Restrict Reprinting of Labels to Pharmacist:** When enabled, only pharmacist users can reprint lot batch barcodes.
* **Disable Border on Unit Dose Labels:** Add/remove border on the unit dose label.

### Inventory

* **Require Purchase Price:** When enabled, this setting will require a user to enter a purchase price when adding ingredient inventory.
