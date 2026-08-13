<!-- GENERATED FILE — DO NOT EDIT -->

<h1 align="center">Analog Devices MAX32655 Evaluation Kit · CodeFusion Studio</h1>
<h3 align="center">Bench supply · 3V3</h3>


<p align="right"><sub>captured on 2025-08-17 @ 01:38:00<br>generated on 2026-08-13 @ 14:47:51</sub></p>

## Activity

- Activity: Bluetooth Low Energy legacy advertising
- Advertising type: non-connectable, non-scannable (`ADV_NONCONN_IND`)
- PHY: LE 1M
- Advertising channels: 37, 38, and 39
- TX power: 0 dBm
- Advertising interval: 1 s
- Advertising payload length: 19 bytes
- Advertising event: one back-to-back transmission on each of channels 37, 38, and 39
- Flags: LE General Discoverable; BR/EDR not supported
- Local name: `BlueJoule`
- Manufacturer ID: Novel Bits (`0x08D3`)
- Manufacturer data: `0xFF`
- Conformance basis: observable over-the-air behavior, not a canonical source implementation
- Measurement result: average event energy and average event duration derived from repeated detected events
- Sleep model: time outside the measured event is treated as sleep for period and daily-energy projections


## Platform

- Board: Analog Devices MAX32655 Evaluation Kit
- MCU: Analog Devices MAX32655
- CPU: 100 MHz Arm Cortex-M4
- Flash: 512 KB
- SRAM: 128 KB
- Development environment: CodeFusion Studio
- CodeFusion Studio: 1.1.0

### References

- [MAX32655 Evaluation Kit](https://www.analog.com/en/resources/evaluation-hardware-and-software/evaluation-boards-kits/max32655evkit.html)
- [MAX32655 SoC](https://www.analog.com/en/products/max32655.html)
- [CodeFusion Studio](https://www.analog.com/en/resources/evaluation-hardware-and-software/embedded-development-software/codefusion-studio.html)
- [BUILD ARTIFACTS](../build)

## Power Source

- Power source: regulated bench supply
- State of charge: not applicable
- Battery model: none



## EM&bull;Scope results · JS220

### 🟠&ensp;measured voltage

| &emsp;average&emsp; | &emsp;minimum&emsp; | &emsp;maximum&emsp; | &emsp;standard deviation&emsp;
|:---:|:---:|:---:|:---:|
| 3.308 V | 3.285 V | 3.316 V | 0.001 V |


### 🟠&ensp;sleep

| supply voltage | &emsp;current (avg)&emsp; | &emsp;current (std)&emsp; | &emsp;average power&emsp;
|:---:|:---:|:---:|:---:|
| 3.3 V |  4.4 µA |  0.9 µA | 14.6 µW |

### 🟠&ensp;1&thinsp;s event period

| &emsp;&emsp;event energy (avg)&emsp;&emsp; | &emsp;&emsp;event energy (std)&emsp;&emsp; | &emsp;&emsp;energy per period&emsp;&emsp; | &emsp;&emsp;energy per day&emsp;&emsp; | &emsp;&emsp;&emsp;**EM&bull;eralds**&emsp;&emsp;&emsp;
|:---:|:---:|:---:|:---:|:---:|
| 47.4 µJ |  7.7 µJ | 61.9 µJ |  5.4 J | 14.95 |

### 🟠&ensp;10&thinsp;s event period

| &emsp;&emsp;event energy (avg)&emsp;&emsp; | &emsp;&emsp;event energy (std)&emsp;&emsp; | &emsp;&emsp;energy per period&emsp;&emsp; | &emsp;&emsp;energy per day&emsp;&emsp; | &emsp;&emsp;&emsp;**EM&bull;eralds**&emsp;&emsp;&emsp;
|:---:|:---:|:---:|:---:|:---:|
| 47.4 µJ |  7.7 µJ | 193.6 µJ |  1.7 J | 47.84 |

## Typical Event

<p align="center"><img src="event-B.png" alt="Event" width="900"></p>

