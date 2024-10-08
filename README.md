# Blasta App

<p align="center">
  <img src="./onboarding-screenshoot.png" alt="Onboarding Screenshot" height="500" style="margin-right: 10px;"/>
  <img src="./qr-code-screenshoot.png" alt="QR Code Screenshot" height="500" style="margin-right: 10px;"/>
  <img src="./your-shop-screenshoot.png" alt="Your Shop Screenshot" height="500"/>
</p>

## Description

Blasta is a mobile application designed for customers to collect digital stamps and redeem rewards from various shops and businesses. It serves as the customer-facing component of the [Blasto](https://github.com/thchan1992/blasto) digital gift card system.

## Features

- **Digital Stamp Collection**: Users can display a QR code to collect stamps from participating businesses.
- **Reward Redemption**: Accumulated stamps can be redeemed for rewards directly through the app.
- **Multi-Shop Support**: View stamps and rewards from different shops all in one place.
- **Reward Tracking**: Keep track of available rewards from various shops.

## Technology Stack

- **Frontend**: Expo (React Native)
- **Authentication**: Clerk

## Installation

To set up the project locally, follow these steps:

1. Clone the repository

   ```
   git clone https://github.com/your-username/blasta-app.git
   cd blasta-app
   ```

2. Install dependencies

   ```
   npm install
   ```

3. Set up environment variables (create a `.env` file in the root directory)

   ```
   EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   ```

4. Start the Expo development server
   ```
   npx expo start
   ```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
MIT License is a permissive license that allows for reuse within proprietary software provided all copies of the licensed software include a copy of the MIT License terms and the copyright notice.

## Contact

For any inquiries or support, please contact Han at info@windyrecipe.com.
