🎵 Pi Music
Transform mathematical constants into generative music in real-time

https://img.shields.io/badge/Live-Demo-brightgreen
https://img.shields.io/badge/License-MIT-blue.svg
https://img.shields.io/badge/Made%2520with-JavaScript-yellow

"Listen to the sound of π - the king of numbers"

🎹 What is Pi Music?
Pi Music is an interactive web application that converts the infinite digits of π (pi) into musical notes in real-time. Each digit (0-9) is mapped to a specific musical note, creating an endless, unique composition based on the mathematical constant.

✨ Features
🎵 Audio Features
Infinite Pi Generation: Generates π digits on-the-fly for endless music

Multiple Sound Sources:

Real π (infinite digits)

22/7 approximation

Custom digit sequences

Musical Scales: Major, Minor, Pentatonic, Chromatic, or custom mapping

Waveform Selection: Sine, Square, Sawtooth, or Triangle waves

Customizable Tempo: Control playback speed (50ms to 2000ms per note)

🎨 Visual Features
Real-time Visualization: See the current π digits and corresponding notes

Custom π Cursor: Unique π symbol cursor that follows your movements

Interactive Controls: Intuitive UI with glassmorphism effects

Live Statistics: Track digits played, notes played, and playtime

Note Mapping Display: Visual representation of digit-to-note mappings

⚙️ Customization
Chunk Size Control: Play π in chunks of 1-50 digits

Custom Note Mapping: Assign specific frequencies to each digit (0-9)

Custom Digit Input: Input any digit sequence for unique compositions

Responsive Design: Works on desktop and mobile devices

🚀 Quick Start
Online Demo
Visit the live demo: https://your-username.github.io/pi-music

Local Installation
Download the application:

Download as ZIP

Clone the repository:

bash
git clone https://github.com/your-username/pi-music.git
Run locally:

Simply open index.html in any modern web browser

No installation or dependencies required!

Optional - Host it yourself:

Upload to GitHub Pages, Netlify, Vercel, or any static hosting

It's 100% client-side - no server needed!

🎮 How to Use
Basic Usage
Click the "Play" button to start the music

Select "Real π" for infinite Pi music

Adjust Tempo to control playback speed

Change Chunk Size to group digits differently

Experiment with different Musical Scales

Advanced Features
Custom Digit Sequences:

Select "Custom" from Pi Source

Enter any digit sequence (e.g., your phone number, birthday)

Click "Play" to hear your custom composition

Custom Note Mapping:

Select "Custom" from Musical Scale

Set specific frequencies (in Hz) for each digit

Create your own musical scale

Waveform Experimentation:

Try different waveforms (Sine, Square, etc.)

Each creates a distinct sound texture

Square waves sound like retro video games!

📁 Project Structure
text
pi-music/
├── index.html          # Main application file
├── README.md           # This documentation
├── LICENSE             # MIT License file
├── screenshots/        # Application screenshots
│   ├── main-ui.png
│   ├── custom-mapping.png
│   └── mobile-view.png
└── assets/             # Optional: For additional resources
    └── pi-digits.txt   # Extended Pi digits file
🛠️ Technical Details
Built With
HTML5 - Structure and semantics

CSS3 - Styling with modern effects (glassmorphism, gradients, animations)

Vanilla JavaScript - No frameworks or dependencies

Web Audio API - Real-time audio synthesis

Canvas API - Visualizations (optional extension)

Key Algorithms
Pi Digit Generation: Simple spigot algorithm for on-the-fly generation

Audio Synthesis: Web Audio API oscillators with configurable waveforms

Chunk Processing: Executes digits in configurable groups with real-time feedback

Custom Cursor: JavaScript-based π cursor with trail effects

🔧 For Developers
Extending the Project
Want to add more features? Here are some ideas:

javascript
// Add more mathematical constants
const constants = {
    e: "2.718281828459045...",
    phi: "1.618033988749894...",
    sqrt2: "1.414213562373095..."
};

// Add rhythm patterns
const rhythms = {
    binary: (digit) => digit % 2 === 0 ? 'short' : 'long',
    prime: (digit) => isPrime(digit) ? 'accent' : 'normal'
};

// Export as MIDI
function exportToMIDI(sequence) {
    // Implement MIDI export functionality
}
Building & Deployment
bash
# For production optimization (optional)
npm install -g uglify-js
uglifyjs script.js -o script.min.js
🌐 Deployment Options
1. GitHub Pages (Free)
Create a GitHub repository

Push your code

Go to Settings → Pages → Select "main branch"

Your site will be at: https://username.github.io/repository-name

2. Netlify/Vercel (Free)
Drag & drop your index.html file

Instant deployment with HTTPS

Custom domain support

3. As a Desktop App (Using Electron)
bash
npm init -y
npm install electron
# Create main.js and package.json
# Package with: npm run build
4. As a Mobile App (Using Capacitor)
bash
npm install @capacitor/core @capacitor/cli
npx cap init
npx cap add android
npx cap add ios
📱 Mobile Support
The application is fully responsive and works on:

✅ Desktop browsers (Chrome, Firefox, Safari, Edge)

✅ Mobile browsers (iOS Safari, Android Chrome)

✅ Tablet devices

✅ Touch screen interactions

📄 License
MIT License - See LICENSE file for details.

Important Attribution Requirement:

You are free to use, modify, and distribute this software, but you MUST give credit to the original author. You cannot copy this project and claim it as your own creation without proper attribution.

markdown
Credits:
Pi Music by [Your Name]
https://github.com/your-username/pi-music
🙏 Acknowledgments
π digits calculated by mathematicians worldwide

Web Audio API by W3C

Inspired by the beauty of mathematics and music

Special thanks to all contributors and testers

🤝 Contributing
Contributions are welcome! Please:

Fork the repository

Create a feature branch

Commit your changes

Push to the branch

Open a Pull Request

🐛 Issues & Support
Found a bug or need help?

Check the Issues page

Create a new issue with details

Or email: your-email@example.com

📊 Statistics
Lines of Code: ~800

File Size: < 50KB

Browser Support: Chrome 60+, Firefox 55+, Safari 11+

Performance: 60 FPS with Web Audio API

🎯 Ready to Download?
Option 1: Single HTML File
Download pi-music.html and open in any browser.

Option 2: Complete Package
Download ZIP containing all files.

Option 3: Desktop Application
Coming soon: Electron wrapper for Windows/Mac/Linux.

🌟 Star History
If you like this project, please give it a star! ⭐

https://api.star-history.com/svg?repos=your-username/pi-music&type=Date

Made with ❤️ by [Your Name]
Turning mathematics into music, one digit at a time
