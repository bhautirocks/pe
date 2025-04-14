# Engineering Joke Generator

This is a simple and fun web app that generates witty engineering jokes using the OpenRouter API and the `mistralai/mixtral-8x7b-instruct` model. You can choose between clean or 18+ jokes, select the joke length (short, medium, long), optionally describe the style or topic (e.g., sarcastic, punny, civil engineers, circuits, etc.), and even regenerate jokes instantly. All in a single HTML file using just HTML, CSS, and JavaScript.

## Setup Instructions

1. **Download or Clone**
   - Clone this repository using `git clone https://github.com/yourusername/engineering-joke-generator.git` OR just download the `index.html` file.

2. **Get API Key**
   - Go to [https://openrouter.ai/](https://openrouter.ai/)
   - Sign in and go to the API settings page to generate your API key.

3. **Insert API Key**
   - Open the `index.html` file in a code editor.
   - Find the line that says:
     ```javascript
     const API_KEY = 'YOUR_API_KEY_HERE';
     ```
   - Replace `'YOUR_API_KEY_HERE'` with your actual OpenRouter API key. It should look something like:
     ```javascript
     const API_KEY = 'sk-xxxxxxxxxxxxxxxxxxxx';
     ```

4. **Run It**
   - Open `index.html` in your browser. No server or setup required. Start laughing!

## Notes

- Make sure you don’t expose your real API key on a live/public website. In real-world deployments, you should use a secure server or environment variable to handle API requests.
- The model used (`mistralai/mixtral-8x7b-instruct`) is powerful and generates original, creative, and technical jokes when prompted with a clear structure.

## Example Prompts Sent to the API

The system prompt:
“You are a witty joke generator that focuses on engineering humor.”

And the user prompt is dynamically generated like:
“Create a medium clean engineering joke about electrical engineers. Make it witty, original, and funny. Add technical wordplay and a sarcastic tone.”

This design allows precise control over the joke’s content and style based on user input.

## Planned Features

- Copy joke to clipboard
- Social sharing
- Image meme generator
- Save favorite jokes
- Light/Dark mode

## License

MIT License – free to use, share, and remix. Contributions welcome!
