
---

# 🌟 Advanced Face Liveness Detection System 🌟

![Face Recognition GIF](https://media.giphy.com/media/IsKFVXvVxyeN1aXfgj/giphy.gif?cid=790b7611lqs2vuq24v02mq7z2q2keawli3idg64fmq63wuy6&ep=v1_gifs_search&rid=giphy.gif&ct=g)  
*A modern solution for secure face verification using hybrid detection techniques.*

## Overview
This project develops an **Advanced Face Liveness Detection System** that ensures secure and accurate face verification by combining **hybrid detection** techniques. The system integrates **active liveness detection** through AI-generated random action prompts and **passive methods** like facial texture and depth analysis to prevent spoofing attacks (e.g., photos or videos).

## Features 🚀
- 🧠 **Hybrid Detection**: Combines active (user interaction) and passive (facial texture, depth) methods for enhanced liveness detection.
- 🤖 **AI-Generated Prompts**: Dynamically generates random action prompts (e.g., blinking, head tilts) based on facial analysis, making it difficult to spoof.
- 🖼️ **Passive Liveness Detection**: Utilizes advanced facial texture, depth, and motion analysis to detect any spoofing attempts using photos or videos.

## Technologies 🛠️
- **OpenCV**: For real-time facial recognition and image processing.
- **Python**: Core programming language.
- **TensorFlow**: For AI-generated prompts and facial analysis.
- **ONNX.js** : For Running on browser
- 🧬 **Deep Learning**: For facial texture and depth detection.
- 🎯 **AI Prompt Generation**: Uses AI to personalize action prompts for users.

## Future Improvements 🌱
- ⚡ **Improve AI models** for faster and more accurate prompt generation.
- 🌐 **Expand passive detection methods** with 3D depth sensing and additional techniques.
- 📱 **Implement mobile-friendly** versions of the system for wide accessibility.

## Installation ⚙️
1. Clone the repository:
   ```bash
   git clone https://github.com/pratikwayal01/Advanced-Face-Liveness-Detection-System.git
   ```
   ```bash
   cd Advanced-Face-Liveness-Detection-System
   ```
2. Create virtual environmental venv:
   ```bash
   python -m venv venv
   ```
  - Activate it
   ```bash
   .\venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python liveness_detection.py
   ```

## License 📝
This project is licensed under the [MIT License](LICENSE).

---
