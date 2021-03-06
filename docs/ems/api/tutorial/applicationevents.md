# Application events

This tutorial describes how a integration application can act on different events that occur in theElfsquad product configurator.

As of this writing there are 3 application events exposed through the API:

| Name                | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| QuotationRequested  | Event is emitted when a quotation is requested either through the configurator or order entry(EMS). |
| QuotationToPending  | This event is emitted when a quotation's status is set to Pending. |
| QuotationToAccepted | This event is emitted when a quotation's status is set to Accepted. |
| QuotationVerified   | This event is emitted when a quotation's status is set to Verified. |

*See [/ems/models/#application-events](/ems/models/#application-events) for information about application event models.*

