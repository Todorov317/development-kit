# Aptus ESP32-P4 GitHub README Pack

本文件包含两份完整的 GitHub README 内容，可直接复制使用。

---

## 1. 产品页仓库 README
**对应链接：** https://www.aptusdisplay.com/products/5-inch-854c397480-esp32-p4-capacitive-touch-lcd-display-development-kit

**建议仓库名：** A050EC01-ESP32-P4-Display 或 Aptus-ESP32-P4-5inch-Touch-LCD

```markdown
# Aptus A050EC01 5-Inch ESP32-P4 Capacitive Touch LCD Development Kit

Integrated 4.96-inch 480×854 IPS capacitive touch display + ESP32-P4 dual-core RISC-V platform in a compact metal housing. Ready for custom HMI, IoT interfaces, industrial control panels and embedded GUI development.

**Product page:** [Aptus A050EC01 5-Inch ESP32-P4 Capacitive Touch LCD Development Kit](https://www.aptusdisplay.com/products/5-inch-854c397480-esp32-p4-capacitive-touch-lcd-display-development-kit)

---

## Overview

The **A050EC01** is a complete ESP32-P4 based display development kit from Aptus. It combines a 4.96-inch portrait IPS capacitive touch screen (480 × 854), 32 MB PSRAM, 16 MB Flash, Wi-Fi / Bluetooth, Ethernet, USB Type-C, UART, GPIO and TF card slot inside a matte-black metal enclosure.

Developers can start building graphical interfaces immediately with **Arduino**, **ESP-IDF** or **MicroPython** without assembling a separate display + controller board.

Ideal for:
- Smart home / room control panels
- Industrial equipment HMI
- IoT status & configuration terminals
- Access control / self-service interfaces
- Rapid UI prototyping

---

## Hardware

### Display Node

| Component              | Details                                      |
|------------------------|----------------------------------------------|
| Product Model          | A050EC01                                     |
| Display Size           | 4.96 inch (IPS)                              |
| Resolution             | 480 × 854 pixels (portrait)                  |
| Touch                  | 5-point capacitive touch                     |
| Brightness             | 400 cd/m²                                    |
| Colors                 | 16.7 million (8-bit)                         |
| Active Area            | 61.78 × 109.91 mm                            |
| Viewing Direction      | All o'clock                                  |
| Response Time          | 30 ms                                        |
| MCU                    | ESP32-P4 dual-core RISC-V                    |
| CPU Frequency          | 360 MHz (HP) / 40 MHz (LP)                   |
| PSRAM                  | 32 MB                                        |
| Flash                  | 16 MB                                        |
| Wireless               | Wi-Fi + Bluetooth                            |
| Interfaces             | USB Type-C, UART, GPIO, Ethernet             |
| Storage Expansion      | TF card slot                                 |
| Power                  | 5 V via Type-C (≤ 5 W)                       |
| Operating Temperature  | −20 °C ~ +70 °C                              |
| Housing                | Matte black metal                            |
| Overall Dimensions     | 70.7 × 124.7 × 27.39 mm                      |
| Weight                 | 169 g                                        |

---

## Key Features

- Integrated 5-inch capacitive touch IPS display in portrait orientation
- ESP32-P4 dual-core RISC-V with 32 MB PSRAM + 16 MB Flash
- Supports Arduino, ESP-IDF and MicroPython
- USB Type-C, UART, GPIO, Ethernet and TF card
- Compact metal housing suitable for evaluation and light industrial use
- Operating temperature −20 °C to +70 °C

---

## Development Environments

| Environment   | Status / Notes                          |
|---------------|-----------------------------------------|
| Arduino       | Supported                               |
| ESP-IDF       | Supported                               |
| MicroPython   | Supported                               |

Developers can create custom interface layouts, control logic and communication functions according to project requirements.

---

## Typical Application Scenarios

### Smart Home Control Panels
Vertical menu systems, device status dashboards and room controllers.

### Industrial Equipment Interfaces
Compact HMI for parameter display, configuration menus and status monitoring. UART / GPIO / Ethernet available for integration.

### IoT Device Terminals
Network-connected status displays, configuration interfaces and monitoring units.

### Access Control & Self-Service
Custom menus, input forms and operational prompts for compact terminals.

### Product Prototyping
Rapid evaluation of embedded GUI concepts before committing to a custom hardware design.

---

## Getting Started

1. Power the kit via USB Type-C (5 V).
2. Select your preferred development environment (Arduino / ESP-IDF / MicroPython).
3. Develop and flash your custom application.
4. Use the capacitive touch interface and available I/O for interaction and external connections.

For detailed specifications, mechanical drawings and customization options, visit the official product page:

**[Aptus A050EC01 Product Page](https://www.aptusdisplay.com/products/5-inch-854c397480-esp32-p4-capacitive-touch-lcd-display-development-kit)**

---

## Repository Structure (Suggested)

```
A050EC01-ESP32-P4-Display/
├── examples/               # Sample Arduino / ESP-IDF / MicroPython projects
├── docs/                   # Additional notes, pinouts, mechanical drawings
├── images/                 # Photos of the kit
├── LICENSE
└── README.md
```

---

## Credits & Links

- Hardware manufacturer: [Aptus Display](https://www.aptusdisplay.com/)
- Product page: [5-Inch 480×854 ESP32-P4 Capacitive Touch LCD Development Kit (A050EC01)](https://www.aptusdisplay.com/products/5-inch-854c397480-esp32-p4-capacitive-touch-lcd-display-development-kit)

---

## License

MIT License
```

