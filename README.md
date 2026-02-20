# JavaFX Gitpod Hello World

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A minimal JavaFX Hello World application configured to run in the cloud using Gitpod with VNC desktop support, enabling browser-based GUI development without any local setup.

## Overview

This project demonstrates the simplest possible JavaFX application running entirely in the browser via Gitpod. It creates a window with a single button that prints "Hello World!" to the console when clicked. The Gitpod configuration includes a VNC-enabled workspace with OpenJFX pre-installed, making it an ideal starting point for learning JavaFX without local environment setup.

## Features

- Minimal JavaFX Hello World application with button interaction
- One-click Gitpod deployment for instant cloud-based development
- VNC desktop environment for rendering JavaFX GUI in the browser
- Pre-configured Dockerfile with OpenJFX and Matchbox window manager
- Zero local setup required

## Prerequisites

- A [GitHub](https://github.com) account
- A [Gitpod](https://gitpod.io) account (free tier available)

## Getting Started

### Installation

1. Click the button below to open this project directly in Gitpod:

   [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/danielcregg/javaFX-gitpod-helloworld-basic)

2. Alternatively, clone and run locally (requires JavaFX):
   ```bash
   git clone https://github.com/danielcregg/javaFX-gitpod-helloworld-basic.git
   cd javaFX-gitpod-helloworld-basic
   ```

### Usage

1. When Gitpod opens, click the **Ports** button in the bottom status bar.
2. Open port **6080** in the browser to view the VNC desktop.
3. In the Gitpod terminal, compile and run the application:
   ```bash
   javac HelloWorld.java && java HelloWorld
   ```
4. Switch to the VNC browser tab to see the JavaFX GUI. Click the button to print "Hello World!" to the console.

## Tech Stack

- **Language:** Java
- **Framework:** JavaFX (OpenJFX)
- **Cloud IDE:** Gitpod
- **Desktop:** VNC via gitpod/workspace-full-vnc
- **Window Manager:** Matchbox

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.