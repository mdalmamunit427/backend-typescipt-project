# Backend TypeScript Project

A modern backend application built with TypeScript and Express.js.

## 🚀 Features

- TypeScript for type safety and better development experience
- Express.js for building robust web applications
- Environment variable support with dotenv
- Development server with hot-reload
- ESLint for code linting
- Prettier for code formatting

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd backend-typescipt-project
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:
```env
PORT=3000
# Add other environment variables as needed
```

## 🚀 Available Scripts

In the project directory, you can run:

- `npm run dev` - Starts the development server with hot-reload
- `npm run build` - Compiles TypeScript to JavaScript
- `npm start` - Runs the compiled JavaScript
- `npm run lint` - Runs ESLint to check code quality

## 📁 Project Structure

```
src/
  ├── server.ts        # Main application entry point
  ├── routes/          # API routes
  ├── controllers/     # Route controllers
  ├── models/          # Data models
  ├── services/        # Business logic
  └── utils/           # Utility functions
```

## 🔧 Development

1. Start the development server:
```bash
npm run dev
```

2. The server will start on `http://localhost:3000` (or the port specified in your .env file)

## 📝 Code Style

This project uses:
- ESLint for code linting
- Prettier for code formatting

To format your code:
```bash
npx prettier --write "src/**/*.ts"
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 📧 Contact

[Your Name] - [Your Email]

Project Link: [https://github.com/yourusername/backend-typescipt-project](https://github.com/yourusername/backend-typescipt-project) 