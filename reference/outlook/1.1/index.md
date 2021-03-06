# Outlook add-in API requirement set 1.1

The Outlook add-in API subset of the JavaScript API for Office includes objects, methods, properties and events that you can use in an Outlook add-in.

> **Note**: This documentation is for a [requirement set](../tutorial-api-requirement-sets.md) other than the latest requirement set. 

## What's new in 1.1?

Requirement set 1.1 includes all of the features of Requirement set 1.0. It added the ability for add-ins to access the body of messages and appointments and the ability to modify the current item.

### Change log

- Added [Body](Body.md) object: Provides methods for adding and updating the content of an item in an Outlook add-in.
- Added [Location](Location.md) object: Provides methods to get and set the location of a meeting in an Outlook add-in.
- Added [Recipients](Recipients.md) object: Provides methods to get and set the recipients of an appointment or message in an Outlook add-in.
- Added [Subject](Subject.md) object: Provides methods to get and set the subject of an appointment or message in an Outlook add-in.
- Added [Time](Time.md) object: Provides methods to get and set the start or end time of a meeting in an Outlook add-in.
- Added [Office.context.mailbox.item.addFileAttachmentAsync](Office.context.mailbox.item.md#addFileAttachmentAsync): Adds a file to a message or appointment as an attachment.
- Added [Office.context.mailbox.item.addItemAttachmentAsync](Office.context.mailbox.item.md#addItemAttachmentAsync): Adds an Exchange item, such as a message, as an attachment to the message or appointment.
- Added [Office.context.mailbox.item.removeAttachmentAsync](Office.context.mailbox.item.md#removeAttachmentAsync): Removes an attachment from a message or appointment.
- Added [Office.context.mailbox.item.body](Office.context.mailbox.item.md#body): Gets an object that provides methods for manipulating the body of an item.
- Added [Office.context.mailbox.item.bcc](Office.context.mailbox.item.md#bcc): Gets or sets the recipients on the Bcc (blind carbon copy) line of a message.
- Added [Office.MailboxEnums.RecipientType](Office.MailboxEnums.md#RecipientType): Specifies the type of recipient for an appointment.

## Additional resources

- [Outlook add-ins](../../../docs/outlook/outlook-add-ins.md)
- [Outlook add-in code samples](https://dev.outlook.com/MailAppsGettingStarted/Samples)
- [Get started](https://dev.outlook.com/MailAppsGettingStarted/GetStarted)
