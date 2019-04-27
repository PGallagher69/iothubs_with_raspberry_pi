# 30 - Routes and EndPoints - Listen to the Queue #

We're now going to add some properties to our messages to trigger the new Route.

---

- Switch back to Visual Studio Code.
- Open the “readcriticalqueue.js” file.
- Paste the Primary Connection String you copied into the “Connection String” empty quotes.
- Remove the “EntityPath=criticalqueue” section from the end as this isn’t required.
- In the “queueName” enter “criticalqueue”.
- Save the file.
- Open a New PuTTY window.
- Connect to your Pi.
- Same username (pi) and Password (raspberry).
- Type in “cd share/NottsDevIoTHub” and press the Enter key.
- Type “sudo node readcriticalqueue.js” and press the Enter key.
- The terminal should start saying “No messages to receive”.
- If you’re using a real BME280, then warm it up by pressing your finger against the sensor.
- Press the button on your breadboard a few times.
- You should eventually see messages appearing.
- Wait for the Terminal to return to showing “No messages to receive” a few times.
- Press “ctrl+c” to stop your code.
- Close the Listener PuTTY window.

| Previous | Next |
| -------- | ---- |
| [< Step 29 - Routes and Endpoints - Message Properties](/29_message_properties/README.md) | [Step 31 - Creating a Logic App >](/31_logic_app/README.md) |