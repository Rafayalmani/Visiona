#✦ Visiona AI
Visiona AI is a next-generation, high-performance AI interface designed for seamless interaction with both Large Language Models (LLMs) and Image Generation models. Featuring a "Midnight Slate" glassmorphism UI, it automatically detects user intent to switch between chat and artistic rendering.

🚀 Features
Smart Intent Detection: No need to toggle modes. If you ask a question, it chats. If you describe a scene, it generates art.

Dual-Engine Power: * Text: Powered by GPT-4o / Gemini via Pollinations.

Images: High-fidelity 1024x1024 renders using the FLUX model.

Contextual File Reading: Upload .txt, .js, or .py files directly into the chat for instant analysis and debugging.

Session Management: LocalStorage integration to save your conversations across browser refreshes.

Fully Responsive: Optimized for desktop, tablets, and mobile devices.

🛠️ Tech Stack
Frontend: HTML5, CSS3 (Custom Variables & Flexbox/Grid), JavaScript (ES6+).

APIs: Pollinations.ai (Text & Image endpoints).

Storage: Browser localStorage for session persistence.

Icons: Custom SVG & Unicode Glyphs.

📥 Installation & Setup
Clone the repository:

Bash
git clone https://github.com/Rafayalmani/visiona.git
Open the project:
Simply open index.html in any modern web browser.

API Configuration:
Open the script section in index.html and ensure your API_KEY is set:

JavaScript
const API_KEY = "your_api_key_here";
📂 Project Structure
Plaintext
├── index.html          # Main application file (UI + Logic)

└── README.md           # Project documentation
🛡️ Security Note
[!WARNING]
The current version uses client-side API calls. For production environments, it is highly recommended to move the API_KEY to a backend proxy (Node.js/Vercel) to prevent exposure in the browser's Network tab.

👨‍💻 Author
Rafay Almani Full Stack Developer Portfolio 