# System Settings

<figure><img src="../../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

### Formulas

* **Number of Reviewers Required:** This setting determines how many reviewers are required to approve changes to formulas. The default number of reviewers is set to 1, but pharmacies can change it to require multiple lab pharmacist reviewers if needed. Any changes to a formula require approval from a pharmacist, not including the user who originally made the change. If one pharmacist creates a formula, a second pharmacist must approve it.
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

* **Label Dimensions:** In this dropdown menu, select the label size you want to use for medications compounded at your pharmacy. Currently, options are:
  * 2 in X 2.725 in
  * 1.5 in X 3.5 in
* **Include GS1 QR Code on Formula Lots:** This code can include the NDC, lot number, and expiration date. Hospital-use only. To show the GS1 QR code on all labels, enable both this setting and the one below it.
*   **Include GS1 QR Code on Ingredient Lots:** This code can include the NDC, lot number, and expiration date.  Hospital-use only. To show the GS1 QR code on all labels, enable both this setting and the one above it.



    <figure><img src="https://uploads.linear.app/69e24f9b-f5a9-47e4-a628-b708d14729e2/00b2abcf-371b-4fbd-92eb-81637abb746c/bcbc4d7b-3926-45e3-ac96-97473dbf35ce" alt="A GS1 QR code appears in the corner of a label for compounded diltiazem 2% ointment."><figcaption><p>When both of the GS1 QR code settings are enabled, the GS1 QR code appears on your labels.</p></figcaption></figure>
* **GS1: Include Quantity:** This setting appears when both the **Include GS1 QR Code on Formula Lots** setting and the **Include GS1 QR Code on Ingredient Lots** setting are enabled. Enable this setting to include the quantity in the GS1 code that appears on the label.
* **GS1 Include Date Compounded:** This setting appears when both the **Include GS1 QR Code on Formula Lots** setting and the **Include GS1 QR Code on Ingredient Lots** setting are enabled. Enable this setting to include the compounding date in the GS1 code that appears on the label.
* **Include 1D Lot Barcode:** Enable this setting to show the 1D lot barcode on your labels. If you enabled the settings above to show the GS1 barcode on labels, we recommend disabling this setting, because the 1D lot barcode is included in the GS1 QR code.
* **Include Formula ID:** Allows the pharmacy to disable their unique ID on batch labels.
* **Restrict Reprinting of Labels to Pharmacist:** When enabled, only pharmacist users can reprint lot batch barcodes.
* **Disable Border on Unit Dose Labels:** Add/remove border on the unit dose label.

### Inventory

* **Require Purchase Price:** When enabled, this setting will require a user to enter a purchase price when adding ingredient inventory.
