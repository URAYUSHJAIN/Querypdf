# QueryPDF 🔒

A privacy-focused PDF chat application that runs 100% in your browser using AI.

## Architecture

![QueryPDF Architecture](https://raw.githubusercontent.com/URAYUSHJAIN/Querypdf/main/architecture-diagram.png)

**100% Client-Side Processing** - No data leaves your device. No backend server.

## Features

- 🔐 **100% Private** - All processing happens locally in your browser
- 💬 **AI-Powered Chat** - Ask questions about your PDF content
- 📝 **Smart Summaries** - Generate document summaries automatically
- 🎯 **Interactive Quizzes** - Create quizzes to test your knowledge
- 📱 **Mobile Friendly** - Works on phones, tablets, and desktops
- ⚡ **Fast & Free** - No sign-up, no server, no data tracking

## How It Works

1. Upload a PDF document
2. AI model processes it locally in your browser
3. Ask questions, generate summaries, or create quizzes
4. Your data never leaves your device

## Tech Stack

- **AI Model**: Xenova/flan-t5-small (via Transformers.js)
- **PDF Processing**: PDF.js
- **UI**: Tailwind CSS
- **Runtime**: Pure JavaScript (ES6 modules)

## Usage

Simply open `index.html` in a modern web browser. The AI model will download and cache on first use (~850MB).

## Enhanced Features

- **Larger PDF View**: 2x scale rendering for better readability
- **One Page at a Time**: Clean, focused page-by-page navigation
- **Aspect Ratio Preserved**: PDF pages display without distortion
- **Smart Context Search**: Keyword-based relevant text retrieval
- **Responsive Design**: Optimized for all screen sizes

## Privacy

- No server-side processing
- No data collection or analytics
- No cookies or tracking
- Works offline after initial model download

## License

Open Source | Privacy First

---

**Note**: First-time load requires downloading the AI model (~850MB). Subsequent visits use cached model for instant startup.
