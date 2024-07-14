![Screenshot 2024-07-14 184614](https://github.com/user-attachments/assets/b21e5a2c-d564-4348-8f47-19297c2f1866)

# Google Generative AI

This project is a web application based on user prompts using Google's Generative AI. The application utilizes Node.js, Express, and EJS for templating.

## Features
- User-friendly interface to input prompts
- Generates using Google Generative AI
- Simple and responsive design

## Prerequisites
- Node.js installed
- npm (Node Package Manager) installed
- Google Generative AI API Key

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashishalf/google-gen-ai
   cd google-gen-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root of your project and add your Google Generative AI API key:
   ```
   API_KEY=your-google-generative-ai-api-key
   ```

## Usage

1. Start the server:
   ```bash
   node server.js
   ```

2. Open your browser and go to `http://localhost:3000`.

3. Enter a prompt in the input field and click "Generate" to get a generated story based on your prompt.

## Project Structure

```
project-root/
│
├── views/
│   ├── index.ejs
│   └── layout.ejs
│
├── public/
│   ├── styles.css
│
├── .env
├── server.js
└── package.json
```

## Links

- [NPM: @google/generative-ai](https://www.npmjs.com/package/@google/generative-ai)
- [Google AI Documentation: Getting Started with Gemini API](https://ai.google.dev/gemini-api/docs/get-started/tutorial?lang=node)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
