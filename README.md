📱 Maestro E2E Testing for Wikipedia Android App
A comprehensive end-to-end mobile automation suite for the Wikipedia Android app using Maestro.
This project tests core user flows including authentication, home navigation, article search, saved pages, and settings—ensuring quality and stability across the app.

👤 Author
👨‍💻 Software QA Engineer
Passionate about building reliable, automated testing systems that ensure product quality and user experience.

📧 Email: ravrommelbanaag@gmail.com

🐱 GitHub: banaagravrommel

💼 Upwork: Upwork

✅ Features Tested
🔐 Main Flows
Sign in

Create account

Sign out

🏠 Home Navigation
Search articles

Edit article description

Explore content

Access saved articles

View notifications

📂 More Menu
Contributions

Places

Watchlist

Talk pages

Settings

Donation screen

🧰 Tech Stack
Maestro – Mobile UI testing framework

YAML – Test flow definitions

GitHub Actions – Optional CI integration

Android Emulator or real device (for test execution)

📁 Project Structure
bash
Copy
Edit
maestro-wikipedia/
│
├── maestro/
│   └── Flows/
│       ├── Home/
│       │   ├── edit.yaml
│       │   ├── explore.yaml
│       │   ├── notifications.yaml
│       │   ├── saved.yaml
│       │   ├── search.yaml
│       │   └── test.yaml
│       ├── Main/
│       │   ├── create_account.yaml
│       │   ├── sign_in.yaml
│       │   └── sign_out.yaml
│       └── More/
│           ├── contributions.yaml
│           ├── donate.yaml
│           ├── places.yaml
│           ├── settings.yaml
│           ├── talk.yaml
│           └── watchlist.yaml
│
├── .github/
│   └── workflows/
│       ├── main.yml
│       └── playwright.yml (Not used by Maestro)
│
├── package.json
└── README.md
🚀 Getting Started
1. Install Maestro CLI
bash
Copy
Edit
brew install maestro
Or manually via:

bash
Copy
Edit
curl -Ls "https://get.maestro.mobile.dev" | bash
2. Verify Installation
bash
Copy
Edit
maestro --version
3. Run a Flow
Make sure your emulator or physical device is running and then execute:

bash
Copy
Edit
maestro test maestro/Flows/Home/search.yaml
You can replace search.yaml with any other flow file you'd like to test.

⚠️ Notes
This test suite targets the official Wikipedia Android app.

Ensure the app is installed on your emulator or device before running tests.

Modify the flow files to match the app version or locale you're testing.

🧩 Contributing
Feel free to fork the repository and submit pull requests to improve test coverage or refactor flows.

