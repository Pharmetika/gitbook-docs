# Managing Shipments for Orders Still in the Pharmacy

Pharmacies can reprint or void an existing shipping label and generate a new one for orders that have not yet left the pharmacy or been scanned by the carrier.

When an existing label is voided and a new shipment is created, the original shipment identifier remains, but a new tracking ID is linked to the order. The order ID continues to link to the shipment charge on the patient's or organization's payment page. This feature ensures that only one shipment ID is associated with the order.

<figure><img src="../../.gitbook/assets/Existing Shipment Found.png" alt=""><figcaption></figcaption></figure>

## Creating a Shipment for a Replacement in an Order

If an order contains items that need to be replaced and the shipment has already been scanned by the carrier and left the pharmacy, it cannot be voided. In this case, the pharmacy should follow the standard replacement process and manually create a new shipment from the Prescription Hand-Off page. This will generate a new shipping label with a unique shipment ID and tracking ID. The new shipment will not be linked to specific items from the original order.

