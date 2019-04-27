# 26 - Routes and EndPoints - Connect IoT Hub to Queue #

We're now going to connect our new Queue to our Service Bus.

---

- Still in ```portal.azure.com```.
- Return to your IoT hub by navigating to Resource Groups, selecting your Resource Group and selecting your IoT Hub.
- Scroll down to the ```Messaging``` section in the list on the left.
- Click the ```Message Routing``` item.
- Click the ```Custom endpoints``` item.
- Press the ```+ Add``` button at the top left and select Service Bus Queue
- In the ```Endpoint Name``` box enter ```iothubep```.
- From the ```Service Bus Namespace``` Dropdown, select your Service Bus Name you set in step 24
- From the ```Service Bus queue``` Dropdown select “criticalqueue”
- Press the ```Create``` Button.
- The Endpoint will begin deploying.
- You can monitor its progress by clicking the ```Notification``` icon (A bell) in the top right corner.
- This may take a minute or so to complete.

| Previous | Next |
| -------- | ---- |
| [< Step 25 - Routes and Endpoints - Queue](/25_queue/README.md) | [Step 27 - Routes and Endpoints - Routes >](/27_routes/README.md) |