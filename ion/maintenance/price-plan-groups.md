# Price Plan Groups

Price plan groups allow your pharmacy to update and manage a large volume of price plans across multiple locations. This feature is especially useful for pharmacies that use tiered pricing or other complex pricing methods and want a quick way to update price plans across multiple organizations at the same time.

By default, the system evaluates whether to use a price plan using the following hierarchy:

1. Is the prescription billed to the patient? If so, the system skips steps 2 and 3 and proceeds to step 4. If the prescription is billed to the organization, the system moves to the next step.
2. Is a price plan attached to the specific product at the organization level? If yes, the system uses that price plan. If not, it moves to the next step.

<figure><img src="../.gitbook/assets/Pricing plan first.png" alt=""><figcaption></figcaption></figure>

3. Is a price plan associated with the specific product in a price plan group attached to the organization? If yes, the system uses that price plan. If not, it moves to the next step.

<figure><img src="../.gitbook/assets/Pricing plan first copy.png" alt=""><figcaption></figcaption></figure>

4. Is a price plan attached to the specific product at the product level? If yes, the system uses that price plan. If not, and the prescription is billed to an organization, it moves to the next step. If not, and the prescription is billed to a patient, the system moves to step 6.

<figure><img src="../.gitbook/assets/Price Plan tier 3.png" alt=""><figcaption></figcaption></figure>

5. Is a price plan entered in the **Default Price Plan** field in the organization? If yes, the system uses that price plan. If not, it moves to the next step.

<figure><img src="../.gitbook/assets/Pricing plan first copy (1).png" alt=""><figcaption></figcaption></figure>

6. Is a price plan entered in the **Default Price Plan** field in the **System Settings** section of **System Configuration**? If yes, the system uses that price plan. If not, the price is $0.

<figure><img src="../.gitbook/assets/Price Plan tier 5.png" alt=""><figcaption></figcaption></figure>

## Using Organization Pricing for Patient-Pay Billing

By default, the system considers organization-level price plans only for organization-pay prescriptions, as described above. As an example, say a prescriber is linked to organization A, which has a price plan group entered in the **Price Plan Group** field in the organization's profile. The prescriber writes a prescription for product X, which has an attached price plan. If the prescriber bills the prescription to their organization, the system uses the price plan group in the organization's profile, but if they bill the patient, the system uses the product's attached price plan.

However, you can configure the system to use the hierarchy above for all prescriptions, even if they are billed to patients. For example, you might have an agreement with one organization that all their patients receive a special price for semaglutide because that organization regularly places large semaglutide orders with your pharmacy and you want to stay competitive with other local pharmacies. In that case, you'd want to keep the organization-specific pricing for all prescriptions, so that the system always uses the organization-specific price plan or group.

To enable this behavior:

1. Go to **Utilities > System Configuration** and open the **Payments** section.
2. Select the **Apply Organization Pricing to Patient Billing** checkbox.

## Create or Manage a Price Plan Group

To get started, go to Maintenance > Price Plan Groups. Click **Create New Group** to create a new price plan group, or click the **Edit** button to edit an existing price plan group.

Next, update any of the following fields:

1. **Description.** Enter a name for the price plan group here.
2. **Archived.** To archive a price plan group, toggle this setting.
3. **Add Product.** To associate a product with a price plan, enter the product here.
4. **Select Price Plan.** Select the price plan you want to associate with the product you entered in the previous step.
5. **Add.** Click this button to add the product-price plan combination to the group.
6. **Remove.** Click this button to remove a product-price plan combination from the group.
7. **Save.** Click this button to save the price plan group.

<figure><img src="../.gitbook/assets/Manage Price Plan Group annotates.png" alt=""><figcaption></figcaption></figure>

## Link a Price Plan Group to an Organization

1. Go to **Maintenance** > **Organizations**.
2. In the **Manage Organization-level Price Plans** section, enter the price plan group in the **Price Plan Group** field.

<figure><img src="../.gitbook/assets/Price Plan Groups new and edit.png" alt=""><figcaption></figcaption></figure>

