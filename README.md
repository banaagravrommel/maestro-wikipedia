🧪 Maestro E2E Testing for Wikipedia Alpha App
An end-to-end automation suite using Maestro to test the Wikipedia Alpha Android application. This project validates core user flows such as onboarding, search functionality, article navigation, and UI responsiveness. It leverages Maestro's declarative syntax for fast, readable, and maintainable mobile test automation.
GitHub

👤 Author
👨‍💻 Software QA Engineer
Passionate about building reliable, automated testing systems that ensure product quality and user experience.
Email: ravrommelbanaag@gmail.com
GitHub: banaagravrommel
Upwork: Upwork

✅ Features Tested
🚀 Onboarding Flow

Skip or complete onboarding steps

Language selection and confirmation
GitHub
+1
Wikipedia
+1

🔍 Search Functionality

Search for articles using keywords

Validate search results and navigation to articles
Wikipedia
+1
Wikipedia
+1

📄 Article Navigation

Scroll through article content

Verify presence of images, links, and references
Wikipedia
+4
Wikipedia
+4
Wikipedia
+4
GitHub Docs

🎨 UI Components

Check visibility of toolbar, tabs, and menus

Validate theme changes and responsiveness
Wikipedia
+2
Wikipedia
+2
Wikipedia
+2

🔄 App Lifecycle

Background and foreground transitions

Handle device rotations and state persistence

🧰 Tech Stack
Maestro (latest version)

Android Emulator or real device

YAML for test flow definitions

GitHub Actions (for optional CI integration)

📁 Project Structure
bash
Copy
Edit
maestro-wikipedia/
├── android-app/             # Wikipedia Alpha APK and related files
├── maestro/                 # Maestro test flows
│   └── Flows/
│       ├── onboarding.yaml
│       ├── search.yaml
│       ├── article_navigation.yaml
│       └── ui_components.yaml
├── test-results/            # Test execution logs and artifacts
├── .github/
│   └── workflows/
│       └── maestro-ci.yml   # CI configuration
├── .gitignore
├── package.json             # Project metadata and dependencies
└── README.md                # Project documentation
🚀 Getting Started
1. Install Maestro CLI
Follow the official installation guide: https://maestro.mobile.dev/getting-started/

2. Run Tests
bash
Copy
Edit
maestro test maestro/Flows/onboarding.yaml
Repeat the command for other test flows as needed.

3. View Test Results
Test execution logs and artifacts are saved in the test-results/ directory.

⚠️ Important Notes
Ensure that the Wikipedia Alpha app is installed on your emulator or device before running tests.

Tests are designed for the Alpha version; compatibility with other versions is not guaranteed.

🏁 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests for improvements or additional test flows.

