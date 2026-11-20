## Super Starbie ##
Super Starbie combines a Tamagotchi and an AI desktop pet into one project. Super Starbie displays monitored temperature and humidity (DHT-11), responds to button presses, and reacts to movement (MPU6050). It also features a built-in microphone (INMP411 MEMS) and a speaker, enabling TTS & STT for the AI version.

**I couldn't test the firmware, especially for the AI voice chat, because of the lack of emulators and the complexity of the project. I will edit the firmware and ensure that every last feature of the project works once the parts are here.**

## Hardware

- **ESP32-C3 SuperMini:** MCU that processes sensor data, handles user inputs, controls the display, and provides wireless connectivity for AI features.

- **0.96" OLED Display:** A 4-pin I2C display for starbie.

- **2 Mechanical Switches:** Open the menu for the Tamagotchi, choosing options in the menu, etc.

- **MPU-6050 Motion Sensor:** A 6-axis gyroscope and accelerometer for motion detection.

- **DHT11 Temperature & Humidity Sensor:** Measures the surrounding temperature and humidity.

- **INMP441 MEMS Microphone:** An I2S digital microphone that captures audio input, enabling Speech-to-Text (STT) and voice interaction in AI mode.

- **LM386 Audio Amplifier:** Amplifies the audio signal to drive the speaker and provide audible responses.

- **Speaker:** Provides audio output for Text-to-Speech (TTS).

- **10KΩ Pull-up Resistor:**.

## BOM TABLE

| Item | Qty | Supplier | Cost/Item | Total Cost |
|---|:---:|---|---:|---:|
| MPU-6050 Gyroscope + Accelerometer | 1 | [Ram Electronics](https://www.ram-e-shop.com/shop/kit-imu-mpu6050-gy521-imu-6-dof-mpu-6050-gyroscope-accelerometer-sensor-module-7076) | $3.34 | $3.34 |
| DHT-11 Temperature & Humidity Sensor | 1 | [Ram Electronics](https://www.ram-e-shop.com/shop/sen-dht11-dht-11-temperature-humidity-sensor-asair-original-brand-7093) | $1.16 | $1.16 |
| 0.96" OLED 4-pin I2C Display | 1 | [Future Electronics](https://store.fut-electronics.com/products/1-3-128x64-oled-display-module-i-c-iic-sh1106) | $4.83 | $4.83 |
| Custom PCB | 1 | [Metanoia](https://metanoia-eg.com/pcbaf/) | $8.36 | $8.36 |
| Mechanical Keyboard Switches | 2 | [Amazon](https://www.amazon.eg/) | $1.16 | $2.32 |
| 10KΩ Resistors (2 pcs) | 1 | [Amazon](https://www.amazon.eg/) | $0.10 | $0.10 |
| ESP32-C3 SuperMini | 1 | [Amazon](https://www.amazon.eg/) | $5.95 | $5.95 |
| LM386 Audio Amplifier Module | 1 | [Ram Electronics](https://www.ram-e-shop.com/shop/kit-amp-lm386-lm386-audio-amplifier-module-200-times-gain-audio-amplifier-7424) | $0.65 | $0.65 |
| INMP441 MEMS Microphone (I2S) | 1 | [Future Electronics](https://store.fut-electronics.com/products/inmp441-mems-microphone-i2s) | $5.20 | $5.20 |
| Speaker (3W, 4Ω) | 1 | [Future Electronics](https://store.fut-electronics.com/) | $1.00 | $1.00 |
| Estimated Shipping | - | - | - | $0.00 |
| **Total** | | | | **$32.91** |

# Firmware

**Hackblub:** https://github.com/SharKingStudios/Starbie/tree/main/Firmware/Starbie

**kaloprojects:** https://github.com/techiesms/Portable-AI-Voice-Assistant-/tree/main/Portable_Voice_Assistant 

  
## Feautres

- **AI Assistant Mode:** Supports voice-based interactions with AI through Speech-to-Text (STT) and Text-to-Speech (TTS).

- **Tamagotchi Mode:** An interactive desktop companion.

- **Motion-Based Interactions:** Reacts to movement and changes in orientation using its motion sensor.

- **Weather & Environment Monitoring:** Displays temperature, and humidity.


## PCB & Components

<img width="868" height="843" alt="image" src="https://github.com/user-attachments/assets/7d818255-2c17-4bbc-851e-4123be817fae" />

<img width="1568" height="817" alt="image" src="https://github.com/user-attachments/assets/370f8355-711b-4cca-8839-e1dd83b188eb" />

## 3D Image
<img width="1675" height="895" alt="image" src="https://github.com/user-attachments/assets/a1e34972-e35e-43e3-9322-fa0a33b9ba7d" />


