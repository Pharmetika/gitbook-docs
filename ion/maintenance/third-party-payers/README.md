# Third Party Payers

If you bill directly to insurance plans, you can submit prescription claims directly to them from Pharmetika. To enable this feature, contact [education@pharmetika.com](mailto:education@pharmetika.com) to get started.

## Adding a Third-Party Payer to the System

After you’ve enabled third-party payer billing, complete the following steps to set up the feature in your system.

{% hint style="info" %}
When you enter the payer’s IIN and PCN in steps 4 and 5, verify that they are correct before you save the new payer entry. These two fields cannot be edited after you save the payer. If you need to change the value in either field, you must create a new payer record and archive the existing one.
{% endhint %}

1. Follow the path **Maintenance** > **Third Party Payers**.
2. To add a new payer, click the **Add New Payer** button.
3. Enter the name of the payer in the **Name** field. This is the name that appears to the pharmacy user in the system.
4. Enter the payer’s Issuer Identification Number (IIN) in the **IIN** field. If this number has fewer than eight digits, add zeros at the beginning of the number until you reach eight digits. For example, if a payer’s IIN is 123456, append two zeros to the number and enter 00123456 in this field.
5. Enter the payer’s Processor Control Number (PCN) in the **PCN** field.
6. Click **Create New** to save your changes.

<figure><img src="../../.gitbook/assets/Manage Third PArty Payer.png" alt=""><figcaption></figcaption></figure>

## Adding a Patient’s Insurance to Their Profile

{% hint style="info" %}
After you add a payer to a patient’s profile, you can edit the values in the **Cardholder ID** field and the **Group** field. However, you cannot change the payer. To replace an existing payer, click **Add Payer** and add a new payer record to the profile, then archive the existing payer record.
{% endhint %}

1. In the Patient Profile, locate the **Payer Accounts** section.
2. Click **Add Payer.**
3. In the **Add Payer Account** window, enter the payer’s name or IIN in the **IIN** or **Name** field and select the payer you want to add.
4. In the **Relationship** field, enter the relationship that the patient has to the payer’s primary subscriber. For example, if the patient is the subscriber, select a value of Self.&#x20;
5. Enter the subscriber ID number of the subscriber in the **Cardholder ID** field.&#x20;
6. Enter the group number of the policy in the **Group** field.
7. If the patient is not the only person covered under the policy, enter the individual’s ID in the **Person Code** field. This ID is assigned to the patient by the insurance company based on the birth order of the subscriber's dependents.
8. Click **Submit** in the **Update Payer Account** window.
9. Currently, the **Worker’s Comp Info** button is not recommended, because the feature isn’t yet available. Do not click this button.

<figure><img src="../../.gitbook/assets/Update Payer Account.png" alt=""><figcaption></figcaption></figure>

## Submitting a Prescription Claim to Insurance

