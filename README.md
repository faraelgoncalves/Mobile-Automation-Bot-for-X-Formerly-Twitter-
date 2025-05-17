# Mobile Automation Bot for X (Formerly Twitter) 🤖

![GitHub release](https://img.shields.io/github/release/faraelgoncalves/Mobile-Automation-Bot-for-X-Formerly-Twitter-/latest.svg?style=flat-square)

Welcome to the **Mobile Automation Bot for X** repository! This project enables automation on the X platform (formerly known as Twitter) using gesture-based interactions. With support for multiple accounts, proxy and SIM rotation, and cloud-driven scheduling, this bot operates seamlessly on real Android and iOS devices.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Gesture-Based Interactions**: Automate actions like tweeting, liking, and retweeting using simple gestures.
- **Multi-Account Support**: Manage multiple accounts easily without logging in and out.
- **Proxy/SIM Rotation**: Use different proxies and SIM cards for each session to enhance security and avoid bans.
- **Cloud-Driven Scheduling**: Schedule tasks to run at specific times using a cloud service.
- **Real Device Automation**: Run the bot on actual Android and iOS devices for better reliability.

## Technologies Used

- **Android Automation**: Utilize Appium for Android device automation.
- **iOS Automation**: Use Appium for iOS device automation.
- **Cloud Services**: Leverage cloud platforms for scheduling and execution.
- **Proxy Management**: Implement proxy handling for secure connections.
- **Multi-Account Management**: Facilitate easy switching between different user accounts.

## Installation

To get started, download the latest release of the Mobile Automation Bot from the [Releases section](https://github.com/faraelgoncalves/Mobile-Automation-Bot-for-X-Formerly-Twitter-/releases). You need to execute the downloaded file to set up the bot on your device.

### Prerequisites

- **Node.js**: Ensure you have Node.js installed on your system.
- **Appium**: Install Appium for mobile automation.
- **Android Studio**: For Android device automation.
- **Xcode**: For iOS device automation.

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/faraelgoncalves/Mobile-Automation-Bot-for-X-Formerly-Twitter-.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd Mobile-Automation-Bot-for-X-Formerly-Twitter-
   ```

3. Install the necessary dependencies:
   ```bash
   npm install
   ```

4. Follow the setup instructions specific to Android or iOS.

## Usage

After installation, you can start using the bot. Below are some basic commands to get you started.

### Starting the Bot

To start the bot, use the following command:
```bash
node bot.js
```

### Basic Commands

- **Tweet**: Send a tweet using:
  ```bash
  node bot.js tweet "Your message here"
  ```

- **Like a Tweet**: Like a specific tweet:
  ```bash
  node bot.js like tweetID
  ```

- **Retweet**: Retweet a specific tweet:
  ```bash
  node bot.js retweet tweetID
  ```

### Scheduling Tasks

To schedule a task, use the following command:
```bash
node bot.js schedule "task" "time"
```

## Configuration

You can customize the bot's behavior by editing the `config.json` file. Here are some settings you can modify:

- **accounts**: Add your multiple X accounts.
- **proxies**: Set up proxies for rotation.
- **schedule**: Define the tasks and their timings.

### Example Configuration

```json
{
  "accounts": [
    {
      "username": "user1",
      "password": "password1"
    },
    {
      "username": "user2",
      "password": "password2"
    }
  ],
  "proxies": [
    "proxy1:port",
    "proxy2:port"
  ],
  "schedule": [
    {
      "task": "tweet",
      "time": "10:00"
    }
  ]
}
```

## Contributing

We welcome contributions! If you want to improve the bot or add new features, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please open an issue in this repository or contact me directly.

Feel free to explore the [Releases section](https://github.com/faraelgoncalves/Mobile-Automation-Bot-for-X-Formerly-Twitter-/releases) for the latest updates and versions. 

---

Thank you for checking out the Mobile Automation Bot for X! Your feedback and contributions are greatly appreciated.