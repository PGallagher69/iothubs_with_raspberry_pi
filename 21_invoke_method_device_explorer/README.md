# 21 - Invoking a Method on the Raspberry Pi (Device Explorer) #

We're now going to Invoke a Command on the Raspberry Pi from the Device Explorer Twin.

---

- Switch back to the Device Explorer;

<p align="center">
    <img src="images/01_device_explorer.png" width="500px" >
</p>

- Click the ```Data``` tab;

<p align="center">
    <img src="images/01a_data_tab_item.png" width="500px" >
</p>

- Click the Cancel Button to stop Monitoring;

<p align="center">
    <img src="images/01b_data_cancel.png" width="500px" >
</p>

- Click the “Call Method On Device” tab;

<p align="center">
    <img src="images/02_call_method_item.png" width="500px" >
</p>

- Make sure that The Event Hub and Device ID match those you chose in the steps above;

<p align="center">
    <img src="images/03_settings.png" width="500px" >
</p>

- In the “Method Name” box type ```getReadings```;

<p align="center">
    <img src="images/04_method_name.png" width="500px" >
</p>

- Press the “Call Method” button.
- The Return Payload box should show something like the following;

<p align="center">
    <img src="images/05_return_payload.png" width="500px" >
</p>

- Switch back to PuTTY, and the terminal should show something like the following;

<p align="center">
    <img src="images/06_method_payload.png" width="400px" >
</p>

| Previous | Next |
| -------- | ---- |
| [< Step 20 - Invoke a Method on the Pi - Setup](/20_invoke_method_on_pi_setup/README.md) | [Step 22 - Invoking a Method from the IoT Hub (VS Code)  >](/22_invoke_method_vs_code/README.md) |