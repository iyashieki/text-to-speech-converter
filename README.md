# 🎙️ Text-to-Speech Converter

A simple **text-to-speech (TTS) web app** built with **HTML, CSS, and JavaScript**, powered by the **Web Speech API**.  
Type any text, choose a voice, and click "Listen" to hear it spoken aloud.  

---

## ✨ Features
- Convert typed text into speech
- Choose between available system/browser voices
- Click outside to close the dropdown
- Cancel old speech when refreshing or replaying
- Works on both **desktop** and **mobile**
- Clean, responsive UI with custom styling

---

## 📜 Limitations
- Voice options depend on your **device, browser, and installed system voices**.  
- On **desktop browsers** (Chrome, Edge, Firefox), you may see dozens of voices in multiple languages.  
- On **mobile browsers** (iOS Safari, Android Chrome), only a few voices are available, and they usually match your **system language**.  

For example:  
- If your phone language is set to **Turkish**, you may only see 3–4 Turkish voices.  
- Even if you type English text, those voices will pronounce it with a Turkish accent.  

✅ To get more voices in different languages, you need to **install additional voices** at the OS level:  
- **Android**: Settings → Language & Input → Text-to-speech → Install voice data.  
- **iOS**: Settings → Accessibility → Spoken Content → Voices → Download a new language.  

This is a **browser/system limitation**, not a bug in this project.
