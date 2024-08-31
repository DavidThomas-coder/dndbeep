# Beeping Timer

This project is a simple beeping timer implemented in HTML, CSS, and JavaScript originally designed for a Dungeons & Dragons puzzle. The timer starts at 60 seconds and counts down to zero, with a beeping sound that increases in frequency as the timer approaches zero. The timer is controlled by a button that starts and resets the countdown.

## Features

- **Dynamic Countdown Timer**: The timer starts at 60 seconds and counts down to zero.
- **Increasing Beep Frequency**: As the timer counts down, the beep frequency increases, creating a sense of urgency.
- **Start/Reset Button**: The timer only starts when the button is clicked and can be reset at any time.

## How It Works

- When the user clicks the "Start/Reset Timer" button, the timer starts counting down from 60 seconds.
- The timer displays the remaining seconds on the screen.
- The beeping sound is triggered at intervals that decrease as the countdown progresses, causing the beeps to occur more frequently as the timer nears zero.
- If the timer reaches zero, an alert is displayed saying "Time's up!".
- Clicking the button while the timer is running will reset the timer to 60 seconds and start it again.

## Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- A local audio file named `beep-3.wav` (placed in the same directory as the HTML file).

## Installation

1. **Download or Clone the Repository**:
   ```bash
   git clone https://github.com/DavidThomas-coder/dndbeep.git
Place the Audio File: Ensure that the beep.wav audio file is in the same directory as the index.html file.

Open the HTML File: Double-click the index.html file to open it in your default web browser.


