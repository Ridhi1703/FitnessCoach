Sure! Here's a detailed GitHub description for your project:

---

# Fitness Coach Chatbot

Welcome to the **Fitness Coach Chatbot**! This project aims to create a conversational AI chatbot to assist users with fitness-related questions and provide personalized workout routines and tips.

## Features

- **Interactive Chat Interface**: The chat interface mimics popular messaging apps, providing a smooth and familiar user experience.
- **Predefined Prompts**: Users can quickly ask common fitness questions using predefined prompts.
- **Generative AI Responses**: Leverages Google Generative AI to generate responses to user queries.
- **Loading Indicator**: Shows a loader while the AI generates a response.
- **Smart Scrolling**: Automatically scrolls to the latest prompt, ensuring users can easily follow the conversation.

## Tech Stack

- **React.js**: For building the user interface.
- **Tailwind CSS**: For styling the application.
- **Google Generative AI**: For generating responses to user queries.

## Installation

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/fitness-coach-chatbot.git
cd fitness-coach-chatbot
```

2. **Install Dependencies**

```bash
npm install
```

3. **Set Up Environment Variables**

Create a `.env` file in the root directory and add your Google Generative AI API key:

```env
REACT_APP_API_KEY=your_actual_api_key_here
```

4. **Start the Development Server**

```bash
npm start
```

## Usage

1. **Enter a Custom Prompt**: Type your question in the input field and press the send button.
2. **Use Predefined Prompts**: Click any predefined prompt to quickly ask common fitness questions.
3. **View Responses**: The bot will generate a response, which will appear below your prompt.

## Contributing

We welcome contributions to the Fitness Coach Chatbot! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Deployment

To deploy this project on Vercel:

1. **Install Vercel CLI**

```bash
npm install -g vercel
```

2. **Login to Vercel**

```bash
vercel login
```

3. **Deploy the Project**

```bash
vercel
```

Follow the prompts to link your project and deploy it. Vercel will handle the rest.

## Environment Variables in Vercel

Set up your environment variables in Vercel:

1. Go to your project dashboard on Vercel.
2. Navigate to the **Settings** tab.
3. Under the **Environment Variables** section, add `REACT_APP_API_KEY` with your actual API key.

## Links

- [Google Generative AI Documentation](https://developers.google.com/generative-ai)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please open an issue on GitHub or contact us at [vernekarriddhi246@gmail.com].

