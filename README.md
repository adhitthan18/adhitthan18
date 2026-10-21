### Hi, I'm Adhi

I build connected systems end to end: **ESP32 firmware, Go backends, web dashboards, and the servers and pipelines they run on.** I run [Adhi Teknologi](https://adhiteknologi.com), a small engineering company in Indonesia that delivers websites, IoT monitoring and control, and POS systems.

What I care about: security that holds up in practice (least privilege, no secrets in source, credentials that each do one job), deploys that can be verified and rolled back, and documentation the next person can follow.

#### Featured projects

| Project | What it is | Stack |
|---|---|---|
| [satumeja-pos-architecture](https://github.com/adhitthan18/satumeja-pos-architecture) | How [SatuMeja](https://satumeja.com), a restaurant and billiard POS in production, is split into least-privilege services and shipped by Jenkins: installers that refuse unapplied migrations and roll themselves back, tested in 25 scenarios. | Go · MariaDB · Angular · Flutter · Jenkins · Docker |
| [qr-relay-platform](https://github.com/adhitthan18/qr-relay-platform) | ESP32 relays controlled over the internet, with HMAC-signed QR enrollment, an MQTT watchdog, and a Jenkins pipeline that deploys without root. Runs in production. | Go · MariaDB · TypeScript · PlatformIO · Jenkins |
| [esp32-atm-security-firmware](https://github.com/adhitthan18/esp32-atm-security-firmware) | Monitoring firmware for ATM booths covering vibration, mains power, and climate, with alerts, QR enrollment on an ST7789, OTA updates, and WiFi recovery. | C++ · Arduino · ESP32 · MQTT |
| [go-relay-api-from-scratch](https://github.com/adhitthan18/go-relay-api-from-scratch) | The same relay idea built with only Go's standard library, to learn every layer: argon2id, sessions, rate limiting, provisioning, command delivery. | Go · React · MySQL |
| [adhiteknologi-website](https://github.com/adhitthan18/adhiteknologi-website) | Bilingual company site with type-checked translations, GSAP motion, and a WCAG AA palette, self-hosted with PM2 and nginx. | Next.js 16 · React 19 · Tailwind v4 |

#### Tools I use

- **Backend:** Go, Node.js, MariaDB/MySQL, REST, MQTT (Mosquitto)
- **Frontend:** TypeScript, React, Angular, Next.js, Vite, Tailwind CSS
- **Embedded:** ESP32, Arduino, PlatformIO, I²C/SPI/UART sensors, PCB design and assembly
- **Infrastructure:** Linux, nginx, systemd, Jenkins, Proxmox (LXC), Cloudflare Tunnel and Access

#### Contact

[adhiteknologi.com](https://adhiteknologi.com) · iotadhiteknologi@gmail.com
