---
title: "ADC Add-on Board"
tagline: "ADC add-on board — Analog to digital Converter"
image: "img/eboards/addon-boards/adc-aob.png"
group: "annex"
description: "ADC Add-on Board for analog front-end evaluation, sampling and calibration."
draft: false
showHero: false
showBreadcrumbs: true
showReadingTime: false
---

<!--
Replace the image and download URLs below with your actual project assets.
Recommended image location:
assets/images/adc-aob.jpg
or
static/images/adc-aob.jpg
-->

<div class="not-prose w-full max-w-none flex flex-col lg:flex-row gap-10 lg:gap-24 items-start mb-16">

<!-- Hero Image -->
<div class="w-full lg:w-[38%] lg:sticky lg:top-24 lg:shrink-0">
<div class="flex items-center justify-center overflow-hidden rounded-xl border border-neutral-200 dark:border-neutral-700 bg-white dark:bg-neutral-900 shadow-sm p-6">
<img
src="/img/eboards/addon-boards/adc-aob.png"
alt="ADC add-on board"
class="adc-hero-image w-full h-auto object-contain"
/>
</div>
</div>

<!-- Hero Content -->
<div class="w-full lg:flex-1 lg:min-w-0 lg:pl-2">

<h1 class="text-4xl md:text-5xl font-light tracking-tight text-neutral-900 dark:text-neutral-100 mb-4">
ADC Add-on Board
</h1>

<a href="/request-quote/?product=ADC%20Add-on%20Board" style="display: inline-flex; align-items: center; margin-bottom: 1.5rem; border-radius: 0.5rem; background: #0284c7; padding: 0.75rem 1.25rem; color: #ffffff; font-weight: 600; text-decoration: none;">
Request a quote
</a>

<p class="text-lg leading-8 text-neutral-600 dark:text-neutral-300 mb-6">
The Ikainex ADC add-on board is designed for precision analog-to-digital conversion. Powered by Microchip's MCP3204 12-bit SAR ADC, it offers a 4-channel single-ended setup with a fast 100 ksps sampling rate and an SPI-compatible interface. Ideal for industrial monitoring, instrumentation, and remote data acquisition systems.
</p>

<!-- Quick Specs -->
<div class="grid grid-cols-2 sm:grid-cols-4 gap-4 mb-8 py-5 border-y border-neutral-200 dark:border-neutral-700">

<div>
<div class="text-xs uppercase tracking-wide text-neutral-400 dark:text-neutral-500 mb-1">Resolution</div>
<div class="text-base font-medium text-neutral-900 dark:text-neutral-100">12-bit</div>
</div>

<div>
<div class="text-xs uppercase tracking-wide text-neutral-400 dark:text-neutral-500 mb-1">Channels</div>
<div class="text-base font-medium text-neutral-900 dark:text-neutral-100">4 (single-ended)</div>
</div>

<div>
<div class="text-xs uppercase tracking-wide text-neutral-400 dark:text-neutral-500 mb-1">Sample Rate</div>
<div class="text-base font-medium text-neutral-900 dark:text-neutral-100">100 ksps</div>
</div>

<div>
<div class="text-xs uppercase tracking-wide text-neutral-400 dark:text-neutral-500 mb-1">Interface</div>
<div class="text-base font-medium text-neutral-900 dark:text-neutral-100">SPI</div>
</div>

</div>

<h2 class="text-xl font-medium text-neutral-900 dark:text-neutral-100 mb-3">Key Features</h2>

