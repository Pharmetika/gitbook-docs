# Canceling an Order

After users create and submit an order, they can cancel it at any time or at any stage in the process. See below for a breakdown of the different scenarios and steps involved in canceling an order.

<figure><img src="../../.gitbook/assets/Cancel button for order.png" alt=""><figcaption></figcaption></figure>

## Scenario 1: Removing Unfilled Items and Canceling the Order

This scenario applies when the user needs to cancel or remove items from an order and cancel the order entirely. The following conditions must both apply:

* An invoice has **not** been created.
* The items in the order have **not** been marked to be filled.

### Steps to Cancel or Remove Items and Cancel the Order

1. Navigate to the relevant order that needs to be canceled or adjusted.
2. Scroll to the bottom of the open order page and click the **Cancel** button.
3. In the **Cancel Order** window, select **Remove Items from Order** to remove the items.
4. Then click **Cancel Order** to complete the cancellation process.
5.

    <figure><img src="../../.gitbook/assets/Cancel Order window for orders (1).png" alt=""><figcaption></figcaption></figure>

At this point, the unfilled items will:

* Be available to be linked to a new or added to an existing order and filled from the **Patient Summary** page.
* No longer be linked to the canceled order.

## Scenario 2: Deleting Filled Items and Cancelling the Order

This scenario applies when the user needs to delete items that have already been filled and cancel the associated order. The following conditions must both apply:

* An invoice has **not** been created.
* The items in the order have already been marked as **filled**.

<figure><img src="../../.gitbook/assets/Filled iterms for cancelled order.png" alt=""><figcaption></figcaption></figure>

### Steps to Delete Filled Items and Cancel the Order

1. Navigate to the relevant order that contains the filled items.
2. Scroll to the bottom of the open order page and click the **Cancel** button.
3. In the **Cancel Order** window, select **Remove Items from Order** to remove the items.
4. Then click **Cancel Order** to complete the cancellation process.

Because the items have been marked as **filled**, they will:

* Remain in the Fill Status and display in the Dispense Queue.
* Appear on the patient's **Payments** activity in the **Unbilled Items** section.
* However, the items are no longer linked to the canceled order.



5. Add the filled items to a new order or an existing order, as their fill status remains intact.

## Scenario 3: Deleting Filled Items, Deleting an Invoice, and Cancelling the Order

This scenario addresses the process of deleting filled items, deleting the associated invoice, and cancelling the order when both of the following conditions are met:

* An invoice has been created.
* &#x20;Items have been filled.

{% hint style="info" %}
It is important to note that invoices should ideally be created only after items have been filled to ensure they include the items and any applicable shipping charges.
{% endhint %}

### Steps to Delete Filled Items, Delete the Invoice, and Cancel the Order

1.
2. Navigate to the relevant order that contains the filled items.
3. Scroll to the bottom of the open order page and click the **Cancel** button.
4. In the **Cancel Order** window, select **Remove Items from Order** to remove the items.
5. Select the **Clear Order Invoice #** checkbo&#x78;**.**
6. Then click **Cancel Order** to complete the cancellation process.

At this point, if the **invoice** was:&#x20;

* Unpaid, then it is deleted from the patient's **Payments** activity.
* Paid, then the shipping cost automatically appears as a credit in the **Unbilled Items** section. The items must be manually refunded by deducting the shipping cost from the total. The credit includes a description containing a set of numbers. These numbers represent the item number, which can be matched to the corresponding invoice for reconciliation.&#x20;

The items marked as filled:

* Remain in the **Dispense Queue** with a status of Filled.
* Remain on the list in the **Unbilled items** section until it is unfilled or linked to another order and invoice.
* No longer are linked to the canceled order or invoice.

The canceled order is now unavailable for reactivation.

## Canceling an Order After a Shipment has been Created

After canceling an order, if the shipment has not been picked up or scanned by the carrier, a message appears prompting the user to void the shipment.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfy8VRiNYDuLiJR-_J_6bB0tblVzHm02NK-K_uYTRe56AufnFtSC29W5aqpurzDFK7Ph4iVEgI7SPC0csjDm-4Ye7HMkRC1FUdFp924g4mpSkvQB-GXuCAEZq6DnmgqIjMaqoOV7Q?key=XfocxVq_Ksd_-k84EaTLpcTY" alt="" width="563"><figcaption></figcaption></figure>
