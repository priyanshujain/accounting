# Purchase Order

A purchase order is a formal record of request for a product or service between a buyer and a seller. This is typically used in cases of a bulk order. A purchase order includes information about the item being purchased, the customer and vendor, and in some cases, delivery information.&#x20;

As an example, the customer would issue a purchase order to the vendor indicating the item, amount needed, and price they intend to pay. The vendor would then send an invoice to the customer to complete the purchase.

_Key Fields:_

* customer: the party making the purchase order.
* PurchaseOrderLineItem\[] object&#x20;
* line\_item: a single entry in a purchase order dedicated to a specific item purchased.
* description: a description of the item purchased.
* status: the state of the purchase order. Can be one of the following: DRAFT, SUBMITTED, AUTHORIZED, BILLED, DELETE.
* vendor: the party fulfilling the purchase order.

\