<ul class="space-y-3 text-neutral-600 dark:text-neutral-300 leading-7">
<li><strong class="text-neutral-900 dark:text-neutral-100">12-Bit 4-Channel ADC</strong> — Driven by the Microchip MCP3204, supporting up to four single-ended input channels (CH0–CH3).</li>
<li><strong class="text-neutral-900 dark:text-neutral-100">Onboard Signal Buffering</strong> — Every analog input passes through a Microchip MCP6284 5MHz rail-to-rail op-amp for optimal signal conditioning before conversion.</li>
<li><strong class="text-neutral-900 dark:text-neutral-100">Flexible Reference Selection</strong> — Easily switch the reference voltage using the onboard REFERENCE jumper between VCC (3.3V/5V) or an ultra-stable 4.096V provided by the onboard Microchip MCP1541 voltage reference.</li>
<li><strong class="text-neutral-900 dark:text-neutral-100">4-Wire SPI Communication</strong> — Supports standard SPI modes (0 and 3) at clock speeds up to 2 MHz, activated via a low CS line.</li>
<li><strong class="text-neutral-900 dark:text-neutral-100">Dual Logic Voltage Support</strong> — Integrated PWR SEL jumper enables seamless operation with both 3.3V and 5V host microcontrollers.</li>
<li><strong class="text-neutral-900 dark:text-neutral-100">Convenient Connectivity</strong> — Dedicated CH0–3 terminal blocks with twin GND connections simplify external analog sensor integration.</li>
</ul>

</div>

</div>

## Overview

The **Ikainex ADC** is a high-precision analog-to-digital converter expansion board powered by Microchip's MCP3204 12-bit, 4-channel A/D converter with a fast SPI serial interface. Designed for reliable signal conversion in industrial, instrumentation, and data acquisition applications, it combines flexible reference selection, integrated signal conditioning, and dual-voltage MCU compatibility.

## Technical Specifications

> ⚠️ **Content check needed:** the table below currently lists wireless/BLE specs (Fanstel BM833A, nRF52811, Bluetooth) that don't match an ADC board. This looks carried over from a different product page — swap in the actual MCP3204 / board specs before publishing.

<div class="overflow-x-auto my-6 rounded-lg border border-neutral-200 dark:border-neutral-700">

| Parameter | Specification |
|---|---|
| Wireless Module | Fanstel BM833A |
| Controller / Transceiver IC | Nordic Semiconductor nRF52811 |
| CPU | 64 MHz Arm Cortex-M4 |
| Flash Memory | 192 KB |
| RAM | 24 KB |
| Operating Voltage | 3.3 V |
| Supported Protocols | Bluetooth Low Energy, IEEE 802.15.4 |
| Wireless Band | 2.4 GHz ISM |
| Antenna | Integrated PCB antenna |
| Board Dimensions | **[Replace with actual dimensions]** |
| PCB Layers | 2 layers |
| Connector Type | MikroBUS™ / Click-compatible headers |
| Debug Interface | SWD |
| Host Interface | UART / GPIO / SPI / I²C — **[verify actual implementation]** |
| Logic Level | 3.3 V |
| Status Indicators | Power / User-configurable LEDs |
| User Input | User buttons |
| Firmware Update | OTA / SWD — **[verify supported method]** |
| Board Weight | Approximately 17 g |

</div>

## Pin Configuration

The following table provides a starting point for documenting the exposed
header signals. **Verify every signal against the final schematic and PCB
before using this table as an electrical reference.**

<div class="overflow-x-auto my-6 rounded-lg border border-neutral-200 dark:border-neutral-700">

| Description | Pin Name |  | Description |
|---:|---|---|---|
| 1 | `3V3` | Power | Regulated 3.3 V supply input/output |
| 2 | `GND` | Power | Ground reference |
| 3 | `VUP` | Power | Upstream / input supply connection |
| 4 | `RST` | Digital Input | Active-low reset signal |
| 5 | `CS` | Digital I/O | Chip-select / configurable GPIO |
| 6 | `P13` | GPIO | nRF52811 GPIO P0.13 |
| 7 | `P14` | GPIO | nRF52811 GPIO P0.14 |
| 8 | `P15` | GPIO | nRF52811 GPIO P0.15 |
| 9 | `P16` | GPIO | nRF52811 GPIO P0.16 |
| 10 | `P17` | GPIO | nRF52811 GPIO P0.17 |
| 11 | `P18` | GPIO | nRF52811 GPIO P0.18 |
| 12 | `P19` | GPIO | nRF52811 GPIO P0.19 |
| 13 | `P20` | GPIO | nRF52811 GPIO P0.20 |
| 14 | `P25` | GPIO | nRF52811 GPIO P0.25 |
| 15 | `P27` | GPIO | nRF52811 GPIO P0.27 |
| 16 | `P28` | GPIO / ADC | nRF52811 GPIO P0.28 |
| 17 | `P29` | GPIO / ADC | nRF52811 GPIO P0.29 |
| 18 | `P30` | GPIO / ADC | nRF52811 GPIO P0.30 |
| 19 | `TX` | UART | UART transmit signal |
| 20 | `RX` | UART | UART receive signal |
| 21 | `INT` | Digital Output | Interrupt / event signal |
| 22 | `CMD` | Digital I/O | Command / control interface |
| 23 | `SWDIO` | Debug | Serial Wire Debug data |
| 24 | `SWDCLK` | Debug | Serial Wire Debug clock |

