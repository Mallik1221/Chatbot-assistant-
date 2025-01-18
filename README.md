# ChatBot.React

An AI-powered chatbot built with React JS and CSS, utilizing the free Google Gemini API for dynamic and intelligent responses. This project demonstrates how to integrate a third-party API with React to create an interactive user experience.

---

## Features
- **Dynamic Responses**: Uses Google Gemini API for AI-driven interactions.
- **Modern Design**: Styled with CSS for a clean and responsive user interface.
- **React Hooks**: Utilizes React hooks for state and effect management.
- **API Integration**: Demonstrates how to make API calls to a third-party service in React.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ChatBot.React.git
   cd ChatBot.React
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Google Gemini API key:
   ```env
   REACT_APP_GEMINI_API_KEY=your_api_key_here
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`.

---

## Project Structure

```
ChatBot.React/
├── public/
├── src/
│   ├── components/
│   │   ├── ChatBox.js
│   │   ├── Message.js
│   │   └── Loader.js
│   ├── styles/
│   │   ├── App.css
│   │   └── ChatBox.css
│   ├── App.js
│   ├── index.js
│   └── utils/
│       └── api.js
├── .env
├── package.json
└── README.md
```

---

## How It Works

1. **User Interface**: The `ChatBox` component renders the chat interface, including the message input and display area.

2. **API Integration**: The `api.js` file contains functions to interact with the Google Gemini API, sending user inputs and receiving AI-generated responses.

3. **State Management**: React hooks are used to manage the state of messages and loading indicators.

4. **Styling**: Custom CSS ensures a responsive and visually appealing layout.

---

## Scripts

- **Start**: Launch the development server.
  ```bash
  npm start
  ```
- **Build**: Create a production build.
  ```bash
  npm run build
  ```
- **Test**: Run tests.
  ```bash
  npm test
  ```

---

## Dependencies

- [React](https://reactjs.org/)
- [Axios](https://axios-http.com/) (for API requests)
- [Google Gemini API](https://developers.google.com/gemini)

---

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Thanks to Google for providing the Gemini API.
- Inspired by modern chatbot designs and AI integration techniques.

---

## Contact

For any inquiries or feedback, please contact:

- **Name**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [your-username](https://github.com/your-username)
