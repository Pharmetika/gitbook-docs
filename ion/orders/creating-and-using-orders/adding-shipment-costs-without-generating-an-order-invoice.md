# Adding Shipment Costs Without Generating an Order Invoice

The Commit and Create Charges button is one way to lock in an order to determine shipping fees (including surcharges) based on the items in the order without generating an invoice. These charges are then applied to the appropriate bill-to party, whether a patient or organization, in the Payments activity, and creates a charge line item in the **Unbilled Items** section. The shipping cost can be adjusted if items with surcharges are added or removed, or if there is a change in the final shipping or handoff method, such as switching carriers or service levels.

To lock in an order and add shipping fees to the corresponding party’s payment page, follow the steps below.

1. Create an order by adding the patient’s prescriptions, selecting a handoff method, choosing a bill-to party (patient by default), and setting the **Date for order** field.
2. Click **Submit Order.** This action saves the order, allowing shipping costs to be calculated based on the handoff method and items included. The **Commit and Create Charges** button is then enabled for selection.
3. After you submit the order, additional action buttons appear at the bottom to confirm the order has been successfully created.

In the following example, the FedEx Express Saver shipping method is listed at $12.50. However, on the patient’s payment page, the line charge shows $17.75. This difference is due to a surcharge for cold pack shipping applied to one of the items in the order.

To confirm which item has cold pack shipping, check the **Product Options** section of the product. Here, you’ll see Diltiazem 1% Ointment is marked for cold pack shipping. We can see that the handoff method FedEx Express Saver includes a $5.25 surcharge for products requiring cold pack shipping. Combining the base rate of $12.50 for FedEx Express Saver with the $5.25 cold pack surcharge brings the total to $17.75.

<figure><img src="../../.gitbook/assets/Example of surcharges for order.png" alt=""><figcaption></figcaption></figure>

If products with surcharges are added to the order after the shipping cost has been paid, the additional surcharges can still be added as a line item and labeled  as "Shipping Remainder Charge” before completing the order. To add the additional surcharge, add the product and click the **Commit and Create Charges** button. However, if the shipping cost has not yet been paid, it updates automatically with the most recent changes after clicking **Commit and Create Charges**.

If the initial charge has already been paid and a subsequent adjustment reduces the shipment cost, requiring a store credit or reimbursement, click [here ](../../patient/payments/applying-payment-credit.md)to learn more about applying a payment credit.
