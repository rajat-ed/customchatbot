## Custom Chatbot Template

A simple, customizable chatbot template built with HTML, CSS, and JavaScript, powered by the Gemini API. This project provides a foundation for creating your own AI-driven chatbot with a modern interface, conversation history, and a typing animation for a polished user experience.

## Features

- **Gemini API Integration**: Uses Google's Gemini 1.5 Flash model for smart, context-aware responses.
- **Plain Text Context**: Loads context from a `context.txt` file to customize the chatbot’s knowledge base.
- **Typing Animation**: Responses appear with a smooth, character-by-character typing effect.
- **Modern UI**: Wide, ChatGPT-like design with a sidebar logo and top-centered title.
- **Conversation History**: Tracks chat history for coherent interactions.
- **Easy to Customize**: Adjust context, styling, or API settings with minimal effort.

## Project Structure

```
/customchatbot
│── index.html          # Main chatbot interface
│── style.css           # Styling for the chatbot UI
│── script.js           # Core chatbot logic
│── context.txt         # Custom knowledge base for chatbot
│── assets/
│   ├── logo.png        # Chatbot logo (optional)
└── README.md           # Project documentation
```

## Setup & Usage

### Prerequisites
- A Google API key with access to the Gemini API.
- A web browser to run the chatbot locally.

### Steps to Run
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/rajat-ed/customchatbot.git
   cd customchatbot
   ```
2. **Customize Context (Optional):**
   - Edit `context.txt` to add custom knowledge.

3. **Run Locally:**
   - Open `index.html` in a web browser.

## Customization

### Modifying the UI
- Edit `style.css` to change colors, fonts, and layout.

### Adjusting Chat Behavior
- Modify `script.js` to customize how the chatbot handles responses.

### Enhancing the Knowledge Base
- Update `context.txt` with domain-specific information.

## Contributing
Feel free to fork this repository and submit pull requests with improvements!

## Credits
Creator: Rajat Thapa
Built With: HTML, CSS, JavaScript, Gemini API

## License
This project is licensed under the MIT License.
