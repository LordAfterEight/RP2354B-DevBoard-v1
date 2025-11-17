# RP2354B-DevBoard-v1
Repository for my first RP2354 based dev board

<p float="middle">
  <img width="49.5%" height="826" alt="image" src="https://github.com/user-attachments/assets/c08a0a62-78d4-4dba-8551-3cb1f9de439f" />
  <img width="49.5%" height="826" alt="image" src="https://github.com/user-attachments/assets/5138cbf7-66fb-4709-8fed-877ff973cdd9" />
</p>

This dev board comes without external flash and only uses the 2MB of flash that come with the RP2354B chip, thus making this board only compatible with this specific version of the chip.

# Pinout
The two rows of pin headers are simply GPIO 0 - 19 on one side and GPIO 20 - 39 on the other. This means that the ADC pins of the RP2354B can **not** be used on this board as they're simply unconnected.

VBUS is directly connected to the micro-usb connector. 3V3/VSYS is connected to the output of the voltage regulator.
