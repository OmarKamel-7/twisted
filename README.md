# Twisted

Twisted is a tiny (14x32mm to be precise) ESP32-S3 based platform, which has dual Xtensa LX7 cores, 4Mb of flash, 2Mb of PSRAM, 512Kb of SRAM as well as BLE and WiFi on board, paired with an [0.42" IPS LCD](https://www.buydisplay.com/0-42-inch-mini-color-tft-lcd-display-module-96x54-ips-st7735), a keypad, a Neopixel and built-in battery management with USB OTG.

![](https://cdn.hackclub.com/01a07dcd-f21f-7968-8a00-245b88ea2e28/twisted-rendered-back.png)
![](https://cdn.hackclub.com/01a07dcd-edd5-7d68-ab97-722aa4a15e99/twisted-rendered-front.png)

<img alt="pcb layer by layer view" src="https://cdn.hackclub.com/01a07ea8-b022-752e-a618-ca72a8a1f7e5/twisted-layer-overview.gif" />

There is one more thing, the platform is extendable! It features a 20pin 1.27mm expansion header which allows you of attaching other boards that add more feature, and also give the _Twisted_ a reason for its name.

We currently have two expansion boards for Twisted...

- **Twisted Listen**: An audio codec based on ES8316, which provides a high performance DAC and ADC, the attachment comes with both a builtin microphone and amplifier for a loudspeaker, as well as a 3.5mm headphone jack (with microphone in.)

![](https://cdn.hackclub.com/01a07dd4-6ed8-747a-877e-fb85dad85dc5/twisted-listen-rendered-front.png)
![](https://cdn.hackclub.com/01a07dd4-6b17-7878-9f14-fcaad158ace0/twisted-listen-rendered-back.png)

- **Twisted Sense (WIP)**: An attachment that provides a a suite of sensors and trackers (pressure, temperature, humidity, gyroscope, accelerometer, magnetometer and GPS/GNSS) aiming to help the device "feel" what happens surround it.

## Production

Production could be done through [JLCPCB](https://jlcpcb.com)'s PCBA service.

Total costs for Twisted boards:

| Item | Price | Qty      | Where                        |
| ---- | ----- | -------- | ---------------------------- |
| PCB  | $7    | 5 Boards | [JLCPCB](https://jlcpcb.com) |
| PCBA | $100  | 5 Boards | [JLCPCB](https://jlcpcb.com) |

You will need to assemble one side of the boardm the other side which has the display, a resistor and the keypad you will have to assemble it yourself, or let JLCPCB assemble it for you at a higher cost.

You will need the display to be sourced and assembled by yourself, this is where you can buy it:

- AliExpress: [listing](https://aliexpress.com/item/1005007804650049.html) / [listing](https://aliexpress.com/item/1005008528322628.html) / [listing](https://aliexpress.com/item/1005012246832580.html) / [listing](https://aliexpress.com/item/1005008885821582.html)
- [BuyDisplay](https://www.buydisplay.com/0-42-inch-mini-color-tft-lcd-display-module-96x54-ips-st7735)

If you decide to buy the display from a different supplier, make sure it comes with a 16 pin flex cable, it also has to follow this pinout:
![](https://cdn.hackclub.com/01a07ec7-c5ce-760a-bc7a-648605e2724d/image.png)

Total costs for a Twisted Listen boards:

| Item | Price | Qty      | Where                        |
| ---- | ----- | -------- | ---------------------------- |
| PCB  | $7    | 5 Boards | [JLCPCB](https://jlcpcb.com) |
| PCBA | $60   | 5 Boards | [JLCPCB](https://jlcpcb.com) |

_Note that these tables don't include shipping charges._

Production files could be found in `/hardware/X/production`.
