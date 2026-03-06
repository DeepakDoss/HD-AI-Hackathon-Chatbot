# HD AI - The Hackathon Chatbot Assistant 🚀

**HD AI** is a premium, AI-powered chatbot designed specifically to help participants survive and thrive in hackathons. From choosing the right tech stack to perfecting your final pitch, HD AI is your 24/7 dedicated mentor.

![HD AI Dashboard](public/logo.png)

## ✨ Features

- **🧠 Specialized AI Mentorship**: Powered by Meta-Llama-3-8B-Instruct, providing concise, expert advice on ideation, tech stacks, and presentations.
- **🎨 Premium UI/UX**: A modern, sleek interface with smooth transitions, splash screens, and a choice between **Dark** and **Light** modes.
- **🔐 Secure Local Auth**: Integrated registration and login system that stores user sessions locally.
- **📜 Chat History**: Never lose your progress. All conversations are saved and can be revisited or managed through the persistent sidebar.
- **💡 Quick-Start Cards**: Instant prompts for common hackathon questions like "What to bring?" or "How to pitch?".
- **📱 Fully Responsive**: Works perfectly on both desktop and mobile devices.

## 🛠️ Tech Stack

- **Frontend**: Vanilla JavaScript (ES6+), CSS3 (Custom Properties), HTML5.
- **Backend**: Node.js & Express.
- **AI Integration**: Hugging Face Inference API (Llama-3-8B).
- **Icons & Fonts**: Font Awesome, Google Fonts (Inter).

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16.x or higher)
- A [Hugging Face](https://huggingface.co/) Account (for API Access)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd hackathon-proj
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory and add your Hugging Face Access Token:
   ```env
   HF_ACCESS_TOKEN=your_hugging_face_token_here
   PORT=3000
   ```

4. **Start the server:**
   ```bash
   npm start
   ```

5. **Open the app:**
   Navigate to `http://localhost:3000` in your web browser.

## 📁 Project Structure

```text
├── public/              # Frontend assets
│   ├── index.html       # Main entry point
│   ├── styles.css       # Premium styling & themes
│   ├── script.js        # Core logic & AI integration
│   └── assets/          # Images, icons, and favicons
├── server.js            # Express backend & API bridge
├── .env                 # Environment variables (API Keys)
└── package.json         # Node.js dependencies
```

## 📝 License

This project is licensed under the ISC License.

---
Built with ❤️ for Hackers everywhere. 🚀
