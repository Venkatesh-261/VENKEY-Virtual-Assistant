# VENKEY-Virtual-Assistant

🎤 VENKEY Virtual Assistant

VENKEY Virtual Assistant is a browser-based voice-controlled AI assistant built using HTML, CSS, and JavaScript. It uses modern Web Speech APIs to recognize user voice commands and respond with synthesized speech. The assistant can greet users, open popular websites, provide real-time information like date and time, and perform smart searches, all while offering a clean, interactive user interface.

📝 Project Description

The VENKEY Virtual Assistant brings a hands-free interaction experience directly in the browser. It acts as a personal digital assistant, enabling simple voice commands to trigger actions like browsing, searching, and retrieving information. With a lightweight architecture, it demonstrates how speech recognition and synthesis can be used to build engaging front-end projects.

🔑 Key Features

👤 Voice Interaction

Captures user speech using SpeechRecognition API.

Responds naturally via SpeechSynthesisUtterance.

🌐 Smart Web Navigation

Opens websites like Google, YouTube, Facebook, Wikipedia via commands.

Performs live Google search queries when a command is not recognized.

🕑 Real-Time Utilities

Announces the current time and date.

Provides greetings based on the time of day (morning, afternoon, evening).

🎨 User Interface

Dark-themed, responsive design.

Animated assistant GIF and microphone control button.

Displays the spoken text for user confirmation.

⚙ Tech Stack
Layer	Technology Used
Frontend	HTML5, CSS3, Font Awesome, Google Fonts
Scripting	JavaScript (Web Speech API: SpeechRecognition & SpeechSynthesis)
Assets	Avatar icon, Animated GIF (giphy.gif)
🧱 Technical Architecture

Client-Side Application Only

UI/UX Layer: HTML5, CSS3 styling, dark theme interface.

Speech Layer: Web Speech API for recognition & synthesis.

Command Layer: JavaScript function takeCommand() parses voice commands and maps them to actions.

Output Layer: Opens new browser tabs/windows for websites, provides audio responses.

📂 Project Structure
VirtualAssistant/
├── index.html
├── style.css
├── app.js
├── avatar.png
├── giphy.gif
└── README.md

🚀 Getting Started
Prerequisites

Modern browser (Google Chrome recommended).

Run the Project

Clone the repository:

git clone https://github.com/your-username/VirtualAssistant.git
cd VirtualAssistant


Open index.html in your browser.

Click the microphone button 🎤 and start speaking commands.

👨‍💼 Use Case Scenario

A user opens the assistant in the browser.

Clicks on the microphone button and says:

“Open YouTube” → YouTube opens in a new tab.

“What is Python?” → Google search results open with spoken feedback.

“What’s the time?” → Assistant announces the current time.

The assistant continuously listens and responds with natural speech.

📷 Project Demo

🎥 Demo Video (if available) – [Add Google Drive/YouTube demo link]

🧪 Testing

Browser Console: For debugging recognition and commands.

Speech Recognition: Test with multiple accents and phrases.

Cross Browser: Works best on Chrome; limited support in other browsers.

📌 License

This project is open-source and available under the MIT License.

👨‍💻 Author

💡 Prepared by: C.VENKATESH
