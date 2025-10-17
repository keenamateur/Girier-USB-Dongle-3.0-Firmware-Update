# Girier Zigbee USB 3.0 Dongle Firmware

- **"Flashing this may turn your dongle into a very expensive paperweight. You've been warned!"**

**Firmware files and flashing instructions for Girier Zigbee USB 3.0 Dongle**

---

---

**Note:** This is **NOT original Girier firmware**. This repository contains **GZ91** type firmware that I successfully flashed onto my Girier USB dongle for update.

## 📁 Firmware Files

All firmware files are located in the `/firmware` directory.

| File | Description |
| :--- | :--- |
| `Dongle_OTA744.gbl` | Zigbee Coordinator firmware |
| `Dongle_OTA803.gbl` | Zigbee Coordinator firmware |
| `Repeater_OTA743.gbl` | Zigbee Repeater firmware |
| `Thread_OTA_731.glb` | Thread protocol firmware |

---
<img width="330" height="225" alt="Screenshot 2025-10-18 000429" src="https://github.com/user-attachments/assets/80499487-eee6-47af-9fa6-6323ec544690" />
<img width="330" height="225" alt="Screenshot 2025-10-18 000438" src="https://github.com/user-attachments/assets/c86578a8-92b7-4425-a8ee-8dbd6a491a8e" />
<img width="330" height="225" alt="Screenshot 2025-10-18 000443" src="https://github.com/user-attachments/assets/b185550a-c503-487a-9701-c4afdb61c124" />
<img width="330" height="225" alt="Screenshot 2025-10-18 000505" src="https://github.com/user-attachments/assets/cdcd07a5-4730-4497-ab35-3707f3de1b1d" />
<img width="330" height="225" alt="Screenshot 2025-10-18 000533" src="https://github.com/user-attachments/assets/b3afabdf-6fde-464b-83f2-c02985ee2f41" />
<img width="330" height="225" alt="Screenshot 2025-10-18 000846" src="https://github.com/user-attachments/assets/490bfd2e-da6b-4c32-bb4d-4df2de4f857c" />

## Flashing

### Using SecureCRT

For flashing, use [SecureCRT](https://www.vandyke.com/products/securecrt/).

## Flashing

1. **Hold the button** and connect the dongle to USB port
2. Choose connection: **"Serial"** and push **Connect**
3. If it didn't work: repeat via **File/Connect**
4. Locate and make eye contact with the **Transfer** tab
5. Push **1** for upload GBL
6. Countdown starts - you have 1 minute!
7. Push **"Send Xmodem"** under Transfer tab
8. **"Choose your weapon"**
9. **Enjoy!**

**Disclaimer:** Flash at your own risk.
- **"Works on my machine!™"**
