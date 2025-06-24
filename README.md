
# VibOS.ai – Final React Demo

This is the final production-ready React + TailwindCSS version of the VibOS.ai demo, now with Firebase memory and voice AI.

---

## ✅ Features
- Emotional voice response (TTS)
- Voice input (speech-to-text)
- GPT-3.5 integration (OpenAI)
- Persistent memory (Firebase)
- Clean modern UI

---

## 🚀 How to Launch the Demo

### 1. Install Prerequisites
- Make sure Node.js is installed (https://nodejs.org/)
- Use terminal (Mac/Linux) or Command Prompt (Windows)

### 2. Unzip the folder
Extract `vibos-react-final.zip` and open terminal in that folder.

### 3. Install dependencies
```
npm install
```

### 4. Start the app locally
```
npm start
```

### 5. Add your OpenAI API key
Edit `src/services/openai.js` and replace the placeholder:
```js
const OPENAI_API_KEY = "YOUR_OPENAI_API_KEY";
```

### 6. Firebase is already configured
Your Firebase project is pre-wired in `src/services/firebase.js`. No setup needed unless you want to customize.

---

## 🌐 Deploy to GitHub Pages (Optional)
If you want it at vibos.ai/demo:
1. Run:
```
npm run build
```
2. Push to GitHub, configure GitHub Pages to point to `/build`
3. Or deploy via Vercel (https://vercel.com)

---

Enjoy!