---

## 2. LVGL 技术文章仓库 README
**对应链接：** https://www.aptusdisplay.com/info-detail/how-to-develop-custom-applications-with-lvgl-on-an-esp32-p4-lcd-display

**建议仓库名：** ESP32-P4-LVGL-Custom-UI 或 Aptus-ESP32-P4-LVGL-Guide

```markdown
# How to Develop Custom Applications with LVGL on an ESP32-P4 LCD Display

Practical guide for building custom graphical interfaces with LVGL + ESP-IDF on the Aptus 5-inch ESP32-P4 capacitive touch LCD development kit (A050EC01).

**Full tutorial:** [How to Develop Custom Applications with LVGL on an ESP32-P4 LCD Display](https://www.aptusdisplay.com/info-detail/how-to-develop-custom-applications-with-lvgl-on-an-esp32-p4-lcd-display)

**Related hardware:** [Aptus A050EC01 5-Inch ESP32-P4 Capacitive Touch LCD Development Kit](https://www.aptusdisplay.com/products/5-inch-854c397480-esp32-p4-capacitive-touch-lcd-display-development-kit)

---

## Overview

This repository documents a practical workflow for developing custom applications on an ESP32-P4 LCD display using **LVGL** (Light and Versatile Graphics Library) together with **ESP-IDF**.

LVGL provides reusable UI components (buttons, labels, menus, charts, touch handling, multi-screen navigation), while ESP-IDF handles firmware development, hardware drivers, build system and flashing.

The guide is written around the **Aptus A050EC01** 5-inch 480×854 capacitive touch development kit and is suitable for:

- Smart home control panels
- IoT status & configuration terminals
- Industrial HMI interfaces
- Access control / self-service UIs
- Rapid embedded GUI prototyping

---

## Prerequisites

| Component                    | Purpose                                              |
|-----------------------------|------------------------------------------------------|
| ESP32-P4 LCD development kit | Processor + LCD + capacitive touch hardware          |
| Computer                    | Runs ESP-IDF tools and compiles the firmware         |
| ESP-IDF                     | Official Espressif framework and toolchain           |
| Visual Studio Code          | Recommended editor (with ESP-IDF extension)          |
| LVGL                        | Graphics library and UI widgets                      |
| Display + Touch drivers     | Board-specific initialization for LCD and touch      |
| USB cable + drivers         | Flashing and serial monitoring                       |

> **Important:** LVGL is a software library that must be integrated into firmware running on the ESP32-P4. It is not a standalone application that can be installed directly onto the LCD panel.

---

## Development Steps Summary

### 1. Install ESP-IDF and set target

Follow the official ESP32-P4 getting-started guide, then set the target:

```bash
idf.py set-target esp32p4
```

### 2. Add LVGL via ESP Component Manager

Recommended approach (using the official port component):

```bash
idf.py add-dependency "espressif/esp_lvgl_port^2.3.0"
```

Alternative (direct LVGL):

```bash
idf.py add-dependency "lvgl/lvgl^9.*"
```

Always check current version compatibility with your ESP-IDF release.

### 3. Configure LCD and Touch Drivers

Typical tasks:

- Initialize ESP32-P4 peripherals used by the board
- Initialize the LCD controller (resolution, color format, buffers, transfer)
- Initialize the capacitive touch controller
- Register LVGL display and input devices
- Start the LVGL task / periodic handler
- Verify basic rendering and touch input

**Recommendation:** Start from any official or validated example project supplied for the Aptus A050EC01 rather than implementing drivers from scratch.

### 4. Create a Basic LVGL Interface (LVGL 9 example)

```c
#include "lvgl.h"

