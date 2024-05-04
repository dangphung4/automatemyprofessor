# Rate My Professor Bot

## Project Overview
The Rate My Professor Bot is a monorepo project consisting of two main components: a Python bot that generates fake reviews for professors using AI, and a React Vite application that serves as a user-friendly interface for interacting with the bot. The goal of this project is to provide an easy way for users to generate realistic fake reviews for professors.

## Features
- Python bot that generates fake reviews with varied descriptions and names to maintain authenticity
- React Vite application with a clean and modern user interface built using Material UI or Chakra UI
- User-friendly input form in the React application for users to provide prompts for generating fake reviews
- Integration between the React application and the Python bot via API endpoints
- Authentication mechanism to ensure only authorized users can access the service (SAAS model)
- Logging and monitoring to track bot activity and generated fake reviews
- Cloud-based deployment, with the Python bot hosted on AWS and the React application on Vercel

## Architecture
The project follows a monorepo structure with two main directories:
- `bot`: Contains the Python bot code responsible for generating fake reviews using AI techniques
- `webapp`: Contains the React Vite application code that serves as the user interface for interacting with the bot

The React application communicates with the Python bot through API endpoints to send user prompts and receive generated fake reviews.

## Prerequisites
- Python 3.11
- Node.js 18.0+ and npm
- AWS account for hosting the Python bot
- Vercel account for hosting the React application, will use react + vite

## Getting Started
1. Clone the repository: `git clone https://github.com/yourusername/rate-my-professor-bot.git`
2. Set up the Python bot:
   - Navigate to the `bot` directory: `cd bot`
   - Install the required Python dependencies: `pip install -r requirements.txt`
   - Configure the necessary AWS credentials and settings
3. Set up the React Vite application:
   - Navigate to the `webapp` directory: `cd webapp`
   - Install the required npm packages: `npm install`
   - Configure the necessary environment variables for the Vercel deployment
4. Start the development servers:
   - In the `bot` directory, run: `python app.py`
   - In the `webapp` directory, run: `npm run dev`
5. Access the application in your browser at `http://localhost:3000`

## Deployment
- Deploy the Python bot to AWS using the provided deployment scripts and instructions
- Deploy the React Vite application to Vercel using the provided deployment scripts and instructions

## Contributing
We welcome contributions to enhance the functionality and usability of the Rate My Professor Bot. To contribute, please follow the standard GitHub workflow:
1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make your changes and commit them with descriptive messages
4. Push your changes to your forked repository
5. Submit a pull request detailing your changes

## Issue Tracking
If you encounter any issues or have suggestions for improvements, please create a new issue in the GitHub repository. We have provided issue templates to help you provide the necessary information for efficient resolution.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any inquiries or further information, please contact the project maintainer at [email@example.com](mailto:email@example.com).

We hope you find the Rate My Professor Bot useful and enjoy using it to generate realistic fake reviews for professors!
