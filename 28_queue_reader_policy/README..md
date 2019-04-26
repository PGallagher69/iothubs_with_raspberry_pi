# 28 - Routes and EndPoints - Adding a Queue Reader Policy #

Here we're going to add a Security Policy to allow our Queue to read messages.

---

- Still in “portal.azure.com”.
- Return to your Service Bus by navigating to Resource Groups, select your Resource Group and select your Service Bus.
- Under the “Entities” section, click “Queues”.
- Click the “criticalqueue” item.
- Under Settings, click “Shared access policies”.
- Click “+ Add” in the top left.
- In the Name box enter “criticalqueuereader”.
- Tick the “Manage” checkbox.
- Press the Create Button.
- The Shared Access Policy will begin deploying.
- You can monitor its progress by clicking the “Notification” icon (A bell) in the top right corner.
- This may take a minute or so to complete.
- Click the “criticalqueuereader” item once it’s deployed.
- Click the Copy   button next to the “Primary Connection String” item.

| Previous | Next |
| -------- | ---- |
| [< Step 27 - Routes and Endpoints - Routes](/27_routes/README.md) | [Step 29 - Routes and Endpoints - Message Properties >](/29_message_properties/README.md) |