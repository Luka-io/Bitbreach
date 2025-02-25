# VulnKit

An innovative open-source hardware and software platform designed for creating a **pentesting device** capable of many soon released features. This repository soon includes PCB design files, firmware, and comprehensive documentation to bring the project to life.

---

## 🚀 Features

- **Powerful Hardware**: Includes ESP32-S3, CC1101, PN7150, and more.
- **Expandable Storage**: MicroSD card slot for additional data storage.
- **Connectivity Options**: USB-C with LiPo charging capabilities.
- **User-Friendly Interface**: Custom UI.
- **Advanced Protocols**: Supports IR, RFID/NFC, and sub-GHz ...etz..communication.
- **Community Growing Projekt Goal**: Social Media Groups.

---

## 📂 Repository Structure

```plaintext
.
├── hardware/      # PCB design files and more...
├── firmware/      # Source code for ESP32-S3
├── docs/          # Documentation and tutorials
└── examples/      # Example projects and usage guides
```

---

## 🛠️ Setup Instructions

### Hardware Assembly
1. Get your the PCB using the provided Gerber files. Be sure to check Out JlcPcb :)


### Firmware Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Luka-io/VulnKit.git
   cd VulnKit
   ```
2. Install dependencies using PlatformIO:
   ```bash
   platformio run
   ```
3. Flash the firmware to the ESP32-S3:
   ```bash
   platformio run --target upload
   ```

---

## 📖 Documentation

- [Getting Started Guide](docs/getting-started.md)
- [Hardware Schematics](hardware/schematics.pdf)
- [Firmware API Reference](docs/firmware-api.md)

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.

---

## 🛡️ License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

Have questions or suggestions? Reach out to me at the soon existing social media platforms.

---

## 🌟 Support

If you like this project, give it a star ⭐ and share it with your network!

---

## 📊 Roadmap

- [ ] Design PCB
- [ ] Implement basic UI and functions
- [ ] Add support for additional protocols
- [ ] Release stable firmware version
- [ ] Work on the User Ideas
- [ ] .....

---

## 🎥 Demo

![Interactive Demo](demo.gif)

Soon Demo Content will be avaible...

---

## 🤝 Sponsored by JLCPCB

Special thanks to JLCPCB for sponsoring the PCB manufacturing for this project. Order high-quality PCBs for your next project at [JLCPCB](https://jlcpcb.com/). https://jlcpcb.com/?from=see

---

## ⚠️ Disclaimer

This project is in active development. Use at your own risk. 

Legal Disclaimer
This device and software are tools designed for cybersecurity education, authorized penetration testing, and research purposes only. Their use must comply with all applicable laws and regulations. Unauthorized or malicious activities using this project are strictly prohibited.

By downloading, using, or modifying this project, you agree to act responsibly and respect the rights of others. This project is provided under an open-source license. GNU Affero General Public License v3.0, allowing for modification and redistribution, provided that proper credit is maintained.

The developers assume no liability for misuse or any damage caused by the use of this project. All usage is at your own risk, and it is your responsibility to ensure compliance with local laws.
