📖 Overview
ISS-25 Explorer is an interactive web project developed to celebrate the 25th anniversary of the International Space Station, created as part of the NASA Space Apps Challenge. The website offers a comprehensive experience to explore the ISS through a modern interface with full bilingual support (Arabic/English).

✨ Key Features
Feature	Description
🛰️ Live Tracking	Real-time ISS positioning with live trajectory updates
🌐 Cupola Simulation	Interactive 360° 3D experience from the Cupola module
📅 Historical Timeline	Journey through 25 years of ISS achievements
👨‍🚀 Life Aboard	Comprehensive guide to astronaut daily life
🌐 Bilingual	Full Arabic/English interface with RTL/LTR support
🛠️ Technologies Used
Frontend:

HTML5, CSS3, JavaScript (ES6+)

Tailwind CSS for responsive design

Three.js for 3D simulations

Leaflet.js for interactive maps

Data & Services:

NASA APIs (images and live data)

Wheretheiss.at for live tracking

CelesTrak for orbital calculations

Satellite.js for astronomical computations

🚀 Local Development
bash
# Clone the repository
git clone https://github.com/your-username/iss-25-explorer.git

# Navigate to directory
cd iss-25-explorer

# Run local server (requires Python)
python -m http.server 8000

# Or using Node.js
npx http-server
Supported Browsers: Chrome, Firefox, Safari, Edge

📁 Project Structure
text
iss-25-explorer/
├── index.html          # Main page
├── life.html           # Life aboard section
├── team.html           # Team members page
├── assets/
│   ├── images/         # Local images
│   ├── videos/         # Video files
│   └── icons/          # SVG icons
├── README.md
└── LICENSE
🤝 Contributing
We welcome contributions! Please follow these steps:

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

👥 Development Team
Team Members

🙏 Acknowledgments
NASA - Data and imagery

ESA - Technical information

OpenStreetMap - Mapping services
