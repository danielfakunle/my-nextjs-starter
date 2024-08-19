<div align="center">
  <img src="public/logo.svg" alt="logo" width="200" height="auto" />
  <h1>My Next.js Starter</h1>
  <p>A simple Next.js boilerplate.</p>
  <!-- Badges -->
  <p>
    <a href="https://github.com/danielfakunle/my-nextjs-starter/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/danielfakunle/my-nextjs-starter.svg?style=for-the-badge" alt="contributors" />
    </a>
    <a href="">
      <img src="https://img.shields.io/github/last-commit/danielfakunle/my-nextjs-starter.svg?style=for-the-badge" alt="last update" />
    </a>
    </a>
    <a href="hhttps://github.com/danielfakunle/my-nextjs-starter/issues/">
      <img src="https://img.shields.io/github/issues/danielfakunle/my-nextjs-starter.svg?style=for-the-badge" alt="open issues" />
    </a>
    <a href="https://github.com/danielfakunle/my-nextjs-starter/blob/master/LICENSE">
      <img src="https://img.shields.io/github/license/danielfakunle/my-nextjs-starter.svg?style=for-the-badge" alt="license" />
    </a>
  </p>
</div>

## About the Project

DISCLAIMER: This project is intended for personal use.

Welcome to `my-nextjs-starter`! This repository contains a boilerplate setup for a Next.js project. It's designed to help you kickstart your Next.js project with a clean and organized structure.

## Features

- **Next.js**: A powerful React framework for building fast and user-friendly applications.
- **Theming**: Easily switch between different themes using a centralized theme provider.
- **Folder Structure**: Organized folder structure for components, pages, and styles.

## Getting Started

Follow these steps to get started with `my-nextjs-starter`:

### Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/danielfakunle/my-nextjs-starter.git
```

### Install Dependencies

Navigate to the project directory and install the required dependencies:

```bash
cd my-nextjs-starter
pnpm install
```

The project forces pnpm. To disabled that, remove the following line from the package.json file:

```json
{
  //...
  "scripts": {
    //...
    "preinstall": "npx only-allow pnpm" // remove this line
  }
  //...
}
```

### Start the Development Server

Start the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see your application.

## Folder Structure

The project structure is organized as follows:

```
my-nextjs-starter/
├── public/             # Static files like images, icons, etc.
├── src/
│   ├── app/            # Next.js pages
│   ├── components/     # Reusable components
│   ├── lib/            # Utility functions and helpers
│   ├── providers/      # Providers
│   ├── styles/         # Global styles and theme configurations
│   ├── utils/
│   ├── theme/          # Theme provider and theme files
│   └── ...
├── next.config.js      # Next.js configuration
├── package.json        # Project metadata and dependencies
└── README.md           # Project documentation
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Shadcn](https://ui.shadcn.com/)

---

Happy coding!

```
Feel free to modify the content according to your specific setup and requirements.
```
