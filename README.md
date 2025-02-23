# NLW Return Impulse Mobile

This repository contains the mobile application developed during the **NLW Return Impulse** event by Rocketseat. The project focuses on building a modern and interactive mobile app using React Native and Expo.

## Technologies Used
- **React Native** - Framework for building native mobile applications
- **Expo** - Platform for developing, building, and deploying React Native apps
- **TypeScript** - Strongly typed JavaScript for better development experience
- **Tailwind CSS** - Utility-first CSS framework for styling
- **Axios** - HTTP client for API requests
- **React Navigation** - Navigation library for handling screens and routes

## Project Structure
The project follows a modular and scalable architecture.

```plaintext
/nlw-return-impulse-mobile
│   README.md
│   package.json
│   .gitignore
│
├───src
│   ├───components
│   ├───screens
│   ├───services
│   ├───hooks
│   ├───assets
│   └───...
│
└───tests
    ├───components
    ├───screens
    └───...
```

## Setup and Execution

### Prerequisites
- Node.js (latest LTS version recommended)
- Expo CLI installed globally
- Android Emulator or iOS Simulator (or a physical device)

### Running the Application
1. Clone the repository:
   ```sh
   git clone https://github.com/victorfg21/nlw-return-impulse-mobile.git
   cd nlw-return-impulse-mobile
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the Expo development server:
   ```sh
   npm run start
   ```
4. Scan the QR code with the Expo Go app (on Android/iOS) or run on an emulator:
   ```sh
   npm run android  # For Android emulator
   npm run ios      # For iOS simulator (Mac only)
   ```

## Running Tests
To execute unit tests, use:
```sh
npm test
```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License
This project is licensed under the MIT License. For more details, refer to the `LICENSE` file.
