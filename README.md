Gemini Clone

Gemini Clone is a React.js-based web application that simulates a conversational AI experience. It leverages Google's Generative AI to provide users with dynamic responses to their prompts. The project features a sidebar for navigation and a main content area for interaction with the AI.

Features

Sidebar Navigation: Allows users to access recent prompts, start a new chat, and navigate to other sections like Help, Activity, and Settings.

Main Chat Interface: Users can input prompts and receive AI-generated responses.

Dynamic Response Rendering: Displays responses with a typing effect and supports formatted text.

Responsive Design: Ensures compatibility with different screen sizes.

Components

1. App

The root component that renders the Sidebar and Main components.

2. Sidebar

Manages navigation and displays recent prompts. Features include:

Toggling between compact and extended views.

Loading and displaying recent prompts.

Navigating to Help, Activity, and Settings.

3. Main

Handles user interactions with the AI, including:

Displaying greetings and prompt suggestions.

Showing AI responses with a typing effect.

Providing an input box for user prompts.

4. ContextProvider

Provides global state management for the application using React's Context API. Manages state for:

Previous prompts.

Current input and response data.

Loading states and result display toggles.

5. runChat

A utility function that interacts with Google's Generative AI API to fetch responses for user prompts.

Installation

Clone the repository:

git clone https://github.com/yourusername/gemini-clone.git

Navigate to the project directory:

cd gemini-clone

Install dependencies:

npm install

Start the development server:

npm run dev

Usage

Open the application in your web browser.

Use the sidebar to navigate and manage chats.

Enter prompts in the main chat interface to interact with the AI.

Configuration

Replace the placeholder API key in runChat.js with your Google Generative AI API key.

Technologies Used

React.js

Vite

Google Generative AI

CSS for styling

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

Google Generative AI for providing the AI model.

Inspired by conversational AI interfaces.

Contact

For questions or support, please contact Vishal at [your email].

