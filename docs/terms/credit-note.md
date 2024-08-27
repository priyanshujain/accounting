# Credit Note

Credit notes are an accounts payable transaction used when a vendor offers a gift or refund to a customer. This record exists on the vendor side, and outlines how the customer is owed credit. A credit note will contain information on the amount of credit owed, the customer, and the account.

_Key Fields:_

* CreditNoteLineItem\[] object
* line\_items: a single entry in a credit note dedicated to a specific item that is owed to the customer.
* description: the description of the item that is owed.
* payments: an array of payment object IDs.
* remaining\_credit: the amount of value remaining in the credit note that the customer can use.
* status: the state of the credit note, which can be SUBMITTED, AUTHORIZED, PAID. In cases where there is no clear mapping, the original value is passed through.

\
