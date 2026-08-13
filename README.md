
# 🎵 Chord Trainer

> **Train instant chord recognition – no hesitation, just playing.**

A powerful, cross‑platform web app that helps you build harmonic fluency – the ability to see any chord symbol and play it instantly, without thinking. Play chords on a MIDI keyboard or the built‑in touch‑friendly piano, and get immediate visual feedback.

Whether you're a *music student, an accompanist, or a jazz pianist, this trainer is designed to help you translate any chord symbol into the right notes without hesitation.

## ✨ Features

| Category | Features |
|----------|----------|
| **🎹 Input** | – Bluetooth / USB MIDI support (Windows, iOS, Android) <br> – On‑screen two‑octave piano (touch or mouse) |
| **🎼 Practice Modes** | – Roman numerals, Absolute chord symbols, and Mixed <br> – Fixed or **Modulating** key mode (each chord can change key) |
| **🎯 Smart Practice** | – **Practice Library** – filter by chord family (Major, Minor, Dominant 7, etc.) <br> – **Voice Leading** – smooth inversions for musical progressions <br> – **Strict Inversions** – force yourself to play the exact inversion shown |
| **🎧 Feedback** | – Real‑time visual feedback on the piano keys: <br> &nbsp; 🟩 Green = correct note <br> &nbsp; 🟥 Red = extra note <br> &nbsp; 🟦 Blue = missing note <br> – Auto‑check or manual check |
| **🔊 Sound** | – Warm, built‑in piano‑like synth with reverb <br> – **MIDI Thru** mode – use the app for detection while routing sound to Pianoteq or other synths |
| **📊 Progress** | – Tracks correct/wrong, streak, and average response time |
| **🌍 Cross‑Platform** | – Works on **Windows**, **macOS**, **iOS**, **iPadOS**, and **Android** <br> – Just a single HTML file – no installation, no app store, no strings attached |

---

## 🚀 Quick Start

1. **Open the app** in your browser:
   - `https://micfe21.github.io/Chord-trainer/chordsequencetrainer17.1.html`
2. **Tap `Start Audio`** (orange button) – this enables sound.
3. **Tap `Generate`** – a chord sequence appears.
4. **Read the chord symbol** in the big display.
5. **Play it** on your MIDI keyboard or the on‑screen piano.
6. **Get feedback** – green keys mean correct, red/blue mean wrong.
7. **Repeat** – the app automatically moves to the next chord.

> 💡 **Tip:** If you have a MIDI keyboard, tap the `MIDI` button and select your device from the dropdown. If not, just tap the keys on the screen.

---

## 🎮 Modes & Controls

| Control | What it does |
|---------|--------------|
| **Key** | Set the key for Roman/Mixed modes. |
| **Mode** | Choose `Roman`, `Absolute`, or `Mixed` chord display. |
| **Key Mode** | `Fixed` – all chords in one key <br> `Modulating` – each chord can be in a different key (great for ear training). |
| **Length** | Number of chords in the sequence (4 – 10). |
| **Triads / Sevenths / Both** | Choose chord complexity. |
| **Voice Leading** | Inverts chords for minimal hand movement – smooth and musical. |
| **Strict Inversions** | Forces you to play the exact inversion shown (`root`, `1st`, `2nd`, `3rd`). Perfect for advanced voicing practice. |
| **Practice Library** | Focus on specific families: Major, Minor, Dominant 7, Major 7, Minor 7, Half‑dim, Dim 7, Aug, Sus, Extended, Altered. |
| **Borrowed Chords** | Occasionally pulls chords from other keys – keeps you on your toes. |

---

## 🛠️ Files in this Repository

| File | Purpose |
|------|---------|
| `chordsequencetrainer17.html` | **Main app** – latest version with Strict Inversions. |
| `setup-guide.html` | Cross‑platform setup guide for USB and Bluetooth 
| `chordsequencetrainermanual.html` | User manual (print‑friendly). |

---

## 🖥️ Platform Support

| Platform | MIDI | On‑Screen Keyboard | Sound |
|----------|------|-------------------|-------|
| **Windows** (Chrome/Edge) | ✅ USB / Bluetooth (via MIDIberry) | ✅ | ✅ |
| **macOS** (Chrome/Edge) | ✅ USB / Bluetooth | ✅ | ✅ |
| **iOS / iPadOS** (Web MIDI Browser) | ✅ Bluetooth | ✅ | ✅ |
| **Android** (Chrome/Edge) | ✅ USB | ✅ | ✅ |

---

## 📝 Keyboard Shortcuts

- **`Space`** – Manually check the current chord (same as "Check" button).

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

> © 2026 [micfe21](https://github.com/micfe21) – Free for personal use and sharing. Not for commercial sale or distribution.

---

## 🙌 Acknowledgements

Built with ❤️ using vanilla JavaScript, Web MIDI API, and Web Audio API.  
Special thanks to the open‑source community for making cross‑platform music tools accessible to everyone.

---

## 📬 Feedback

Feel free to open an issue or discussion on GitHub if you have suggestions, questions, or just want to say hi!

---

**Enjoy practising! 🎹**
