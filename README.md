# WLED Controller with DMX Input

ESP32‑S3 based WLED controller with DMX512 input, fused LED outputs, and a built‑in level shifter – designed for 12V WS2815 LED strips.


## Features

- **MCU**: ESP32‑S3 (WiFi & BLE)
- **DMX512 input** via MAX485
- **4 addressable LED channels**  
  - Each with a 3.3V → 5V level shifter
  - Designed for 12V WS2815 strips (work with others ws281x)
- **4 fuses** – 5A per channel
- **Power supply**  
  - 12V DC input  
  - XL1509 buck converter (12V → 5V) for logic
  <img width="1003" height="1101" alt="Picture" src="https://github.com/user-attachments/assets/38ccd4b9-5db8-484b-8aa1-4ba1b7b12238" />
