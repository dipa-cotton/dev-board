# dev board
This is a custom dev board I made for halflife week 5! It follows a guide but also includes an IMU sensor for things that might be useful during flight. I made this with my drone team in mind, so in the future, we can use this devboard to power everything.
# includes:
This dev board is rp2040 powered, and includes:
- A usb c port
- MCP1700
- 12 mhz crystal
- W25Q128JVS
- LSM6DSOX (IMU part)
# bom
## Bill of Materials (BOM)

| Item | Qty | Supplier | Cost/item | Total Cost | Link |
|---|---:|---|---:|---:|---|
| USB-C Receptacle | 1 | DigiKey | $1.00 | $1.00 | [DigiKey](https://www.digikey.com/en/products/detail/gct/USB4105-GF-A/11198441) |
| Surface-Mounted Capacitors | 1 | AliExpress | $3.00 | $3.00 | [AliExpress](https://www.aliexpress.com/ssr/300000512/BundleDeals2?spm=a2g0o.productlist.main.3.380266f9WEBsaM&productIds=1005012588693858:12000058767763111&pha_manifest=ssr&_immersiveMode=true&disableNav=YES&sourceName=SEARCHProduct&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012588693858%7C_p_origin_prod%3A1005011978546415&pvid=ddab0176-8947-4268-97fe-9c1ed6acb81d) |
| Surface-Mounted Resistors | 1 | AliExpress | $4.00 | $4.00 | [AliExpress](https://www.aliexpress.us/item/3256813168252345.html) |
| RP2040 | 1 | DigiKey | $1.00 | $1.00 | [DigiKey](https://www.digikey.com/en/products/detail/raspberry-pi/SC0914(13)/14306010) |
| MCP1700 | 1 | DigiKey | $0.50 | $0.50 | [DigiKey](https://www.digikey.com/en/products/detail/microchip-technology/MCP1700T-3302E-TT/652676) |
| 12 MHz Crystal | 1 | DigiKey | $1.00 | $1.00 | [DigiKey](https://www.digikey.com/en/products/detail/abracon-llc/ABM3C-12.000MHZ-D4Y-T/2639882) |
| W25Q128JVS | 1 | DigiKey | $1.50 | $1.50 | [DigiKey](https://www.digikey.com/en/products/detail/renesas-electronics-corporation/AT25FF321A-SHN-T/10390991) |
| LSM6DSOX | 1 | DigiKey | $6.00 | $6.00 | [DigiKey](https://www.digikey.com/en/products/detail/stmicroelectronics/LSM6DSO32XTR/14291421) |
| PCB | 1 | JLCPCB | $4.00 | $4.00 | [JLCPCB](https://jlcpcb.com) |
| Estimated Shipping | 1 | — | — | $8.00 | — |
| **Total** | | | | **$30.00** | |
# why i built this
I built this for my drone team so we can have a compact, light, small dev board that is perfect for flight, integrating an IMU without needing additional sensors.
it includes i2c!
# pictures
<img width="915" height="633" alt="Screenshot 2026-11-08 at 11 11 42 PM" src="https://github.com/user-attachments/assets/5d099cf0-0822-41a1-9e1c-16fde46215f7" />
<img width="982" height="677" alt="Screenshot 2026-11-08 at 11 11 28 PM" src="https://github.com/user-attachments/assets/734114ae-2493-4337-ae3c-ccbdf43cbad8" />
<img width="982" height="677" alt="Screenshot 2026-11-08 at 11 11 11 PM" src="https://github.com/user-attachments/assets/c81ecb4e-a9a1-434c-b2f5-3814edb63e0a" />
