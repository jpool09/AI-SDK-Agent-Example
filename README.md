# Example of AI Agents with Next.js and Vercel AI SDK

This repository contains a simple example of **AI Agents** developed with **Next.js** and the **AI SDK by Vercel**. The project demonstrates how to integrate OpenAI language models (such as GPT-3.5 or GPT-4) into a web application to create conversational assistants.

<br>

## Features

- **Integration with OpenAI:** Uses the OpenAI API to generate real-time responses.
- **Usage of Vercel AI SDK:** Implements streaming responses and custom tools.
- **Example Tools:** Includes functionalities to get weather data and convert temperatures.
- **Development with Next.js:** A project based on Next.js, optimized for deployment on Vercel.

<br>

## Requirements

- **Node.js:** Version 14 or higher.
- **npm** or **yarn**.
- An account on [OpenAI](https://platform.openai.com) and an API Key.
- *(Optional)* An account on [Vercel](https://vercel.com) for deployment.

<br>

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. **Install the dependencies:**

   ```bash
    npm install
    # or, if you prefer yarn:
    yarn install
   
3. **Configure the environment variables:**

    Create a file named .env.local in the root of the project and add your OpenAI API Key:
   ```bash
   OPENAI_API_KEY=your_api_key_here

<br>

## Usage

  Start the development server:
  ```bash
  npm run dev
  # or
  yarn dev
  ```

Access the application:
Open your browser and visit http://localhost:3000 to interact with the AI Agent.

<br>

## Deployment

This project is optimized for deployment on Vercel. To deploy it:

- Upload the repository to GitHub.
- Connect your repository to Vercel through the dashboard.
- Configure the **OPENAI_API_KEY** environment variable in the Vercel settings panel.
- Deploy the application following Vercel's instructions.

<br>

## Contributions

Contributions are welcome! If you wish to improve this project:

1. Fork the repository.
2. Create a branch for your new feature or bug fix.
3. Submit a pull request describing the changes made.

<br>

## License

This project is distributed under the MIT License.

<br>

## Contact

If you have questions or suggestions, feel free to open an issue on GitHub or contact **cruzonchain@gmail.com**.
