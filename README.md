<h1 align="center">🤖  VBot - Ultimate Ai App</h1>

<p align="center">
  A beautiful AI-powered chatbot built with <strong>Flutter</strong> using the <strong>Gemini API</strong>, <strong>GetX</strong> for state management, and <strong>Chat Bubbles</strong> for sleek UI.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-Chatbot-blue?logo=flutter&style=flat-square" />
  <img src="https://img.shields.io/badge/Gemini%20API-AI-yellow?logo=google&style=flat-square" />
  <img src="https://img.shields.io/badge/GetX-State%20Management-purple?style=flat-square" />
  <img src="https://img.shields.io/badge/Chat%20UI-Cool%20Bubbles-green?style=flat-square" />
</p>

---

<h2>✨ Features</h2>

<ul>
  <li>🤖 Gemini API-powered smart chat responses</li>
  <li>⚡ GetX state management for reactive updates</li>
  <li>💬 Beautiful chat UI using <code>chat_bubbles</code> package</li>
  <li>🌐 Simple integration using <code>http</code> package</li>
  <li>🎨 Fully responsive UI with gradients and modern design</li>
</ul>

---


---

<h2>🧰 Tech Stack</h2>

| Technology        | Usage                            |
|------------------|----------------------------------|
| Flutter           | UI Framework                     |
| Dart              | Programming Language             |
| Gemini API        | Chatbot intelligence             |
| GetX              | State management                 |
| Chat Bubbles      | Modern chat UI                   |
| HTTP              | API requests                     |

---

<h2>🚀 Getting Started</h2>

```bash
git clone https://github.com/your-username/gemini-chatbot-flutter.git
cd gemini-chatbot-flutter
flutter pub get
```

<h2>🔑 Setup Gemini API Key</h2>
Visit <a href="https://makersuite.google.com/app/apikey" target="_blank">Gemini API Key Page</a>

Generate an API key.

Create a file: lib/constant/api_constants.dart:

```
<h2>📂 Folder Structure</h2>

lib/
├── controller/
│   └── message_controller.dart
├── screens/
│   └── chat_screen.dart
├── constant/
│   └── api_constants.dart
├── main.dart
```
```
<h2>🧠 Example Gemini API Call</h2>

final response = await http.post(
  Uri.parse("${ApiContant.baseUrl}${ApiContant.apiKey}"),
  headers: {'Content-Type': 'application/json'},
  body: jsonEncode({
    "contents": [
      {
        "parts": [{"text": message}]
      }
    ]
  }),
);

```

<h2>💡 UI Highlights</h2>

- Gradient AppBar

- Floating action button to send messages

- Animated chat bubbles

- Responsive layout

- Modern fonts and icons

<h2>🤝 Contributing</h2>
Contributions are welcome! If you find a bug or have a feature request, feel free to open an issue or a pull request.


