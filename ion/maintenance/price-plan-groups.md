# Price Plan Groups

Price plan groups allow your pharmacy to update and manage a large volume of price plans across multiple locations. This feature is especially useful for pharmacies that use tiered pricing or other complex pricing methods and want a quick way to update price plans across multiple organizations at the same time.

The system evaluates whether to use a price plan using the following hierarchy:

1. Is a price plan attached to the specific product at the organization level? If yes, the system uses that price plan. If not, it moves to the next step.

<figure><img src="../.gitbook/assets/Pricing plan first.png" alt=""><figcaption></figcaption></figure>

2. Is a price plan associated with the specific product in a price plan group attached to the organization? If yes, the system uses that price plan. If not, it moves to the next step.

<figure><img src="../.gitbook/assets/Pricing plan first copy.png" alt=""><figcaption></figcaption></figure>

3. Is a price plan attached to the specific product at the product level? If yes, the system uses that price plan. If not, it moves to the next step.

<figure><img src="../.gitbook/assets/Price Plan tier 3.png" alt=""><figcaption></figcaption></figure>

4. Is a price plan entered in the **Default Price Plan** field in the organization? If yes, the system uses that price plan. If not, it moves to the next step.

<figure><img src="../.gitbook/assets/Pricing plan first copy (1).png" alt=""><figcaption></figcaption></figure>

5. The system uses the price plan entered in the **Default Price Plan** field in the **System Settings** section of **System Configuration.**

<figure><img src="../.gitbook/assets/Price Plan tier 5.png" alt=""><figcaption></figcaption></figure>

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
