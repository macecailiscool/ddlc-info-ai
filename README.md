# DDLC AI

The DDLC AI is an artificial intelligence-powered chatbot specifically designed to answer questions related to the game "Doki Doki Literature Club" (DDLC). It utilizes a pre-built database containing information about the characters, storyline, development, music, and other aspects of DDLC.

## Features

- Provides answers to a wide range of questions related to DDLC.
- Covers various topics, including characters, storyline, development, and music.
- Offers accurate and detailed responses based on the embedded database.
- User-friendly interface for interacting with the AI.

## Usage

To use the DDLC AI, follow these steps:

1. Clone the repository or download the source code to your local machine.
2. Open the `index.html` file in a web browser.
3. Type your DDLC-related question in the input field provided.
4. Click the "Ask" button to submit your question.
5. The AI will generate a response based on the embedded database and display it on the page.

## Customization

If you want to expand the DDLC AI's knowledge base or add more questions and answers, you can modify the embedded XML data in the JavaScript code. Locate the `xmlData` variable within the `<script>` tag in the HTML file. You can add additional categories, entries, questions, and answers to cover additional topics related to DDLC.

```javascript
// XML data embedded in the JavaScript code
var xmlData = `<?xml version="1.0" encoding="UTF-8"?>
  <database title="DDLC AI Database">
    <!-- Add more categories, entries, questions, and answers here -->
  </database>`;
```

## Contributions

Contributions to the DDLC AI project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue on the project's GitHub repository. You can also submit pull requests with improvements or additions to the codebase.

## License

The DDLC AI project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code according to the terms of the license.

## Disclaimer

The DDLC AI is an unofficial project and is not affiliated with Team Salvato, the developers of Doki Doki Literature Club. The AI's responses are based on the information provided in the embedded database and may not always reflect the official or complete knowledge of the game.

## Credits

The DDLC AI project was created by Mace Cail and is based on an XML AI database.

## Acknowledgments

Special thanks to Team Salvato for developing Doki Doki Literature Club and providing a memorable and unique gaming experience.
