# 32 - Tweet Critical Messages #

Now we'll join all of our steps together can have our system tweet out a message when our temperature breaches a given level.

---

- Still in “portal.azure.com”.
- Once the Logic App has been created, it should take you straight to the Designer.
- From the “Start with a common trigger” section, click “When a message is received in a Service Bus queue”.
- In the “Service Bus” item, click the “Create” button.
- In the “Connection Name” box enter “servicebusconnection”.
- Under “Service Bus Namespace”, click the Service Bus namespace you created at Step 24.
- Click the “RootManagedSharedAccessKey”.
- From the Authentication Type Dropdown select “Connection String”.
- Press the “Create” button.
- Press the “Continue” button.
- From the “Queue name” Dropdown, select “criticalqueue”.
- Press the “Edit” link next to “Using the default values for the parameters”.
- From the Frequency Dropdown, select “Second”.
- Press the “New Step” button.
- Press “Add an Action”.
- In the “Search all connectors and actions” box type “tweet”.
- From the Search Results, select “Twitter – Post a tweet”.
- Press the “Sign In” button.
- Enter Your Twitter Username and Password.
- Press the “Authorize app” button to Authorise the Logic App to use your account.
- In the “Tweet Text” box enter “The Temperature was Critical :”.
- From the Dynamic Content flyout on the right, click “Content” to add the Message content to the tweet.
- Press the “Save” button in the menu bar.
- Press the Run button in the menu bar.
- Open your twitter feed.
- Press the Button on the Breadboard a few times until tweets start to appear!


| Previous | Next |
| -------- | ---- |
| [< Step 31 - Creating a Logic App](/31_logic_app/README.md) | [Step 33 - Delete Resources >](/33_delete_resources/README.md) |