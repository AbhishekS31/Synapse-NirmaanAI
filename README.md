# 🧠 Synapse NirmaanAI – Multimodal UI Generator for eCommerce

> Powered by AI | Built with React, Vite, and TailwindCSS

Synapse NirmaanAI helps eCommerce brands quickly generate brand-aligned landing pages using text prompts, brand inputs, and product images.  
Go from **idea → design → deploy** within minutes.

---

## 🚀 Features

- 🎨 Generate landing pages using AI-powered text prompts
- 🖼️ Upload product images and apply brand styles (colors, fonts, tone)
- 💻 Live code preview and editing with Monaco Editor
- 🎭 Add animations using Framer Motion
- 📦 Export project files (ZIP) or deploy directly
- ⚡ Built with Vite for lightning-fast development

---

## 🧱 Tech Stack

- **Frontend Framework:** React 18 + Vite + TypeScript
- **Styling:** TailwindCSS + shadcn/ui (Radix UI)
- **AI Integration:** Google Gemini API (gemini-1.5-pro)
- **Code Editor:** Monaco Editor
- **Live Preview:** Sandpack React
- **State Management:** Zustand
- **Animations:** Framer Motion
- **UI Components:** Lucide React Icons, Recharts
- **Routing:** React Router DOM
- **Form Handling:** React Hook Form + Zod
- **Deployment:** Vercel

---

## 📦 Getting Started

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/AbhishekS31/Synapse-NirmaanAI.git
cd Synapse-NirmaanAI
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Set Up Environment Variables

Create a `.env` file in the root directory and add your API key:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
```

📌 **Note:** Get your free Google Gemini API key from [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

### 4️⃣ Run the Development Server

```bash
npm run dev
```

Open your browser and visit: **http://localhost:5173**

### 5️⃣ Build for Production

```bash
npm run build
```

### 6️⃣ Preview Production Build

```bash
npm run preview
```

---

## 🚀 Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/AbhishekS31/Synapse-NirmaanAI)

**Easy Deployment Steps:**

1. Click the button above or visit [Vercel Dashboard](https://vercel.com/new)
2. Import your GitHub repository: `AbhishekS31/Synapse-NirmaanAI`
3. Add environment variable:
   - **Key:** `VITE_GEMINI_API_KEY`
   - **Value:** Your Google Gemini API key
4. Click **Deploy**!
5. Your app will be live in 2-3 minutes! 🎉

---

## 📁 Project Structure

```
Synapse-NirmaanAI/
├── src/
│   ├── components/          # React components
│   │   ├── ui/             # shadcn/ui components (40+ components)
│   │   ├── ChatPanel.tsx   # AI chat interface
│   │   ├── CodeEditor.tsx  # Monaco code editor
│   │   ├── PreviewPane.tsx # Live preview with Sandpack
│   │   ├── BrandSettings.tsx
│   │   ├── FileExplorer.tsx
│   │   └── ...
│   ├── lib/                # Utilities and API logic
│   │   ├── api.ts          # Gemini AI integration
│   │   ├── ai.ts           # AI helper functions
│   │   ├── store.ts        # Zustand state management
│   │   ├── prompts.ts      # AI prompts
│   │   └── utils.ts        # Utility functions
│   ├── hooks/              # Custom React hooks
│   ├── App.tsx             # Main app component
│   └── main.tsx            # Entry point
├── public/                 # Static assets
├── .npmrc                  # npm configuration (legacy-peer-deps)
├── vercel.json             # Vercel deployment config
├── vite.config.ts          # Vite configuration
├── tailwind.config.js      # TailwindCSS config
└── package.json            # Dependencies
```

---

## 📦 Key Dependencies

```json
{
  "dependencies": {
    "@google/generative-ai": "^0.24.0",      // Gemini AI SDK
    "@monaco-editor/react": "^4.7.0",        // Code editor
    "@codesandbox/sandpack-react": "^2.20.0", // Live preview
    "framer-motion": "^11.0.8",              // Animations
    "zustand": "^4.5.2",                     // State management
    "react-router-dom": "^7.5.2",            // Routing
    "react-hook-form": "^7.51.0",            // Form handling
    "zod": "^3.22.4",                        // Validation
    "lucide-react": "^0.358.0",              // Icons
    "file-saver": "^2.0.5",                  // Export functionality
    "jszip": "^3.10.1"                       // ZIP export
  }
}
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Abhishek S**  
GitHub: [@AbhishekS31](https://github.com/AbhishekS31)

---

**Made with ❤️ for the eCommerce community**
