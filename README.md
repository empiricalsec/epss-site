<div align="lef">
  <img src="https://empiricalsec.github.io/epss-site/epss-logo.svg" alt="EPSS Logo" width="400">
</div>

# EPSS Insiders

## Prerequisites

### Install Node.js

Using Homebrew:

```bash
brew install node
```

Verify the installation:

```bash
node --version
npm --version
```

### Install Yarn

If using Corepack (recommended):

```bash
corepack enable
```

Or install Yarn directly with Homebrew:

```bash
brew install yarn
```

Verify the installation:

```bash
yarn --version
```

## Getting Started

1. Clone the repository and navigate to the project directory:

```bash
cd epss-site
```

2. Install dependencies:

```bash
yarn install
```

3. Start the development server:

```bash
yarn start
```

4. Open your browser and navigate to:

```
http://localhost:1234
```

## Commands

### Start Development Server

```bash
yarn start
```

Starts the Parcel development server at `localhost:1234`.

### Build for Production

```bash
yarn build
```

Creates a production build in the `production/` directory.

Before building, the existing `dist/` and `production/` directories are removed to ensure a clean build.

## Troubleshooting

If dependencies become corrupted or out of sync:

```bash
rm -rf node_modules
yarn install
```

Then restart the development server:

```bash
yarn start
```

## Tech Stack

* Node.js
* Yarn
* Parcel 2
* Sass
