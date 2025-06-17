# 🎓 Flashcard Generator App

A modern, intelligent flashcard generator that transforms educational content into interactive study materials. Built with React, TypeScript, and Tailwind CSS.

![Flashcard Generator Demo](./public/demo.png)

## ✨ Features

- **📁 File Upload**: Drag-and-drop support for .txt files (PDF parsing simulated)
- **📝 Text Input**: Direct paste functionality for educational content
- **🎯 Subject Selection**: 12+ academic subjects with specialized question patterns
- **🤖 Intelligent Generation**: AI-powered flashcard creation with 10-15 Q&A pairs
- **🎴 Interactive Cards**: Beautiful 3D flip animations for engaging study experience
- **📊 Export Options**: Download flashcards in JSON or CSV format
- **📱 Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **🎨 Modern UI**: Clean, professional design with smooth animations

## 🚀 Live Demo

[View Live Demo](https://your-demo-url.netlify.app) *(Replace with your deployed URL)*

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Deployment**: Netlify/Vercel ready

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/flashcard-generator.git
   cd flashcard-generator
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Project Structure

```
flashcard-generator/
├── public/
│   ├── demo.png
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── FileUpload.tsx
│   │   ├── TextInput.tsx
│   │   ├── SubjectSelector.tsx
│   │   └── FlashcardDisplay.tsx
│   ├── utils/
│   │   ├── flashcardGenerator.ts
│   │   └── exportUtils.ts
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── vite-env.d.ts
├── package.json
├── tailwind.config.js
├── vite.config.ts
└── README.md
```

## 🎯 Usage

### 1. Input Content
- **Upload File**: Drag and drop a .txt file or click to browse
- **Paste Text**: Directly paste educational content into the text area
- **Select Subject**: Choose from 12+ academic subjects for better results

### 2. Generate Flashcards
- Click "Generate Flashcards" to create 10-15 Q&A pairs
- The AI analyzes your content using subject-specific patterns
- Wait for the generation process to complete

### 3. Study & Export
- Click any flashcard to flip between question and answer
- Use "Reset All" to flip all cards back to questions
- Export your flashcards in JSON or CSV format

## 🧠 How It Works

The app uses intelligent pattern matching to generate flashcards:

1. **Content Analysis**: Breaks down text into meaningful sentences
2. **Pattern Recognition**: Uses subject-specific regex patterns to identify key concepts
3. **Question Generation**: Creates relevant questions based on content structure
4. **Answer Extraction**: Pairs questions with appropriate explanatory text

### Subject-Specific Patterns

- **Biology**: Focuses on processes, functions, and definitions
- **History**: Emphasizes dates, events, and historical figures
- **Computer Science**: Targets algorithms, methods, and technical concepts
- **General**: Applies universal question patterns for any subject

## 🎨 Design Features

- **Modern Aesthetics**: Clean, professional design with subtle gradients
- **3D Animations**: Smooth flip transitions for interactive experience
- **Responsive Layout**: Optimized for all screen sizes
- **Accessibility**: Proper contrast ratios and keyboard navigation
- **Loading States**: Visual feedback during processing
- **Error Handling**: Clear error messages and recovery options

## 📱 Responsive Design

The app is fully responsive with breakpoints for:
- **Mobile**: Single column layout, touch-optimized
- **Tablet**: Two-column card grid
- **Desktop**: Three-column layout with sidebar

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Code Quality

- **TypeScript**: Full type safety throughout the application
- **ESLint**: Configured with React and TypeScript rules
- **Prettier**: Code formatting (add .prettierrc if needed)
- **Component Architecture**: Modular, reusable components

## 🚀 Deployment

### Netlify
1. Build the project: `npm run build`
2. Deploy the `dist` folder to Netlify
3. Set build command: `npm run build`
4. Set publish directory: `dist`

### Vercel
1. Connect your GitHub repository
2. Vercel will auto-detect Vite configuration
3. Deploy with default settings

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons by [Lucide](https://lucide.dev/)
- Styling with [Tailwind CSS](https://tailwindcss.com/)
- Built with [Vite](https://vitejs.dev/) and [React](https://reactjs.org/)

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Contact: your-email@example.com

---

**Made with ❤️ by [Your Name]**

*Transform your study materials into interactive flashcards!*