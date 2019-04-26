# 18 - Sending a Message from the IoT Hub to the Raspberry Pi #

We're now going to send messages from the Device Explorer Twin to our Raspberry Pi.

---

- Switch back to the Device Explorer;

<p align="center">
    <img src="images/01_device_explorer.png" width="500px" >
</p>

- Select the “Messages To Device” tab;

<p align="center">
    <img src="images/02_messages_to_device_tab_item.png" width="500px" >
</p>

- Make sure that The Event Hub and Device ID match those you chose in the steps above;

<p align="center">
    <img src="images/03_settings.png" width="500px" >
</p>

- In the ```Message``` box type ```TestMessage```

<p align="center">
    <img src="images/04_testmessage_box.png" width="500px" >
</p>

- Press the “Send” button.
- You should see a status message that the message was sent;

<p align="center">
    <img src="images/05_message_sent.png" width="500px" >
</p>

- Switch back to PuTTY and the terminal should show something like ```Command = TestMessage```;

<p align="center">
    <img src="images/06_message_received.png" width="400px" >
</p>

- Try sending ```RedLED``` and ```GreenLED``` to see the LEDs Flash;

<p align="center">
    <img src="images/07_flash_leds.png" width="400px" >
</p>

| Previous | Next |
| -------- | ---- |
| [< Step 17 - Receiving a Message from the IoT Hub on Button Press](/17_receive_msg_from_iot_hub/README.md) | [Step 19 - Sending a Message from the IoT Hub to the Raspberry Pi (VS Code) >](/19_send_msg_from_hub_to_pi_vs_code/README.md) |