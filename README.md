# Flutter Tawk.io AI Assistant Chatbot Integration

Integrate a powerful AI-driven chatbot into your Flutter apps (mobile and web) using tawk.io. Enhance user engagement, automate support, and deliver personalized assistance seamlessly.

## Overview

This project demonstrates a proof-of-concept (POC) for integrating the tawk.io AI Assistant chatbot into your Flutter applications. By leveraging tawk.io's AI capabilities, you can:

 - Provide real-time chat support to your users
 - Automate responses to common queries
 - Offer personalized assistance with the AI Assistant
 - Streamline customer support and improve user experience
## Key Features

 - Seamless Integration: Easily embed the tawk.io chatbot into your Flutter app's UI.
 - Cross-Platform Support: Works flawlessly on both mobile (iOS, Android) and web platforms.
 - AI-Powered Chat: Leverage the AI Assistant for intelligent, automated conversations.
 - Customizable Chat Widget: Tailor the appearance of the chat widget to match your app's design.
 - Chat History & Management: Access chat history and manage conversations efficiently.

## Demo Videos

See the chatbot in action:

- Web:  <br />

<video src="https://github.com/vsc9729/tawk-poc/blob/2180cd7334dee0c8aed1e4e4008d3b18dca36ab5/readme%20files/Screen%20Recording%202024-07-26%20at%2011.20.15%E2%80%AFAM.mov?raw=true" height="500" width = "300"></video>

- Mobile:  <br />

<video src="https://github.com/vsc9729/tawk-poc/blob/2180cd7334dee0c8aed1e4e4008d3b18dca36ab5/readme%20files/screen-20240726-112938.mp4?raw=true"></video>


## Getting Started

### Prerequisites

 - Flutter project (mobile and/or web)
 - tawk.io account (free or paid)

### Tawk.io Setup

Follow the following steps to setup your tawk io chatbot: 

 1. Sign Up: Create a tawk.io account at https://www.tawk.io.
 2. AI Assistant:
    - Set up the AI Assistant with custom prompts and responses.
    - Optionally: Train the AI using a CSV file with prompts and responses. (See example: Fashion Shop Consultant Dataset)
 3. Dashboard: Access your tawk.io dashboard.
 4. Channels: Navigate to the "Channels" section > "Chat Widget." You'll find your:
    - Direct Chat Link: Used for mobile integration.
    - Widget Code: Used for web integration.
![Tawk.io Dashboard Screenshot](https://github.com/vsc9729/tawk-poc/blob/2180cd7334dee0c8aed1e4e4008d3b18dca36ab5/readme%20files/Screenshot%202024-07-23%20at%201.34.05%E2%80%AFPM.png)

### Flutter Integration

Follow the following steps to add the chatbot to flutter: 

#### Flutter Web

1. Enable Flutter Web: Ensure your project supports web compilation.
2. Index.html: Open web/index.html.
3. Paste Widget Code: Insert the Widget Code from tawk.io before the opening body tag.
![Tawk.io Widget Code in index.html](https://github.com/vsc9729/tawk-poc/blob/2180cd7334dee0c8aed1e4e4008d3b18dca36ab5/readme%20files/Screenshot%202024-07-26%20at%2010.30.59%E2%80%AFAM.png)

#### Flutter Mobile
1. Add Dependency: Include webview_flutter in your pubspec.yaml.
2. WebView Controller: Create a WebViewController using your tawk.io Direct Chat Link.
3. Display Chat:
 - Use a WebView widget to display the chat (e.g., in a bottom modal sheet).
 - Trigger the chat with a Floating Action Button.
![Flutter Mobile Chat Implementation](https://github.com/vsc9729/tawk-poc/blob/2180cd7334dee0c8aed1e4e4008d3b18dca36ab5/readme%20files/Screenshot%202024-07-26%20at%2010.53.49%E2%80%AFAM.png)
![Flutter Mobile Chat Implementation](https://github.com/vsc9729/tawk-poc/blob/2180cd7334dee0c8aed1e4e4008d3b18dca36ab5/readme%20files/Screenshot%202024-07-26%20at%2010.54.38%E2%80%AFAM.png)

## Additional Notes
- Customization: Explore tawk.io's documentation to customize the chat widget further.
- Troubleshooting: If you encounter issues, check the tawk.io help center or Flutter community forums.

Let me know if you have any other questions or would like further refinements to the README!
