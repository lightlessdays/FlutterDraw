# FlutterDraw: Convert your Drawings into Flutter Apps 💗

<img src="flutterdrawbanner.png" width=100%>

Welcome to FlutterDraw, an innovative application powered by the GPT Vision 4 API. This unique tool empowers users to sketch and design their Flutter applications on an online whiteboard and seamlessly convert these sketches into fully functional Flutter code with just one click.

## Index 🥳

1. [Features](https://github.com/lightlessdays/FlutterDraw?tab=readme-ov-file#features)
2. [Requirements](https://github.com/lightlessdays/FlutterDraw?tab=readme-ov-file#requirements)
3. [Getting Started](https://github.com/lightlessdays/FlutterDraw?tab=readme-ov-file#getting-started)
4. [Demonstration](https://github.com/lightlessdays/FlutterDraw?tab=readme-ov-file#demonstration)
5. [API Key](https://github.com/lightlessdays/FlutterDraw?tab=readme-ov-file#api-key)
6. [Community](https://github.com/lightlessdays/FlutterDraw?tab=readme-ov-file#community)
7. [Inspiration](https://github.com/lightlessdays/FlutterDraw?tab=readme-ov-file#drawing-to-html--css)

## Features 🔮

- **Interactive Whiteboard:** Utilize an intuitive online whiteboard interface to sketch and draw your Flutter application layout and design.
- **GPT Vision 4 Integration:** Leverage the power of the GPT Vision 4 API for intelligent recognition and interpretation of your sketches.
- **One-Click Conversion:** Instantly convert your sketches into complete, runnable Flutter code with a single click.
- **Customization Options:** Fine-tune your designs and add specifications before conversion, including widget properties, layout configurations, and more.
- **Preview and Download:** Review a preview of your generated Flutter app and easily download the code for immediate use.

## Requirements ✨

- Compatible web browser (Chrome, Firefox, Safari, etc.)
- Internet connectivity
- GPT-4 Vision Access Key

## Getting Started ✅

Before getting started, make sure you have a version of Node.JS greater than 18.17 installed in your system. You can install Node.JS by [clicking here](https://nodejs.org/en/download). You can learn about Node.JS from [here](https://blog.dhruvbadaya.in/what-the-fck-is-nodejs-a-complete-tutorial).

To get started, follow the given steps:

- **Step 1:** Download the code for the repository by [clicking here](https://github.com/lightlessdays/FlutterDraw/archive/refs/tags/v1.zip).
- **Step 2:** Unzip the downloaded folder and open the folder in Visual Studio Code (or your favorite terminal).
- **Step 3:** Get your OPENAI GPT-4 Access Key and copy the following command:
  ```
  echo OPENAI_API_KEY=sk-your-key > .env.local
  ```
  Make sure to replace sk-your-key with your OPENAI key.
  This will create a new file called `$.env.local` in your folder.
- Once the command runs, enter the following command:
  ```
  npm install
  ```
  This command will install all the required NPM Packages for FlutterDraw.
- Lastly, run the following command:
  ```
  npm run dev
  ```
  This will start the FlutterDraw server. Once the server starts, go to your favorite browser and type in the URL `https://localhost:3000` or [click here](https://localhost:3000). This will take you to the FlutterDraw whiteboard, where you can start drawing.

## Demonstration 🎥

<img src="demonstration.gif">

## API Key 🔑

To utilize the full functionality of FlutterDraw, ensure that you have obtained a valid API key for the GPT Vision 4 API. You can acquire an API key by signing up on the GPT Vision 4 platform and following the provided instructions.

## Community 🫂

We welcome contributions from the community! Please refer to the following files before Contributing:
- [CONTRIBUTING GUIDELINES](https://github.com/lightlessdays/FlutterDraw/blob/main/CONTRIBUTING_GUIDELINES.md)
- [CODE OF CONDUCT](https://github.com/lightlessdays/FlutterDraw/blob/main/CODE_OF_CONDUCT.md)

## Inspiration 😎

This project has been inspired from, and several components of the code and UI have been derived from the original project by Sawyer Hood that translated wireframes into HTML & CSS. If you want to convert your drawings into HTML & CSS, instead of Flutter, check out this repository: [https://github.com/SawyerHood/draw-a-ui](https://github.com/SawyerHood/draw-a-ui)https://github.com/SawyerHood/draw-a-ui
