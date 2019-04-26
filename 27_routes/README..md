# 27 - Routes and EndPoints - Adding A Route #

We're now going to add some Routes for our messages so we can do different things dependant upon the content of our messages.

---

- Still in ```portal.azure.com```.
- Still in your IoT hub.
- Scroll down to the ```Messaging``` section in the list on the left.
- Click the ```Routes``` item.
- Click ```+ Add```.
- In the ```Name``` box enter ```criticalroute```.
- From the ```Endpoint``` Dropdown, select ```iothubep```.
- From the ```Data source``` Dropdown, select ```Device Telemetry Messages```.
- In the ```Query string``` box, Replace the ```True``` with the following;

```level="critical"```

- Press the ```Save``` button. 
- The Endpoint will begin deploying.
- You can monitor its progress by clicking the ```Notification``` icon (A bell) in the top right corner.
- This may take a minute or so to complete.

| Previous | Next |
| -------- | ---- |
| [< Step 26 - Routes and Endpoints - Connect IoT Hub to Queue](/26_iot_hub_to_queue/README.md) | [Step 28 - Routes and Endpoints - Queue Reader Policy >](/28_queue_reader_policy/README.md) |