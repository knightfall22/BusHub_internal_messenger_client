# BusHub Internal Messaging Application

This is a React-based internal messaging application built using the GetStream API. The application provides several features for seamless communication within an organization, including channel creation, joining channels, searching for channels, direct messaging, posting and reacting to messages, as well as support for sharing images and GIFs in chats.

## Prerequisites

To run this application locally, you need to have the following installed on your machine:

- Node.js (version 12 or above)
- NPM (Node Package Manager) or Yarn

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/knightfall22/BusHub_internal_messenger_client.git
   ```

2. Navigate to the project directory:

   ```bash
   cd BusHub_internal_messenger_client
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

4. Configure GetStream API credentials:

   - Obtain your API credentials (API key, secret, and app ID) from the GetStream website: [https://getstream.io](https://getstream.io).


5. Start the application:

   ```bash
   npm start
   ```

   or

   ```bash
   yarn start
   ```

6. Open your browser and visit `http://localhost:3000` to view the application.

## Features

### Channel Management

- Create Channels: Users can create channels for different teams, projects, or topics to facilitate group communication.

- Join Channels: Users can join existing channels to participate in discussions relevant to their work or interests.

- Search Channels: Users can search for channels based on keywords to discover relevant conversations.

### Messaging

- Direct Messaging: Users can send direct messages to other users for one-on-one communication.

- Post Messages: Users can compose and send messages in channels or direct conversations.

- React to Messages: Users can react to messages using emojis to express their sentiments.

### Media Support

- Image Support: Users can share images by uploading them in chats.

- GIF Support: Users can share animated GIFs in chats for more engaging conversations.

## Technologies Used

- React: A JavaScript library for building user interfaces.

- GetStream: A scalable and reliable API for building chat and messaging applications.

- Axios: A library for making HTTP requests.

- Styled Components: A CSS-in-JS library for styling React components.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code as per the terms of the license.
