# Recipe Management Application

A modern, full-stack recipe management application built with Next.js 14, TypeScript, and Tailwind CSS. This application allows users to create, manage, and share their favorite recipes.

## 🚀 Features
- [Recipe App Feature Development Board](https://trello.com/b/LsFF1kFO/recipe-app)

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/Bobali92/recipe-app.git
cd recipe-app
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
Create a `.env` file in the root directory and add the following:
```env
DATABASE_URL="postgresql://username:password@localhost:5432/recipe_app"
NEXT_PUBLIC_APP_URL="http://localhost:3000"
```

4. **Start the development server**
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## 📁 Project Structure

```
recipe-app/
├── src/
│   ├── app/                # App router pages
│   ├── components/         # React components
│   ├── lib/               # Utility functions
│   ├── types/             # TypeScript types
│   ├── styles/            # Global styles
│   ├── hooks/             # Custom React hooks
│   └── config/            # Configuration files
├── public/                # Static files
└── tests/                 # Test files
```

## 🔑 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build production application
- `npm start` - Start production server

## 🧪 Testing

Run the test suite:
```bash
npm test
```

Run tests in watch mode:
```bash
npm test:watch
```

### Deploy to Vercel

1. Push your code to GitHub
2. Import your repository to Vercel
3. Set up environment variables
4. Deploy!

## 🤝 Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Commit your changes: `git commit -m 'Add amazing feature'`
5. Push to the branch: `git push origin feature/amazing-feature`
6. Submit a pull request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)


