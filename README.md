# Yggdrasil — ESPHome

A collection of custom **ESPHome devices** built around my Home Assistant system.
It started with a simple problem: **protect the LG G5 OLED from direct sunlight**.
That became **Lightwatcher** — an ambient-light sensor that automatically lowers the blind when the sun gets too intense and raises it again when the light drops.

Then came **Birdwatcher** — an ESP32-S3 camera watching the bird feeder outside the window, helping identify who comes to visit.

And then came the **voice satellites**.

The satellites are custom ESP32-S3 devices for Home Assistant Assist, with microphones, speakers, displays, and room sensors. The most important part is not the hardware, though: **they speak Ukrainian**. That's something I couldn't simply buy in the form I wanted, so I built it.

## Projects

* **Satellite** — ESP32-S3 voice assistant with custom audio, display, and room sensors.
* **Satellite Lite** — a smaller voice-assistant node.
* **Lightwatcher** — sunlight protection for the LG G5 OLED.
* **Birdwatcher** — camera and bird detection for the feeder.

The detailed hardware, wiring, pin assignments and ESPHome configuration live in the YAML files themselves.

## Around the system

The main Home Assistant instance runs **Home Assistant Supervised on Debian Linux**, hosted on a **2014 Mac mini**.

The devices connect to Home Assistant through ESPHome, MQTT, Zigbee2MQTT, Matter and various APIs, depending on the problem being solved.

## Built with AI

There is another important part of the story: **I built this project with AI as a development partner.**

My background is in philology and more than a decade of work in IT recruitment rather than software engineering. AI helps me bridge that gap — turning ideas into code, helping me understand unfamiliar systems, and working through problems as I build.

But the architecture, experiments, hardware, 3D modeling, 3D printing, soldering, testing, debugging, and final decisions are mine.

For me, that's one of the most interesting things about this project: seeing how far a real technical system can be taken by someone coming from a completely different professional background, with AI as a collaborator.

## Status

This is an evolving project, built around real problems at home.
It started with keeping the sun off a TV. It just kept growing.