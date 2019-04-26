# 08 - Create a Shared Access Policy #

We're now going to create a Shared Access Policy. This will allow us to connect to the IoT Hub with monitoring tools like the Device Explorer Twin.

---

- Still in ```portal.azure.com```, make sure you’re in your new IoT Hub;

<p align="center">
    <img src="images/01_iot_hub.png" width="500px" >
</p>

- Under ```Settings``` select ```Shared access policies```;

<p align="center">
    <img src="images/02_shared_access_policy_link.png" width="500px" >
</p>

- Press the ```+ Add``` button at the top;

<p align="center">
    <img src="images/03_shared_access_policy_add_button.png" width="500px" >
</p>

- In ```Access policy name``` type ```deviceexplorer```;

<p align="center">
    <img src="images/04_shared_access_policy_name.png" width="300px" >
</p>

- Tick all of the permissions;

<p align="center">
    <img src="images/04_shared_access_policy_all_permissions.png" width="300px" >
</p>

- Press the “Create” button at the Bottom;

<p align="center">
    <img src="images/06_shared_access_policy_create_button.png" width="500px" >
</p>

- Wait for the IoTHub to be updated...
- Check the Notification Area for progress updates;

<p align="center">
    <img src="images/07_shared_access_policy_creation_notification.png" width="400px" >
</p>

- When the Policy has been created, click its name in the list of policies;

<p align="center">
    <img src="images/08_device_explorer_item.png" width="500px" >
</p>

- Click the ```Copy``` icon next to ```Connection string – primary key``` to copy the connection string to your clipboard;

<p align="center">
    <img src="images/09_connection_string_primary_copy.png" width="300px" >
</p>

| Previous | Next |
| -------- | ---- |
| [< [Step 7 - Creating an IoT Device ](/07_create_iot_device/README.md) | [Step 9 - Using the Device Explorer Twin >](/09_device_explorer_twin/README.md) |