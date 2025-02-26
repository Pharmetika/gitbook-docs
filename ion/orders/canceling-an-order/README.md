# Canceling an Order

After users create and submit an order, they can cancel it at any time or at any stage in the process. See below for a breakdown of the different scenarios and steps involved in canceling an order.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-08 at 11.47.39 AM (1).png" alt=""><figcaption></figcaption></figure>

## Scenario 1: Removing Unfilled Items and Canceling the Order

This scenario applies when the user needs to cancel or remove items from an order and cancel the order entirely. The following conditions apply:

1. An invoice has **not** been created.
2. The items in the order have **not** been marked to be filled.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfhohszd523D-j7HpwUN8f42M3yacNAzzgmTYJfUj58M-aA7DsiAFa9vICo6ac08_qZcx4PmlrmQTlWXBaf8Dl6br1GHsrlsrfNvQHHGCpsqfI7NTk5Gl8dKzn9mXuaNHw0Y5w_3Q?key=XfocxVq_Ksd_-k84EaTLpcTY" alt="" width="563"><figcaption></figcaption></figure>

### Steps to Cancel or Remove Items and Cancel the Order

1. **Access the Order**
   1. Navigate to the relevant order that needs to be canceled or adjusted.
2. **Initiate Cancellation**
   1. Scroll to the bottom of the open order page.
   2. Click the **Cancel** button.
3. **Select Desired Options**
   1. A prompt will appear with cancellation options.
   2. Select **Remove Items from Order** to remove the items.
   3. Then select **Cancel Order** to complete the cancellation process.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-12 at 1.47.25 PM.png" alt="" width="563"><figcaption></figcaption></figure>

4. **Outcome of Cancellation**
   1. The **unfilled items** will:
      1. Be available to be linked to a new or added to an existing order and filled from the **Patient Summary** page.
      2. No longer be linked to the canceled order.

## Scenario 2: Deleting Filled Items and Cancelling the Order

This scenario applies when the user needs to delete items that have already been filled and cancel the associated order. The following conditions apply:

1. An invoice has **not** been created.
2. The items in the order have already been marked as **filled**.

<figure><img src="../../.gitbook/assets/Screenshot 2025-01-12 at 12.44.18 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Steps to Delete Filled Items and Cancel the Order

1. **Access the Order**
   1. Navigate to the relevant order that contains the filled items.
2. **Initiate Cancellation**
   1. Scroll to the bottom of the order page.
   2. Click the **Cancel** button.
3. **Select Desired Options**
   1. A prompt will appear with cancellation options.
   2. Select **Remove Items from Order** to delete the filled items.
   3. Then select **Cancel Order** to finalize the cancellation.
4. **Outcome of Cancellation**
   1. Because the items have been marked as **filled**, they will:
      1. **Remain in the Fill Status** and display in the Dispense Queue.
      2. Appear on the **Patient Payment** page under unbilled items.
   2. However, the items will no longer be linked to the canceled order.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfEsFmsw-gJ-9zSvX186kyFLuW4h-GQ-oSHJtYa2xLQ5VjGKP7IEhN4ybArFdGHQsaGo3aa-Q1OVeeKC936292K-_Z8YDyM1CMz1rCnakSGLuoWlulehxSPDIKxKNCgZjaElpIwQw?key=XfocxVq_Ksd_-k84EaTLpcTY" alt=""><figcaption><p>Dispensing Queue</p></figcaption></figure>

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXehB0OGfRm25TgQVQROLjR-A-kmR4dpXVTssQreQ7Gv_9fOfjcFFCL9V-XL6vXJJI__ASgry1xRL6Bft8QtBj-uVRatropdwbnbtc1ojw4G6lxd-nL0L671Zwy838gBm0z2dl41?key=XfocxVq_Ksd_-k84EaTLpcTY" alt=""><figcaption><p>Payment Page</p></figcaption></figure>

5. **Adding Items to a New or Existing Order**
   1. The filled items can be added to a new order or an existing order, as their fill status will remain intact.

## Scenario 3: Deleting Filled Items, Deleting an Invoice, and Cancelling the Order

This scenario addresses the process of deleting filled items, deleting the associated invoice, and cancelling the order when:

1. **An invoice has been created**, and
2. &#x20;**Items have been filled.**

_It is important to note that invoices should ideally be created only after items have been filled to ensure they include the items and any applicable shipping charges._

### Steps to Delete Filled Items, Delete the Invoice, and Cancel the Order

1. **Access the Order**
   1. Navigate to the order that includes filled items and an associated invoice.
2. **Initiate Cancellation**
   1. Scroll to the bottom of the order page.
   2. Click the **Cancel** button.
3. **Select Desired Options**
   1. A prompt will appear with multiple cancellation options.
   2. Select both **Remove Items from the Order** and **Clear Order Invoice #**.
   3. Then select the **Cancel Order** to proceed.
4. **Outcome of Removing Items, Deleting the Invoice, and Canceling the Order**
   1. If the **invoice** was:&#x20;
      1. **Unpaid** then it will be deleted on the Patient Payment page.
      2.  **Paid** then the shipping cost will automatically appear as a **credit** under the Unbilled Items list. The **items** will need to be **manually refunded** by deducting the shipping cost from the total. The credit will have a description containing a set of numbers. These numbers represent the item number, which can be matched to the corresponding invoice for reconciliation.&#x20;

          <figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeMN3WK3_6z0pUt8unRr0uar7nuZW74WdqKyShzdeuuhmmq4o2Jj9fceHdvGxPrYh2TK_KkETEjzqxhXwQsAJohh0roBHCtBl62ZNVeY0_bHdAOcI36cwKEM8U7PKutS0TiXi9erQ?key=XfocxVq_Ksd_-k84EaTLpcTY" alt=""><figcaption></figcaption></figure>
   2. The **items** marked as **filled** will:
      1. Remain in the **Dispense Queue** under the “Filled Status”.
      2. Remain on the list under **Unbilled items** until it is unfilled or linked to another order and invoice.
      3. No longer be linked to the canceled order or invoice.
   3. The canceled order will be unavailable for reactivation.

## Canceling an Order After a Shipment has been Created

After canceling an order, **if the shipment has not been picked up or scanned by the carrier,** a follow-up prompt will appear prompting the user to void the shipment.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfy8VRiNYDuLiJR-_J_6bB0tblVzHm02NK-K_uYTRe56AufnFtSC29W5aqpurzDFK7Ph4iVEgI7SPC0csjDm-4Ye7HMkRC1FUdFp924g4mpSkvQB-GXuCAEZq6DnmgqIjMaqoOV7Q?key=XfocxVq_Ksd_-k84EaTLpcTY" alt="" width="563"><figcaption></figcaption></figure>
