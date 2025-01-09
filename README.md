# React + TypeScript + Vite - Chrome Browser Extension

This repository contains the essential setup to create a Chrome browser extension using React, TypeScript, and Vite.

## Development Setup

### Prerequisites

- [pnpm](https://pnpm.io/installation)
- [Node.js](https://nodejs.org/)

### Getting Started

Ensure that Node.js and pnpm are installed on your system.

1. Clone this repository:

```sh
git clone <repository-url>
```

2. Navigate to the root folder:

```sh
cd chrome-extension-starter
```

3. Install the dependencies:

```sh
pnpm install
```

You are now ready to start developing your Chrome extension.

### Running Locally

To run the extension locally in a browser, execute:

```sh
pnpm run dev
```

### Building the Extension

To build the extension, execute:

```sh
pnpm run build
```

The build output will be located in the `dist` folder.

## Loading the Extension in Chrome

1. Open Chrome and navigate to `chrome://extensions`.
2. Enable **Developer mode**.
3. Click **Load unpacked** and select the `dist` folder.

Your extension should now be loaded and ready for testing.
