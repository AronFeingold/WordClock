# WordClock

A word clock designed and built entirely from scratch — hardware and software.

## How it works
The clock displays the current time in plain English using a grid of letters,
with the relevant words lit up by NeoPixel LEDs behind a custom front panel.

1. The **ESP8266** connects to WiFi and syncs time via **NTP** (Network Time Protocol)
2. Time is handled using the **ezTime** library, which automatically manages GMT/BST switching
3. The firmware maps the current time to the correct LEDs and lights them up

## Components
| Part | Description |
|------|-------------|
| ESP8266 | WiFi-enabled microcontroller |
| NeoPixel LEDs | Addressable RGB LEDs for the letter grid |
| Custom front panel | Designed in Fusion 360, 3D printed |

## Features
- Automatic BST/GMT switching via NTP — no manual adjustment needed
- Custom Fusion 360 front panel design
- Fully hand-wired and soldered

## What I learned
- NTP time sync and timezone handling on embedded systems
- Driving addressable LEDs
- Fusion 360 CAD design for functional enclosures

## Built with
- C++ / Arduino IDE
- ezTime library

<img width="1216" height="913" alt="image" src="https://github.com/user-attachments/assets/6d52327a-1395-42fa-a5a1-a501ac6876aa" />
