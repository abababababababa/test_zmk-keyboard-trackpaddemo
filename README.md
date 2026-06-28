# ZMK Trackpad Demo

A minimal ZMK keyboard demonstrating trackpad integration using the Azoteq TPS43 sensor on a Seeed XIAO BLE / XIAO nRF52840 Plus. This demo uses the [geeksville/zmk_driver_azoteq](https://github.com/geeksville/zmk_driver_azoteq) driver.

## Hardware

| Component        | Details                                     |
| ---------------- | ------------------------------------------- |
| MCU board        | Seeed Studio XIAO BLE / XIAO nRF52840 Plus  |
| Trackpad sensor  | Azoteq TPS43                                |

### Pin mapping

| Signal         | Pin    |
| -------------- | ------ |
| I2C SDA        | P1.14  |
| I2C SCL        | P1.15  |
| RDY            | P1.12  |
| RST            | P1.13  |

## Where to Buy

Breakout boards / PCBs can be purchased at [beekeeb.com](https://beekeeb.com) or [beekeeb.jp](https://beekeeb.jp).

## ZMK version

This config targets the ZMK `main` branch (slated for release as **v0.4**), as of 2026-06-28. Things may break as `main` evolves before the v0.4 release.

## License

MIT — see [LICENSE](LICENSE).

---

> Parts of this project were developed with assistance from AI tools.
