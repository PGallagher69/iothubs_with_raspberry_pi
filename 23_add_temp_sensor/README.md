# 23 - Adding a Temperature Sensor #

We're now going to get the next version of Raspberry Pi Code. This version will either read a real Temperature Sensor on the BreadBoard, or Simulate the readings if there's not one fitted.

---

- Back in PuTTY, make sure that your session is still active.
- Make sure your code isn’t still running – Press ```ctrl+c``` to stop it if it is.
- Type the following and press enter to get the next version of code;

```git checkout 10_add_BME``` 

- The terminal should say ```Your branch is up-to-date with 'origin/10_add_BME '.```
- If you don’t have a BME Sensor… Switch Back to VS Code.
- Open the ```config.json``` file.
- Change the ```BME280Type``` from ```1``` to ```0``` to use a fake BME sensor.
- Type the following and press enter to run the code;

```sudo node index.js```

- Wait for the terminal to show ```Client Connected``` and ```Version 96```.
- to get the actual readings from the Pi, repeat either;

[Step 21 - Invoking a Method from the IoT Hub (Device Explorer)](/21_invoke_method_device_explorer/README.md)

or

 [Step 22 - Invoking a Method from the IoT Hub (VS Code)](/22_invoke_method_vs_code/README.md)

- If you get any errors using Device Explorer, you may need to close VS Code as it has taken over control.

| Previous | Next |
| -------- | ---- |
| [Step 22 - Invoking a Method from the IoT Hub (VS Code)  >](/22_invoke_method_vs_code/README.md) | [Step 24 - Routes and Endpoints - Service bus >](/24_service_bus/README.md) |