</div>

> **⚠️ Logic-level warning:** The BM833A Click uses **3.3 V logic**. Do not
> connect 5 V GPIO signals directly to the module unless the corresponding
> interface has been specifically designed for 5 V tolerance or an appropriate
> level shifter is used.

## Hardware Architecture

The BM833A Click is organized around the BM833A wireless module and its
nRF52811 SoC. The board provides the supporting power, reset, programming,
debugging, status, and host-interface circuitry required to integrate the
wireless subsystem into a larger embedded design.

The external supply is routed through the board's power section to provide
the appropriate operating voltage for the wireless module and supporting
components. Local bypass and decoupling capacitors should be positioned close
to the module supply pins to minimize supply noise and transient voltage
variations.

High-speed digital signals are routed with short connections and appropriate
ground references. Decoupling capacitors, pull-up/pull-down networks, series
termination components, and other passive components should be selected and
placed according to the final schematic and PCB layout requirements.

## Functional Block Diagram

<div class="overflow-x-auto my-6 rounded-lg border border-neutral-200 dark:border-neutral-700 bg-neutral-50 dark:bg-neutral-900 p-4">

```text
                    +----------------------+
                    |   External Supply    |
                    |     VUP / 3.3 V      |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    |   Power Regulation   |
                    |   + Decoupling       |
                    +----------+-----------+
                               |
                               v
+----------------+     +----------------------+
| Host MCU /     |<--->|      BM833A         |
| Embedded Host  |     | Wireless Module     |
+-------+--------+     +----------+-----------+
        |                         |
        | UART / SPI / I2C / GPIO |
        |                         |
        v                         v
+---------------+        +----------------------+
| Control /     |        | nRF52811 SoC        |
| Data Signals  |        | 64 MHz Cortex-M4     |
+---------------+        +----------+-----------+
                                    |
                                    v
                         +----------------------+
                         | 2.4 GHz Wireless     |
                         | BLE / IEEE 802.15.4  |
                         +----------+-----------+
                                    |
                                    v
                         +----------------------+
                         | Integrated PCB       |
                         | Antenna               |
                         +----------------------+
```

</div>

## Signal Integrity & Filtering

The wireless module is sensitive to supply and RF noise, making appropriate
PCB layout and power decoupling important for reliable operation.

Power traces should be kept sufficiently short and supported by a continuous
ground reference wherever possible. Decoupling capacitors should be located
close to the associated power pins rather than being placed far away on the
board.

Digital interfaces should be routed with appropriate consideration for trace
length, return paths, impedance, and switching noise. Where required, optional
series resistors or filtering components can be populated to reduce ringing
and electromagnetic interference.

The antenna area should remain free from unnecessary copper, routing, and
metallic objects according to the module manufacturer's recommended PCB layout
guidelines.

## Programming & Debugging

Firmware can be loaded and debugged through the exposed **SWD interface**.
The SWD connection provides access to the nRF52811 programming and debugging
interface and can be used during firmware development, production testing,
and board bring-up.

Typical debugging connections are:

<div class="overflow-x-auto my-6 rounded-lg border border-neutral-200 dark:border-neutral-700">

| Debug Signal | Function                  |
| ------------ | ------------------------- |
| `SWDIO`      | Serial Wire Debug data    |
| `SWDCLK`     | Serial Wire Debug clock   |
| `GND`        | Debugger ground reference |
| `3V3`        | Target voltage reference  |
| `RST`        | Optional target reset     |

</div>

## Design & Project Files

The following project files should be maintained together with the hardware
design and released with each production revision.

