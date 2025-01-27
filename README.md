# Node-RED Google Speech Custom

🚀 **This package is an enhancement of [`node-red-contrib-viseo-google-speech`](https://www.npmjs.com/package/node-red-contrib-viseo-google-speech), adding new features for better speech recognition and synthesis.**

## 🔹 Features Added:
- 🌍 **Alternative Languages Parameter** in the Speech-to-Text function.
- 🎙 **Voice Name Selection** in the Text-to-Speech Node.

This package integrates with **Google Speech API** to provide **speech-to-text (STT) and text-to-speech (TTS)** functionalities.

---

## 📥 Installation

To install the package in your Node-RED environment, run:
```sh
npm install node-red-contrib-viseo-google-speech-custom
```


## 📝 How to Use in Node-RED

### **1️⃣ Add the Node**
- Install the package (`node-red-contrib-viseo-google-speech-custom`).
- Open **Node-RED** and drag the **Google Speech** node into the flow.

### **2️⃣ Configure the Node**
- **For STT**: Set **language parameters** (e.g., `["en-US", "fr-FR"]`).
- **For TTS**: Choose **voice name** and **gender**.

### **3️⃣ Connect and Deploy**
- Link the node to other nodes (e.g., inject, function, debug).
- Click **Deploy** and test your speech recognition or synthesis.


## 💬 Support & Contributions

If you need help or want to report an issue:

- Open an issue in the [GitHub Issues Tracker](https://github.com/YOUR_GITHUB_REPO/issues).
- Ensure you mention that you are using this **custom-enhanced version**.

### **How to Contribute**
1. **Fork** the repository.
2. **Add your enhancements** and submit a **pull request**.
3. Follow best practices and include clear documentation.

---

## 📢 Disclaimer

This is an **unofficial enhanced version** of the original `node-red-contrib-viseo-google-speech` package.  
It **adds new features** but does not modify the original core functionality.
