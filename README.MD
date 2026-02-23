🕐 Smart Queue

A modern, responsive Queue Management System web application built with HTML and Tailwind CSS — designed for desktop with full mobile responsiveness.

Show Image Show Image Show Image Show Image

📸 Preview
Smart Queue provides a clean dashboard interface that allows users to:

Join virtual queues at hospitals, banks, government offices, and more
Track their real-time queue position and estimated wait time
Receive notifications when their turn is approaching
View and manage their profile and visit history


✨ Features

Live Queue Tracking — See your ticket number, who's being served now, and how many people are ahead of you
Active Queue Banner — Full-width hero card with a real-time progress bar
Branch Directory — Browse and join queues at multiple institution types (Bank, Hospital, Government, etc.)
Stats Dashboard — At-a-glance cards showing visits, wait times, and queue status
Profile Card — User info, visit count, and average wait time
Real-time Notifications — Alerts when your turn is approaching or queue status changes
Responsive Design — Sidebar layout on desktop; bottom navigation bar on mobile
Tab Filtering — Filter branches by category (All, Bank, Hospital, Gov)
Hover Interactions — Action buttons reveal on branch row hover


🛠️ Tech Stack
TechnologyPurposeHTML5Structure and markupTailwind CSS (CDN)Utility-first stylingGoogle FontsPlus Jakarta Sans typographyVanilla JavaScriptTab switching & nav interactions

No frameworks, no build tools, no dependencies to install — just open and run.


🚀 Getting Started
1. Clone the repository
bashgit clone https://github.com/byiringirojeanbosco/Cat_practique.git
cd smart-queue
2. Open in browser
Simply open smart-queue.html in any modern browser:
bash# macOS
open smart-queue.html

# Windows
start smart-queue.html

# Linux
xdg-open smart-queue.html
Or use a local dev server (optional):
bash# Using VS Code Live Server extension — right-click smart-queue.html → "Open with Live Server"

# Using Python
python -m http.server 8080
# Then visit http://localhost:8080/smart-queue.html

📁 Project Structure
smart-queue/
├── smart-queue.html     # Main application file (single-file app)
└── README.md            # Project documentation

The entire app lives in a single HTML file — no separate CSS or JS files required.


📱 Responsive Behavior
Screen SizeLayoutDesktop (> 768px)Fixed left sidebar + main content areaMobile (≤ 768px)Sidebar hidden, fixed bottom navigation bar
The layout adapts automatically using Tailwind's responsive utilities and CSS media queries — no JavaScript required for the responsive toggle.

🎨 Design Highlights

Color Palette — Primary blue (#1a56db), success green (#16a34a), alert red (#dc2626)
Typography — Plus Jakarta Sans (Google Fonts) for a modern, clean look
Animations — Fade-up entrance animations with staggered delays, pulsing active indicators, smooth hover transitions
Cards — Rounded-2xl cards with subtle borders and hover shadow effects
Queue Hero — Dotted radial grid pattern overlay for depth and visual interest


🔧 Customization
Change the active user
Edit the user details in the sidebar footer and profile card sections:
html<!-- Sidebar footer -->
<p class="text-sm font-semibold text-gray-800 truncate">Jean Bosco</p>
<p class="text-xs text-gray-400 truncate">#QN0-1N5N4X34</p>
Add or remove branches
Copy a branch row block inside the .branches-grid div and update the name, icon color, and queue info.
Update queue numbers
Find the queue stats in the Active Queue Banner and Stats Grid sections and update the numbers to match your live data source.

🗺️ Roadmap

 Backend integration (Node.js / Firebase)
 Real-time queue updates via WebSockets
 QR code ticket generation
 SMS/email notifications
 Admin dashboard for branch managers
 Multi-language support
 PWA (Progressive Web App) support for offline use


🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository
Create a new branch: git checkout -b feature/your-feature-name
Commit your changes: git commit -m 'Add some feature'
Push to the branch: git push origin feature/your-feature-name
Open a Pull Request


📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

👤 Author
Byiringiro Jean Bosco(25RP00721)


GitHub: @Byiringiro Jean Bosco


<p align="center">Made with ❤️ using HTML & Tailwind CSS</p>