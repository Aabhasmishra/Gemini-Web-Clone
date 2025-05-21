# Gemini AI Chat Clone

A responsive Gemini AI chat interface with theme switching, local chat history, and markdown support.

## Features

- 💬 Real-time chat with Gemini API
- 🌓 Light/dark theme toggle
- 📝 Markdown support with syntax highlighting
- 📋 Copy code/prompt functionality
- 💾 Local storage for chat history
- ✨ Typing animation effects
- 📱 Mobile responsive design

## Technologies

- HTML5, CSS3, JavaScript
- [Gemini API](https://ai.google.dev/)
- [Marked.js](https://marked.js.org/) - Markdown parsing
- [Highlight.js](https://highlightjs.org/) - Syntax highlighting
- [Boxicons](https://boxicons.com/) - Icons

## Setup

1. Get your Gemini API key from [Google AI Studio](https://ai.google.dev/)
2. Replace `Google_API_Key` in `script.js`
3. Open `index.html` in browser

```html
const Google_API_Key = "YOUR_API_KEY_HERE"; // Replace this
```

## 🛠️ Usage
### 💬 Chatting
1. Type your prompt in the input field at the bottom
2. Press Enter or click the send button (→)
3. Alternatively, click any suggestion to auto-fill

### 🎨 Theme Toggle
- Click the moon/sun icon (top-right) to switch between dark/light modes
- Theme preference saves automatically

### 🗑️ Clearing History
- Click the trash icon (next to send button) 
- Confirms before deleting all chat history

### 📋 Copying Responses
- Hover any AI response and click the copy icon (📋)
- Icon changes to (✓) briefly when copied

### ⌨️ Keyboard Shortcuts
- Enter       : Send message
- Ctrl/Cmd+/  : Toggle theme

## Screenshots
![Screenshot 2025-04-07 004329](https://github.com/user-attachments/assets/e3483215-5773-47c9-af77-a4b48e5b681e)

## 💻 Contributions

Contributions are welcome! Follow these steps:

1. **Fork** the [repository](https://github.com/Aabhasmishra/Gemini-Web-Clone)
2. Create a **branch** (`git checkout -b feature/your-feature`)
3. **Commit** changes (`git commit -m 'Add feature'`)
4. **Push** to branch (`git push origin feature/your-feature`)
5. Open a **Pull Request** against the `main` branch

**Guidelines:**
- 🔍 Check [existing issues](https://github.com/Aabhasmishra/Gemini-Web-Clone/issues) first
- 🐛 For bugs, include steps to reproduce (screenshots welcome)
- ✨ For features, explain the use case clearly
- 🔒 Never commit `config.js` or API keys
- 💻 Follow existing code style (ES6+, clean indentation)

For major changes, please open an issue to discuss first.
