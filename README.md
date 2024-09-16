Here’s an all-in-one README file for your Vite project, including the instructions for running both the Vite server and the JSON server:

````markdown
# Vite Project with JSON Server

This project uses Vite as the frontend build tool and a JSON server to simulate a backend database.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- npm (included with Node.js)

## Installation and Setup

1. **Clone the repository** and navigate into the project folder.

```bash
git clone <repository-url>
cd <project-folder>
```
````

2. **Install dependencies** using npm.

```bash
npm install
```

## Running the Application

### 1. Start Vite Development Server

To run the Vite development server, execute:

```bash
npm run dev
```

The app will be available at [http://localhost:5173](http://localhost:5173).

### 2. Start JSON Server

In a **separate terminal**, use the following command to start the JSON server:

```bash
npm run server
```

The JSON server will be available at [http://localhost:9000](http://localhost:9000).

Ensure that your `db.json` file is configured correctly to serve data.

## Building for Production

To create a production build of the project:

```bash
npm run build
```

The build files will be placed in the `dist` folder, ready for deployment.

## License

This project is licensed under the MIT License.

```

This README now provides a complete guide for running both the Vite server and JSON server in one file.
```