1. Open the prescription for filling.
2.  Verify that all the following conditions are met before continuing:&#x20;

    * The patient has a date of birth, address, and gender documented in the **Patient Profile**. If this condition isn't met, add these pieces of information.

    &#x20;![](<../../.gitbook/assets/Demographics (1).png>)

    * The prescriber has an NPI number on file.&#x20;

    ![](<../../.gitbook/assets/Prescriber's NPI.png>)&#x20;

If this condition isn’t met, open the Prescriber Profile for the prescriber and add this information in the **NPI** field.

&#x20;![](<../../.gitbook/assets/Verify NPI.png>)

* The **AWP** value appears and the product is linked to a price plan that populates the **Price** field. ![](<../../.gitbook/assets/AWP and pricing during fill.png>)&#x20;

If this condition isn’t met, verify that the product is attached to a price plan. ![](<../../.gitbook/assets/Pricing Plan field (1).png>)

If so, open the prescription in the **Prescription Entry** activity and verify that the override price is not set. ![](<../../.gitbook/assets/Override price.png>)

3. In the **Options** section, select a hand-off method in the **Hand-off** field.
4. In the **Pricing** section, select the third-party payer in the **Bill To** field.

<figure><img src="../../.gitbook/assets/Bill To field for insurance.png" alt=""><figcaption></figcaption></figure>

5. Click the **Show Additional Fields** button.

<figure><img src="../../.gitbook/assets/Show Additional Fields button.png" alt=""><figcaption></figcaption></figure>

5.  In the window that appears, enter necessary information for the insurance claim. The most commonly needed fields are:

    * **Level of Effort.** This field is usually required for insurance claims. This field appears on the **PA & Claim Info** tab.

    &#x20;![](<../../.gitbook/assets/Level of Effort.png>)

    * **SCC.** This field contains the submission clarification code (SCC) for the claim. It needs to be set to 08-Process Compound For Approved Ingredients if you are submitting a claim for individual covered ingredients. This field appears on the **DUR/PPS** tab.![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXew2pEiY5BeV0zg4PGiJTUT_V8P0TGEC5NqUCZ25M63A4KUFJVolK7qEV08TNnIGy8NzIe0_EkezYPdDxk4GeIUqrZJCF3fz9etRDDxdatg4Xk5TilCpI25mHY7pv1FYvRWgUBA?key=4NAA0PKfeF_lDYxkg9FnDg)
    * **Compound Ingredients.** Click the tab and verify that all ingredients contain a numeric value equal to or greater than $0.01 in the **AWP** column. If the value in this column appears as NaN, that ingredient isn’t linked to a valid AWP and can’t be submitted to the third party. If you see an ingredient with a value of NaN in this column, copy the NDC of the ingredient, open the ingredient’s product in ION (**Maintenance** > **Products**), and review the entry to ensure the information in the **Pricing** section is complete.

    &#x20;

    <figure><img src="../../.gitbook/assets/Ingredients with NaN AWP.png" alt=""><figcaption><p>In this example, the claim is rejected, not only because the AWP appears as NaN for all ingredients, but also because one ingredient has an invalid 10-digit NDC.</p></figcaption></figure>
6. Close the window by clicking **Done**.
7. Click **Fill** to fill the prescription. When you click this button, the system submits the claim to the third-party payer. If the claim doesn’t include rejections, the results of the claim appear and the user can accept the claim and fill the prescription or decline the claim and return to the fill entry.

## Troubleshooting Insurance Claim Submissions

### Issue: Claims aren’t being processed or are being rejected when I don’t expect them to be.

If you’re seeing claims rejected, follow these steps to check whether the correct information is included in the claim:

1. Open the product in ION (**Maintenance** > **Products**).
2. Verify that a valid NDC is entered in the **NDC** field.
3. Verify that the **AWP** field contains a value equal to or larger than $0.01.

### Issue: The Average Wholesale Price (AWP) is showing as zero.

When you fill a prescription and submit it to a third-party payer, it must have an associated AWP of greater than or equal to one cent in order to be processed. If the AWP is appearing as zero, verify that a value is entered in the AWP field for the product. Verify also that the override price is not set or is set to a non-zero value in the prescription in the **Prescription Entry** activity.

### Issue: I’m seeing an error code I don’t understand.

The most common error codes pharmacies receive include:

* **70-Product/Service Not Covered.** This code indicates that the product isn’t covered by the insurance plan. If you receive this code, you can try using SCC code **08-Process Compound For Approved Ingredients** to request approval for each individual ingredient. However, it is still possible that the plan does not cover the ingredients.
* **8B-Missing/Incomplete DUR/PPS Level of Effort.** This code indicates that the Level of Effort associated with the product is either blank or invalid. To fix this issue, void the original fill, re-open the prescription in the Fill activity, and click the **Show Additional Fields** button in the Pricing section. Then, select the **PA & Claim Info** tab and enter or adjust the value in the **Level of Effort** field.

### Issue: I’ve tried everything and the claim is still not being processed as expected.

If you’ve tried these troubleshooting steps and the claim is still not being processed, contact [education@pharmetika.com](mailto:education@pharmetika.com). We can work with you to determine the origin of the issue.
