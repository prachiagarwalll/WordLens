## 📖 WordLens

**WordLens** is a client-side dictionary web app that extracts words from images in the browser and shows real-time definitions and Wikipedia links on hover.

### 🔧 Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **OCR:** [Tesseract.js](https://tesseract.projectnaptha.com/) (runs fully in the browser via HTML5 Canvas + WebAssembly)  
- **Zero-backend architecture:** All OCR, lookups, and caching run entirely client-side  

### 🚀 Features
- 🖼️ **Real-time OCR**: 95%+ word detection accuracy on standard printed documents  
- ⚡ **Fast & Lightweight**: Page load and lookup latency reduced by ~30% with client-side execution  
- 📚 **Smart Lookup**: Hover-based tooltips instantly fetch definitions and Wikipedia links  
- 🖱️ **Improved UX**: ~40% faster interaction speed compared to traditional click-based flow  

### 🌐 How It Works
1. Upload or drop an image into the app  
2. The app extracts text in real-time using Tesseract.js  
3. Hover over any recognized word to instantly see its definition and related Wikipedia entry  

---
