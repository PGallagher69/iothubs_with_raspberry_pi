# 25 - Routes and EndPoints - Queue #

We're now going to set up a queue to hold our IoT Hub Messages while they wait to be processed.

---

- Still in ```portal.azure.com```.
- Make sure you’re in the new Service Bus you created, or navigate there via Resource Groups, and clicking on your resource group, then clicking on your new Service Bus
- Under ```Entities``` click ```Queues```.
- Click the ```+ Queue``` button.
- In the Name box enter ```criticalqueue```.
- Leave all the options as default.
- Press the ```Create``` button.
- The Queue will begin deploying.
- You can monitor its progress by clicking the ```Notification``` icon (A bell) in the top right corner.
- This may take a minute or so to complete.

| Previous | Next |
| -------- | ---- |
| [< Step 24 - Routes and Endpoints - Service bus](/24_service_bus/README.md) | [Step 26 - Routes and Endpoints - Connect IoT Hub to Queue >](/26_iot_hub_to_queue/README.md) |