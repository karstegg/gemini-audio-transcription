# Audio Transcription App

A simple web application that uses Google's Gemini API to transcribe audio files.

## Features

- Upload and transcribe audio or video files
- Support for large files through file chunking
- Visual progress indicators
- Debug console for development and troubleshooting

## Getting Started

### Prerequisites

- Node.js 20 or higher
- Google Gemini API key ([Get one here](https://g.co/ai/idxGetGeminiKey))

### Installation

1. Clone the repository:
```bash
git clone https://github.com/karstegg/gemini-audio-transcription.git
cd gemini-audio-transcription
```

2. Install dependencies:
```bash
npm install
```

3. Configure your API key:
   - Open `config.js`
   - Replace the placeholder API key with your own

4. Start the development server:
```bash
npm run dev
```

5. Open your browser and navigate to the URL shown in the terminal (usually http://localhost:5173)
