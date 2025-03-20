# Recovery Journey Tracker

A clean, motivational web application designed to help individuals track and stay motivated during their recovery journey. Whether you're recovering from addiction, breaking a habit, or making a significant life change, this tracker helps you visualize progress, celebrate milestones, and stay inspired.

## Features

### 💫 Visual Progress Tracking

- **Interactive Flip Clock**: Tracks days, hours, minutes, and seconds of your recovery journey with a visually appealing animation
- **Progress Bar**: Visual representation of progress toward your next milestone
- **Achievement Celebrations**: Confetti animations and congratulatory messages when milestones are reached

### 🏆 Customizable Milestones

- **Default Milestones**: Pre-configured important milestones (1 day, 1 week, 1 month, 90 days)
- **Custom Milestones**: Add personalized milestones for your unique journey
- **Milestone Management**: Easily add or remove milestones as needed

### 🌟 Motivation Center

- **Motivational Quotes**: 30+ inspirational quotes that randomly display to keep you motivated
- **Benefits Timeline**: Visual roadmap showing the physical, mental, and lifestyle benefits at different stages of recovery
- **Daily Affirmations**: 20 positive affirmations you can cycle through for daily encouragement
- **Visualization Exercises**: 10 guided visualization prompts to help you mentally rehearse success

### 💾 Data Persistence

- **Local Storage**: Your journey data is saved to your browser's local storage
- **Privacy-Focused**: All data stays on your device - no accounts or servers required

## Installation

This is a standalone HTML/CSS/JavaScript application that runs entirely in the browser. No installation or build steps are required.

### Option 1: Direct Download

1. Download all files from this repository
2. Open `index.html` in any modern web browser

### Option 2: Clone Repository

```bash
git clone https://github.com/thor8126/recovery-journey-tracker.git
cd recovery-journey-tracker
# Open index.html in your browser
```

### Option 3: Run a Local Server (optional)

If you prefer to run a local development server:

With Python:

```bash
# Python 3
python -m http.server

# Python 2
python -m SimpleHTTPServer
```

With Node.js (requires http-server package):

```bash
npm install -g http-server
http-server
```

Then visit `http://localhost:8000` in your browser.

## Usage Guide

### Getting Started

1. When you first open the application, your journey begins immediately
2. The timer will start counting from zero
3. Default milestones are already set up (1 day, 1 week, 1 month, 90 days)

### Adding Custom Milestones

1. Click the "Add a milestone" button
2. Enter the day number for your milestone (e.g., 14 for two weeks)
3. Enter a description for your milestone (e.g., "Two weeks clean!")
4. Your new milestone will appear in the milestones list

### Resetting Your Counter

If you need to reset your counter:

1. Click the "Reset counter" button
2. Confirm the reset when prompted
3. The counter will restart from the current moment

### Using the Motivation Center

The Motivation Center has three tabs to help you stay motivated:

1. **Benefits**: View the timeline of recovery benefits at different stages
2. **Daily Affirmations**: Read positive affirmations and cycle through them with the "New Affirmation" button
3. **Visualization**: Use guided visualization prompts to picture your successful recovery

## Technologies Used

- **HTML5**: Core structure and semantics
- **CSS3**: Styling and animations, including:
  - Flexbox layouts
  - CSS animations
  - Custom properties (variables)
  - Media queries for responsiveness
- **JavaScript (ES6+)**: Dynamic functionality, including:
  - DOM manipulation
  - Local Storage API
  - Event handling
  - Dynamic content generation

No external libraries or frameworks are used, making this application lightweight and dependency-free.

## Browser Compatibility

This application is compatible with all modern browsers:

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Recovery Journey Tracker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to improve the application.

---

Made with ❤️ for those on their recovery journey
