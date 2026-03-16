# Hamster Punch 🐹🥊 (萌萌仓鼠大作战)

An interactive, browser-based AR game where you use your real hands to punch virtual hamsters! Powered by MediaPipe hand tracking.

![Hamster Punch Demo](https://img.shields.io/badge/Status-Playable-success)
![Technology](https://img.shields.io/badge/Tech-HTML5%20%7C%20Canvas%20%7C%20MediaPipe-blue)

## Features
*   **Webcam Hand Tracking:** Uses your camera to track your hand movements in real-time.
*   **Gesture Controls:** 
    *   ✌️ **Scissors**: Player 2 hammer.
    *   ✊ **Fist**: Summon the hammer.
    *   ⬇️ **Punch Down**: Smash the hamster!
*   **No Installation Required:** Runs entirely in your web browser.
*   **Privacy First:** All video processing is done locally on your machine.

---

## 游戏指南 / How to Play

### 🎮 How to Play (English)
1.  **Open the Game:** Open `index.html` in a modern web browser (e.g., Chrome, Edge).
2.  **Allow Camera Access:** The game requires your webcam to track your hands.
3.  **Player 2:** Make a **scissors (✌️)** gesture with your hand to summon the blue hammer.
4.  **Player 1:** Make a **fist (✊)** with your hand to summon the red hammer.
5.  **SMASH!:** Quickly swing your fist **downwards (⬇️)** when a hamster appears! You only have 0.5 to 1 second before they hide again!

### 🎮 游戏指南 (中文)
1.  **打开游戏：** 在现代浏览器（推荐 Chrome 或 Edge）中直接双击打开 `index.html`。
2.  **允许摄像头权限：** 浏览器会提示需要摄像头权限来识别您的手部动作，请点击允许。
3.  **玩家 2：** 比出 **剪刀手 (✌️)**，召唤蓝色惩罚之槌。
4.  **玩家 1：** 将手 **握紧成拳 (✊)**，召唤红色惩罚之槌。
5.  **出击！：** 当仓鼠钻出地洞时，迅速 **向下挥拳 (⬇️)** 用力敲击！注意，仓鼠只会在洞口停留 0.5 到 1 秒哦，拼手速的时候到了！

---

## 🔒 Privacy Statement / 隐私声明

**English:**
*All camera feeds are processed in real-time locally within your browser. This game will never collect, store, or upload any facial or environmental privacy data. Please enjoy the game with peace of mind.*

**中文：**
*本游戏所有摄像头画面仅在您的本地/浏览器实时处理，绝不会收集或上传任何面部及环境隐私数据，请放心体验。*

---

## Development

This game was developed using pure HTML5 Canvas and the `@mediapipe/hands` library for lightweight, plug-and-play browser interaction.
