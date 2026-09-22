<!-- GENERATED FILE — DO NOT EDIT -->

<h1 align="center">STMicro STM32WBA25 · STM32CubeWBA</h1>
<h3 align="center">Bench supply · 3V0</h3>


<p align="right"><sub>captured on 2026-04-16 @ 11:49:27<br>generated on 2026-09-22 @ 14:53:31</sub></p>

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

- Board: NUCLEO-WBA25CE1
- MCU: STM32WBA25CEU7
- CPU: 64 MHz Arm Cortex-M33
- Flash: 512 KB
- SRAM: 96 KB
- SDK: STM32CubeWBA 1.9.0
- Benchmark application: BlueJoule-ADV, 1 s advertising interval

### References

- [NUCLEO-WBA25CE1](https://www.st.com/en/evaluation-tools/nucleo-wba25ce1.html)
- [Board pinout and CAD resources](https://www.st.com/en/evaluation-tools/nucleo-wba25ce1.html#cad-resources)
- [STM32WBA25CEU7](https://www.st.com/en/microcontrollers-microprocessors/stm32wba25ce.html)
- [STM32CubeWBA](https://www.st.com/en/embedded-software/stm32cubewba.html)

## Power Source

- Power source: regulated bench supply
- State of charge: not applicable
- Battery model: none



## EM&bull;Scope results · JS220

### 🟠&ensp;measured voltage

| &emsp;average&emsp; | &emsp;minimum&emsp; | &emsp;maximum&emsp; | &emsp;standard deviation&emsp;
|:---:|:---:|:---:|:---:|
| 3.004 V | 2.990 V | 3.010 V | 0.001 V |


### 🟠&ensp;sleep

| supply voltage | &emsp;current (avg)&emsp; | &emsp;current (std)&emsp; | &emsp;average power&emsp;
|:---:|:---:|:---:|:---:|
| 3.0 V |  1.2 µA |  0.6 µA |  3.7 µW |

### 🟠&ensp;boundary / closure

| accounting window | sleep window | event duty | closure residual | floor residual |
|:---:|:---:|:---:|:---:|:---:|
| 10.000 s | 0.500 s | 1.000% | 0.001% | -0.0 µA |

### 🟠&ensp;1&thinsp;s event period

| &emsp;&emsp;event energy (avg)&emsp;&emsp; | &emsp;&emsp;event energy (std)&emsp;&emsp; | &emsp;&emsp;energy per period&emsp;&emsp; | &emsp;&emsp;energy per day&emsp;&emsp; | &emsp;&emsp;&emsp;**EM&bull;eralds**&emsp;&emsp;&emsp;
|:---:|:---:|:---:|:---:|:---:|
| 21.3 µJ |  0.2 µJ | 25.0 µJ |  2.2 J | 36.97 |

### 🟠&ensp;10&thinsp;s event period

| &emsp;&emsp;event energy (avg)&emsp;&emsp; | &emsp;&emsp;event energy (std)&emsp;&emsp; | &emsp;&emsp;energy per period&emsp;&emsp; | &emsp;&emsp;energy per day&emsp;&emsp; | &emsp;&emsp;&emsp;**EM&bull;eralds**&emsp;&emsp;&emsp;
|:---:|:---:|:---:|:---:|:---:|
| 21.3 µJ |  0.2 µJ | 58.7 µJ |  0.5 J | 157.85 |

## Typical Event

<p align="center"><img src="event-B.png" alt="Event" width="900"></p>

