**This repository has been archived, and no additional maintenance, development, bug fixes, or security fixes should be expected. No issues or pull requests will be addressed on this repository going forward. This repository remains visible for historical reference, but we do not support or recommend usage of the contents of this repository. If you fork this repository, please be mindful to respect the licensing and copyright attribution of its contents, as archiving the repository does not change the ownership or permissions of the contents.**

# Fullstack AppSync Events 4-in-a-Row
![gameplay](https://github.com/user-attachments/assets/6e0506c7-71d1-4586-b1ce-683e7401b828)

## Overview

Fullstack 4-in-a-Row is a real-time multiplayer game built using AWS Amplify, AWS AppSync Event API, and React. Challenge your friends to a classic connect four game with real-time updates and in-game chat functionality.

## Features

- 🎮 Real-time 4-in-a-Row gameplay
- 💬 In-game chat system
- 🔐 User authentication
- 🎟️ Game room creation and joining
- 📡 Powered by AWS AppSync Event API

## Tech Stack
![archoverview](https://github.com/user-attachments/assets/ef5fe379-4de6-4dd7-9ca8-74fb0f0312e8)

- **Frontend:** React (v0)
- **Backend:** AWS Amplify
- **Real-time Communication:** AWS AppSync Event API
- **Infrastructure:** AWS CDK

## Prerequisites

- Node.js (v18+)
- AWS Account
- AWS Amplify CLI
- npm or yarn

## Getting Started

### 1. Clone the Repository

### 2. Install Dependencies

```bash
npm install
```

### 3. Deploy Backend

```bash
npx ampx sandbox
```

## Game Mechanics
![intro-4](https://github.com/user-attachments/assets/f9b8d6ce-68c6-4872-9a66-cc04df4f256d)

1. Create a new game room
2. Share the room code with a friend
3. Take turns placing your colored discs
4. First player to connect four discs wins!

## Key Components

- 🏠 **Home Screen:** Create or join a game room
- 🎲 **Game Board:** Interactive 4-in-a-Row grid
- 💬 **Chat Interface:** Real-time messaging
- 👤 **User Management:** Authentication and profiles

**Note:** This project is a demonstration of AWS AppSync Event API capabilities and modern full-stack development practices.
## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

