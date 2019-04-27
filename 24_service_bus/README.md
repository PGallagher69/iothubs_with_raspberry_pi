# 24 - Routes and EndPoints - Service Bus #

We're now going to set up some Routes and Endpoints which will let us begin to monitor messages and react to their content.

We'll begin by creating a Service Bus which will allow us to hook into the Messages Sent through the IoT Hub.

---

- Switch back to your browser and ```portal.azure.com```.
- Press the ```+ Create a Resource``` button in the top left.
- Type ```Service Bus``` and press Enter.
- Select the ```Service Bus``` item from the search results.
- Press the Create Button in the bottom left.
- The ```Name``` box enter a unique name, e.g. ```petesiotsb1```.
- From the ```Pricing Tier``` Drop down, choose ```Basic```.
- From the ```Subscription``` Dropdown, select your Azure Subscription.
- In ```Resource group``` make sure ```Use existing``` is selected.
- From the ```Resource group``` Dropdown, select the Resource Group you created at step 6.
- Make sure the ```Location``` is set to ```UK West```.
- Press the ```Create``` button.
- The Service bus will begin deploying.
- You can monitor its progress by clicking the ```Notification``` icon (A bell) in the top right corner.
- This may take a minute or so to complete.

| Previous | Next |
| -------- | ---- |
| [< Step 23- Adding a Temperature Sensor](/23_add_temp_sensor/README.md) | [Step 25 - Routes and Endpoints - Queue >](/25_queue/README.md) |