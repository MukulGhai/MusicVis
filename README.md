# 🎵 Music Visualizer (Web Audio API)

A modern, interactive **Music Visualizer Web App** built using **HTML, CSS, and JavaScript**.  
This project allows users to upload audio files and experience real-time visualizations powered by the **Web Audio API**.

---

## 🚀 Features

- 🎧 Upload and play any audio file
- 🎨 Multiple visualization modes:
  - Bars
  - Waveform
  - Radial
  - Spiral
- ⏯ Play / Pause control
- ⏱ Real-time progress bar with seek functionality
- 🌈 Dynamic color transitions (hue shifting)
- ✨ Particle effects reacting to music energy
- 🖥 Responsive full-screen canvas UI
- 🎼 Displays track name and duration

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **Web Audio API**
- **Canvas API**

---

## 📂 Project Structure

```
music-visualizer/
│
├── index.html   # Main application file (UI + logic)
```

---

## ⚙️ How It Works

1. User uploads an audio file  
2. File is decoded using the **AudioContext**  
3. Audio data is passed to an **Analyser Node**  
4. Frequency & time-domain data is extracted  
5. Canvas renders visuals based on:  
   - Frequency data → Bars / Radial / Spiral  
   - Time data → Waveform  
6. Animation loop updates visuals in real-time  

---

## 🎮 Controls

| Control | Description |
|--------|-------------|
| ▶ / ⏸ | Play / Pause audio |
| Progress Bar | Seek audio position |
| Load Track | Upload audio file |
| Mode Buttons | Switch visualization style |

---

## 🎨 Visualization Modes

### 1. Bars
- Frequency-based vertical bars  
- Reacts strongly to bass and beats  

### 2. Wave
- Smooth waveform line  
- Based on time-domain signal  

### 3. Radial
- Circular spectrum visualization  
- Expands with energy  

### 4. Spiral
- Dynamic spiral particles  
- Rotates with time and sound intensity  

---

## ✨ Special Effects

- 🔥 Particle bursts on high energy peaks  
- 🌌 Background glow using radial gradients  
- 🎨 Hue cycling for smooth color transitions  

---

## 📦 Setup & Usage

1. Clone the repository:
```bash
git clone https://github.com/your-username/music-visualizer.git
```

2. Open the project:
```bash
cd music-visualizer
```

3. Run:
- Simply open `index.html` in your browser  

---

## ⚠️ Notes

- Works best in modern browsers (Chrome, Edge)  
- Audio playback requires user interaction (browser policy)  
- Large files may take time to load  

---

## 💡 Future Improvements

- Playlist support  
- Volume control  
- Beat detection enhancements  
- Mobile optimization  
- Dark/Light theme toggle  
- Export visualization as video  

---

## 🙌 Author

**Mukul Ghai**
