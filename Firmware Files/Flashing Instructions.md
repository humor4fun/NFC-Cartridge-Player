# Flashing ESP32 with New ESPHome Firmware

Follow these steps to flash your ESP32 device with new firmware using [web.esphome.io](https://web.esphome.io):

1. Go to [web.esphome.io](https://web.esphome.io) in Google Chrome or Microsoft Edge.
2. Plug in your ESP32 device via USB.

>[!NOTE]
>If it's your first time you may be prompted to install a driver or grant permission to access the USB device. Approve any pop-ups that appear.

3. Click **Connect** and choose your ESP32 device from the list.
4. Click **Install**, then choose **"Pick a file"** and select the `.bin` firmware file from the GitHub repository.
5. Wait for the flashing process to complete. This may take up to a minute.
6. Once complete, unplug and reconnect your device.

---

### Troubleshooting

If the install fails:

- Press and hold the **BOOT** button on your ESP32.
- While holding **BOOT**, tap the **RESET** button once.
- Continue from step 3

> This puts your ESP32 into a special download mode required for flashing.

---

### Notes

- This process works best in **Google Chrome** or **Microsoft Edge**.
- If your device doesn’t show up, try a different USB cable or port.
- Make sure your `.bin` file is built for the correct ESP32 variant.
