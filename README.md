# Text Summarizer with Gemini API

This project is a _Text Summarizer_ application that takes a user-provided paragraph and generates a concise summary using the _Gemini API. It features a modern, interactive user interface built with \*\*React.js_ and a secure backend powered by _Node.js_. The design incorporates elements from [UIverse.io](https://uiverse.io).

---

## Features

- _Interactive User Interface_: Built with React.js and styled using UIverse.io components.
- _Accurate Summarization_: Utilizes the Gemini API for precise and concise text summarization.
- _Real-Time Results_: Submit a paragraph and instantly receive a summarized version.
- _Responsive Design_: Optimized for desktops, tablets, and mobile devices.
- _Secure Backend Integration_: Node.js backend handles API requests securely.

---

## Technologies Used

### Frontend:

- _React.js_ for building the user interface.
- _CSS3_ for styling.
- _UI Components_ from [UIverse.io](https://uiverse.io).

### Backend:

- _Node.js_ with Express for API handling.
- _Dotenv_ for managing environment variables.

### API:

- _Gemini API_ for performing text summarization.

---

## Prerequisites

Ensure you have the following installed:

- _Node.js_ (v14+)
- _npm_ or _yarn_
- Gemini API key

---

## Installation and Setup

Follow these steps to set up the project:

### 1. Clone the Repository

```bash
git clone https://github.com/DenzilSerrao/Summarisation-using-Gemini-API.git
cd Summarisation-using-Gemini-API
```

### 2. Backend Setup (Node.js)

Navigate to the backend folder:

```bash

cd server
```

#### 3.Install dependencies:

```bash

npm install
```

#### 4. Create a .env file in the server directory and add your Gemini API key:

```bash env
API_KEY=your_api_key_here
```

#### 5. Start the backend server:

```bash

npm start
```

The backend server will run on http://localhost:5000.

### Frontend Setup (React.js)

Navigate to the frontend folder:

```bash

cd ../client
```

#### 3.Install dependencies:

```bash

npm install
```

### Start the React development server:

#### 3.Install dependencies:

```bash

npm start
```

The frontend will run on http://localhost:3000.

## Usage

Start both the backend server (server) and the React frontend (client).
Open your browser and go to http://localhost:3000.
Enter a paragraph in the input field provided.
Click the "Summarize" button.
View the summarized text displayed below the input area.

## Acknowledgments

#### Gemini API: For providing advanced text summarization capabilities.

#### UIverse.io: For inspiring UI components.

#### The React.js and Node.js communities for their fantastic tools and resources.