<div class="grid grid-cols-1 sm:grid-cols-2 gap-4 my-6">

<div class="rounded-xl border border-neutral-200 dark:border-neutral-700 p-5">
<h3 class="text-base font-medium text-neutral-900 dark:text-neutral-100 mb-1">Schematics</h3>
<p class="text-sm text-neutral-600 dark:text-neutral-300 mb-3">Complete electrical schematic, including power, wireless module, connectors, programming/debugging, status indicators, and supporting circuitry.</p>
<a href="/downloads/bm833a-click-schematic.pdf" class="text-sm font-medium text-blue-600 dark:text-blue-400 hover:underline">Download Schematics (PDF) →</a>
</div>

<div class="rounded-xl border border-neutral-200 dark:border-neutral-700 p-5">
<h3 class="text-base font-medium text-neutral-900 dark:text-neutral-100 mb-1">Gerber Files</h3>
<p class="text-sm text-neutral-600 dark:text-neutral-300 mb-3">Manufacturing package containing the PCB fabrication layers, solder mask, silkscreen, copper, drill files, and board outline.</p>
<a href="/downloads/bm833a-click-gerbers.zip" class="text-sm font-medium text-blue-600 dark:text-blue-400 hover:underline">Download Gerber Files (ZIP) →</a>
</div>

<div class="rounded-xl border border-neutral-200 dark:border-neutral-700 p-5">
<h3 class="text-base font-medium text-neutral-900 dark:text-neutral-100 mb-1">Bill of Materials</h3>
<p class="text-sm text-neutral-600 dark:text-neutral-300 mb-3">Manufacturer part numbers, component values, packages, quantities, approved alternatives, and sourcing information.</p>
<a href="/downloads/bm833a-click-bom.csv" class="text-sm font-medium text-blue-600 dark:text-blue-400 hover:underline">Download Bill of Materials (CSV) →</a>
</div>

<div class="rounded-xl border border-neutral-200 dark:border-neutral-700 p-5">
<h3 class="text-base font-medium text-neutral-900 dark:text-neutral-100 mb-1">3D STEP Model</h3>
<p class="text-sm text-neutral-600 dark:text-neutral-300 mb-3">STEP model for mechanical integration, enclosure design, clearance checks, and CAD assembly work.</p>
<a href="/downloads/bm833a-click.step" class="text-sm font-medium text-blue-600 dark:text-blue-400 hover:underline">Download 3D STEP Model →</a>
</div>

</div>

## How to Order

To order the ADC Add-on Board, send us your required quantity and delivery
details. We will confirm availability, lead time, shipping, and the final price
before processing your order.

1. Submit your contact details and requirements using the quote request form.
2. Review the quotation and delivery information we send you.
3. Confirm the order with our team.

<p class="not-prose my-6">
<a href="/request-quote/?product=ADC%20Add-on%20Board" style="display: inline-flex; align-items: center; border-radius: 0.5rem; background: #0284c7; padding: 0.75rem 1.25rem; color: #ffffff; font-weight: 600; text-decoration: none;">
Request a quote for the ADC Add-on Board
</a>
</p>

[View Hardware Repository on GitHub](https://github.com/YOUR-USERNAME/bm833a-click-hardware) — the repository contains the latest schematic source files, PCB layout, library files, manufacturing outputs, documentation, and revision history.

## Revision History

<div class="overflow-x-auto my-6 rounded-lg border border-neutral-200 dark:border-neutral-700">

| Revision | Date       | Description                    |
| -------- | ---------- | ------------------------------ |
| `v0.1`   | 2026-08-17 | Initial hardware documentation |
| `v0.2`   | **[Date]** | **[Describe changes]**         |
| `v1.0`   | **[Date]** | **[Production release]**       |

</div>

## Notes

* Replace all placeholder specifications with values from the final schematic
  and datasheets.
* Verify the pin mapping against the actual PCB revision before manufacturing.
* Confirm the final board dimensions using the PCB mechanical drawing.
* Confirm all voltage and signal-level requirements before connecting external
  hardware.
* Keep the RF antenna area clear according to the BM833A module layout
  recommendations.
* The design files linked above are placeholders and should be replaced with
  the actual project artifacts before publishing the documentation.
