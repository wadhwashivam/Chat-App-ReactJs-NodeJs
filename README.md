# Chat App with ReactJS and NodeJS

This repository contains a chat application built using ReactJS and NodeJS, utilizing the ChatEngine.io platform to provide real-time messaging capabilities. The application is designed for chat and communication between users and features a user-friendly interface created with the "react-chat-engine-pretty" package. Additionally, there's an alternative version using the "react-chat-engine-advanced" package for those who prefer a more advanced interface.

## Features

- Real-time chat functionality.
- User-friendly interface.
- Multiple chat rooms.
- Supports up to 10 users concurrently.
- Functional even after the 30-day trial period.
- Customizable with "react-chat-engine-pretty" or "react-chat-engine-advanced."

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/chat-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chat-app
   ```

3. Install the dependencies for the frontend and backend:

   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

4. Set up your ChatEngine.io account and get your API keys.

5. Configure the API keys in the `server/.env` file:

   ```plaintext
   CE_API_KEY=your_chatengine_api_key
   ```

6. Start the backend server:

   ```bash
   cd ../server
   npm start
   ```

7. Start the React frontend:

   ```bash
   cd ../client
   npm start
   ```

8. Visit [http://localhost:5173](http://localhost:5173) in your browser to access the chat application.

## Usage

- Register and log in to start using the chat application.
- Create chat rooms and invite users to join.
- Enjoy real-time communication with up to 10 users at a time.

## Frontend Customization

This repository provides two versions of the frontend interface for your convenience. Choose either "react-chat-engine-pretty" or "react-chat-engine-advanced" to customize the frontend design according to your preference.

- To switch to the "react-chat-engine-pretty" version, run:

  ```bash
  cd client
  npm uninstall react-chat-engine-advanced
  npm install react-chat-engine-pretty
  npm start
  ```

- To switch to the "react-chat-engine-advanced" version, run:

  ```bash
  cd client
  npm uninstall react-chat-engine-pretty
  npm install react-chat-engine-advanced
  npm start
  ```

## Limitations

Please note that this application uses free services from ChatEngine.io, which limits concurrent users to 10. Additionally, the free trial for ChatEngine.io lasts for 30 days, after which you may need to subscribe to their services or explore alternative options to continue using the app.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create a pull request or open an issue in this repository.

## Author

- [Shivam Wadhwa](https://github.com/wadhwashivam)

Feel free to contact me if you have any questions or need assistance with this project. Enjoy using the Chat App! 🚀
