🐟 Kenya Fishing Guide
Kenya Fishing Guide is a web application that helps local fishers, hobbyists, and researchers locate fishing spots, log fish catches, access weather data, and share fish sightings across different regions in Kenya. It combines real-time environmental insights with community sharing tools to promote sustainable fishing.

🌐 Features {TAKE NOTE ALL THE REQUIRED APIS AND MACHINE LEARNING STUFF ARE MISSING DUE TO NOT FULLY EQUIPPED MY SKILLS IN THESE PARTS}
🌍 Multi-language Support – Users can select from a dropdown listing all world languages for easy accessibility.

📍 Fishing Spot Maps – Interactive maps (Google Maps integrated) displaying fishing points across Kenyan water bodies.

🌤️ Weather Integration – Real-time weather updates for different fishing locations to aid in planning.

🐠 Fish Species Info – View fish types categorized by region and water body.(NOT DONE WITH APIS)

📝 Fish Catch Log – Users can log catches with location, time, fish type, and quantity.

📸 Image/Video Upload – Share newly discovered or rare fish species through images and videos.(Not fully developed since not covered machine learning with AI)

🧠 AI Fish Recognition – Upload a photo of a fish and get identification assistance (planned feature).

👤 User Authentication – Secure sign-up/login system with profile picture upload.

💬 Interactive UI – Dynamic, animated interface with moving backgrounds and fish animations for an immersive feel.

🛠️ Tech Stack
Frontend:

HTML, CSS, JavaScript

 CSS (for styling)

Google Maps JavaScript API


Other Integrations:

Weather API (e.g., OpenWeatherMap)

Google Maps API

AI Image Recognition API (planned)

🔧 Installation and Setup
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/kenya-fishing-guide.git
cd kenya-fishing-guide
Database Setup

Import the fishing_guide.sql file into your MySQL server.

Configure your database credentials in config.php.


API Configuration

Insert your API keys in the respective configuration files:.(I am still working on APIs)

weatherConfig.js

mapConfig.js

Run the website

Open https://luond-glitch.github.io/kenya-fishing/ in your browser.

📁 Project Structure
bash
Copy
Edit
kenya-fishing-guide/
│
├── assets/               # Images, fish icons, videos
├── css/                  # Styling files
├── js/                   # JS scripts (weather, maps, UI)
├── php/                  # Backend PHP scripts
├── uploads/              # User-uploaded media
├── index.html            # Landing page
├── login.html            # User login
├── dashboard.html        # Main user interface
├── config.php            # DB credentials
└── README.md
📈 Future Enhancements
✅ Add language translation API for full site translation.

✅ Expand user profiles to show activity history and stats.

🔄 AI-powered fish recognition from uploaded photos.

🔄 Offline access via a PWA (Progressive Web App).

🔄 Admin dashboard to manage uploaded content and species data.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Please fork the repo and submit a pull request.

🧑‍💻 Developer
Sylvester Otieno
Software Engineering Student | Environmental Tech student @ cooperative University of Kenya
LinkedIn • GitHub

