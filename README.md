# task_2_dev_t_gadani

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

//test


# LG AIRPORT CONTROLLER SIMULATOR

## Table of Contents
1. [About](#about)
2. [Requirements](#requirements)
3. [Server Setup](#server-setup)
4. [Mobile Connection](#mobile-connection)
5. [Functionalities](#functionalities)
6. [Technical Stack](#technical-stack)

## About

The goal of an airport controller is to guide air traffic, prevent airplanes from overlapping or colliding, and ensure they take off and land safely at the airport.

This project consists of a comprehensive airport traffic control simulation system with the following components:

- **Node.js Server**: Handles all communication and coordination between different components
- **Chromium Client**: A browser-based interface using plain JavaScript and HTML to display real-time airplane animations across multiple screens
- **Flutter Controller App**: A mobile application that serves as the primary control interface, providing:
  - Start, stop, pause, and restart functionality for both simulation and server
  - Text-to-speech feature that announces airplane commands
  - Customizable voice settings for enhanced user experience
  - Real-time control of aircraft movements and airport operations

The system is designed to work seamlessly with Liquid Galaxy (LG) rigs, providing an immersive multi-screen experience for air traffic control simulation.

## Requirements

### Server Requirements
- **Node.js Version**: 4.2.6 (default version available in LG systems)
- Compatible with Liquid Galaxy infrastructure

### Mobile App Requirements
- **Android Version**: 13+ (maximum supported version)
- Flutter-compatible device

## Server Setup

1. **Download and Extract**
   - Download the project ZIP file
   - Extract it to your home directory
   - Keep the default Git repository name for the folder

2. **Initial Setup**
   - Navigate to the extracted folder
   - Ensure Node.js 4.2.6 is installed and accessible

## Mobile Connection

### Step 1: Read Instructions
- Open the mobile app
- You will see an instruction page upon first launch
- **Important**: Read the instructions carefully as they contain important rules and operational information

### Step 2: Connect to LG
- Navigate to the **Settings** section in the app
- Connect to the Liquid Galaxy rig first
- Wait for successful connection confirmation

### Step 3: Start Server
- After successful LG connection, go to **Settings** → **Game Task**
- Start the server from this section
- **Note**: Server startup may take some time
- Wait patiently as the system will automatically open Chromium on all screens of the rig

### Step 4: Begin Simulation
- Once all screens are connected and displaying properly, start the game
- The simulation will begin with planes automatically departing from other airports
- **Your Tasks**:
  - Manage incoming aircraft safely
  - Handle plane takeoffs in the directions specified in the right tab on the home screen
  - Available planes for takeoff will be displayed in the designated area

## Functionalities

### Game Controls
- **Pause**: Temporarily halt the simulation
- **Resume**: Continue paused simulation
- **Start**: Begin new simulation session
- **Stop**: End current simulation

### Server Controls
- **Start**: Initialize the communication server
- **Stop**: Shut down the server safely

### Additional Features
- Real-time aircraft tracking and management
- Multi-screen display support for Liquid Galaxy
- Voice announcements with customizable settings
- Interactive control interface optimized for mobile devices

## Technical Stack

- **Backend**: Node.js with Socket.IO for real-time communication
- **Frontend**: Plain JavaScript and HTML for browser-based visualization
- **Mobile App**: Flutter framework for cross-platform compatibility
- **Communication**: WebSocket connections via Socket.IO for real-time data exchange

## Acknowledgments

I would like to express my sincere gratitude to all the mentors and team members who supported this project:

### Mentors
- **Vedant** - Main Mentor, for invaluable guidance and technical expertise
- **Rosemarie Garcia** - Secondary Mentor, for continuous support and feedback
- **Prayag Biswas** - Secondary Mentor, for technical insights and project direction

### Liquid Galaxy LAB Team
Special thanks to the entire team at Liquid Galaxy LAB Lleida, the headquarters of the Liquid Galaxy project:

**Team Members**: Alba, Paula, Josep, Jordi, Oriol, Sharon, Alejandro, Marc  
**Administrator**: Andreu

Their continuous support, expertise, and dedication made this project possible.

**More Information**: [www.liquidgalaxy.eu](http://www.liquidgalaxy.eu)

## Useful Repositories

The following repositories were instrumental in the development of this project:

## Gallery 
![game1](./images/gamescreenshot.webp )
![game1](./images/gamescreenshot2.jpg )
![game1](./images/gamescreenshot.webp )
![game1](./images/gamescreenshot.webp )
![game1](./images/gamescreenshot.webp )


### Core Technologies
### Liquid Galaxy Resources
- **Liquid Galaxy Scripts**: [https://github.com/LiquidGalaxyLAB/liquid-galaxy](https://github.com/LiquidGalaxyLAB/liquid-galaxy)

### Reference Projects
- **Galaxy Pacman**: [project that gave reference to screen management](https://github.com/LiquidGalaxyLAB/galaxy-pacman)
- **LG RetroGaming**: [Give understanding for screen number as in head LG lab ](https://github.com/LiquidGalaxyLAB/lg-retro-gaming)

<!-- License Badge -->
![License](https://img.shields.io/github/license/devtgadani/task_2_dev_t_gadani)

<!-- Languages Count -->
![Languages](https://img.shields.io/github/languages/count/devtgadani/task_2_dev_t_gadani)

<!-- Top Language -->
![Top Language](https://img.shields.io/github/languages/top/devtgadani/task_2_dev_t_gadani)

<!-- Issues -->
![Issues](https://img.shields.io/github/issues/devtgadani/task_2_dev_t_gadani)

<!-- Forks -->
![Forks](https://img.shields.io/github/forks/devtgadani/task_2_dev_t_gadani)

<!-- Stars -->
![Stars](https://img.shields.io/github/stars/devtgadani/task_2_dev_t_gadani)

<!-- Repo Size -->
![Repo Size](https://img.shields.io/github/repo-size/devtgadani/task_2_dev_t_gadani)
---

*This simulator provides an educational and engaging way to understand air traffic control operations while showcasing the capabilities of Liquid Galaxy technology.*