static void button_event_cb(lv_event_t * e)
{
    lv_obj_t * label = (lv_obj_t *)lv_event_get_user_data(e);
    lv_label_set_text(label, "Button clicked!");
}

void create_home_screen(void)
{
    lv_obj_t * screen = lv_screen_active();

    lv_obj_t * title = lv_label_create(screen);
    lv_label_set_text(title, "My Smart Home");
    lv_obj_align(title, LV_ALIGN_TOP_MID, 0, 30);

    lv_obj_t * status = lv_label_create(screen);
    lv_label_set_text(status, "Light: OFF");
    lv_obj_align(status, LV_ALIGN_CENTER, 0, -50);

    lv_obj_t * button = lv_button_create(screen);
    lv_obj_set_size(button, 180, 60);
    lv_obj_align(button, LV_ALIGN_CENTER, 0, 20);

    lv_obj_t * button_label = lv_label_create(button);
    lv_label_set_text(button_label, "Turn On Light");
    lv_obj_center(button_label);

    lv_obj_add_event_cb(button, button_event_cb, LV_EVENT_CLICKED, status);
}
```

This example creates a simple title, status label and interactive button. Expand it with additional pages, charts, sliders and application logic as needed.

### 5. Build, Flash and Monitor

```bash
idf.py build
idf.py -p PORT flash monitor
```

Replace `PORT` with the correct serial port (e.g. `COM5` on Windows or `/dev/ttyUSB0` on Linux).

### 6. Develop and Test Your Own Application

Suggested development order:

1. Static UI elements
2. Touch interactions and multi-screen navigation
3. Device control / sensor reading / communication logic
4. Performance and memory optimization

Pay attention to memory usage, rendering performance, font/image sizes and touch accuracy.

---

## Hardware Reference (A050EC01)

| Specification              | Details                                      |
|---------------------------|----------------------------------------------|
| Product Model             | A050EC01                                     |
| Display                   | 4.96-inch IPS, 480 × 854                     |
| Touch                     | 5-point capacitive                           |
| Brightness                | 400 cd/m²                                    |
| MCU                       | ESP32-P4 dual-core RISC-V                    |
| CPU Frequency             | 360 MHz (HP) / 40 MHz (LP)                   |
| PSRAM                     | 32 MB                                        |
| Flash                     | 16 MB                                        |
| Wireless                  | Wi-Fi + Bluetooth                            |
| Interfaces                | USB Type-C, UART, GPIO, Ethernet, TF card    |
| Power                     | 5 V via Type-C (≤ 5 W)                       |
| Operating Temperature     | −20 °C ~ +70 °C                              |
| Housing                   | Matte black metal                            |
| Dimensions                | 70.7 × 124.7 × 27.39 mm                      |

---

## Useful Links

- Full tutorial: [How to Develop Custom Applications with LVGL on an ESP32-P4 LCD Display](https://www.aptusdisplay.com/info-detail/how-to-develop-custom-applications-with-lvgl-on-an-esp32-p4-lcd-display)
- Hardware product page: [A050EC01 5-Inch ESP32-P4 Capacitive Touch LCD Development Kit](https://www.aptusdisplay.com/products/5-inch-854c397480-esp32-p4-capacitive-touch-lcd-display-development-kit)
- LVGL official documentation: https://lvgl.io/docs
- ESP-IDF ESP32-P4 Getting Started: https://docs.espressif.com/projects/esp-idf/en/latest/esp32p4/get-started/index.html

---

## Suggested Repository Structure

```
ESP32-P4-LVGL-Custom-UI/
├── examples/                 # Sample projects (Arduino / ESP-IDF)
├── docs/                     # Extra notes, pinouts, screenshots
├── images/                   # UI screenshots and hardware photos
├── LICENSE
└── README.md
```

---

## Credits

Guide and hardware provided by [Aptus Display](https://www.aptusdisplay.com/).

---

## License

MIT License
```
