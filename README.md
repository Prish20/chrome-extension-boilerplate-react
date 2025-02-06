# Chrome Extension Boilerplate with React

A boilerplate for developing Chrome extensions using React, TypeScript, and Webpack.

## Features

- **React 19** for UI components
- **TypeScript** for type safety
- **Webpack 5** for bundling
- **Hot Module Replacement (HMR)** for faster development
- **Manifest v3** compatibility
- **Linting and Formatting** with ESLint and Prettier
- **Modular structure** for easier maintenance

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 16+ recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Prish20/chrome-extension-boilerplate-react.git
   cd chrome-extension-boilerplate-react

   ```

2. Install dependencies:

   ```sh
   npm install
   ```

### Development Mode

To start the development server:

```sh
npm start

```

This enables Hot Module Replacement (HMR) for non-background scripts.

### Build for Production

To build the extension for production:

```sh
npm run build
```

The output will be in the `build/` directory.

### Load the Extension in Chrome

1. Open **chrome://extensions/** in Chrome.
2. Enable **Developer mode** (toggle in the top right corner).
3. Click **Load unpacked** and select the `build/` folder.
4. The extension is now installed and ready to use.

## Project Structure

```none
prish20-chrome-extension-boilerplate-react/
├── src/
│   ├── pages/
│   │   ├── Background/
│   │   ├── Content/
│   │   ├── Devtools/
│   │   ├── Newtab/
│   │   ├── Options/
│   │   ├── Panel/
│   │   └── Popup/
│   ├── containers/
│   ├── assets/
│   ├── utils/
│   ├── manifest.json
├── package.json
├── webpack.config.js
├── tsconfig.json
├── .eslintrc
├── .prettierrc
└── README.md
```

## Scripts

- `npm start` - Starts the development server
- `npm run build` - Builds the extension for production
- `npm run prettier` - Formats the code with Prettier

## Contribution

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make changes and commit (`git commit -m "Added new feature"`)
4. Push to your branch (`git push origin feature-branch`)
5. Submit a pull request

## License

This project is licensed under the [MIT License](LICENSE).
