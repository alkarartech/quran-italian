# quran-italian
# 📖 Quran Audio Hosting Repository
Stream Quranic recitations directly in your apps/websites—no downloads required!

This repository hosts high-quality MP3 files of Quran recitations, optimized for direct streaming (playback without forcing downloads). Use the links in your projects to embed Quran audio seamlessly.

## 🔗 How to Use the Audio Links
Direct MP3 Links (Streaming)
Replace [filename].mp3 with the surah/reciter you need:
(Right now there is only one reciter but I may add more)

https://alkarartech.github.io./quran-audio/###.mp3

(### << surah number i.e. Surah Al-Fatiha is 001)

### Example:

https://alkarartech.github.io./quran-audio/001.mp3

#### Embed in HTML (Audio Player)
html

<audio controls>
  <source src="https://alkarartech.github.io./quran-audio/001.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
Run HTML
For Developers (JavaScript Example)
javascript


const audio = new Audio("https://alkarartech.github.io./quran-audio/001.mp3");
audio.play(); // Play programmatically

## 📂 File Structure

/repo-root
│
├── /reciters
│   ├── /reciter1
│   │   ├── surah1.mp3
│   │   └── surah2.mp3
│   └── /reciter2
│       └── ...
│
└── /surahs
    ├── surah1.mp3
    └── surah2.mp3

## ⚠️ Important Notes
No downloads required – Files stream by default in most browsers.

Hotlinking allowed – Use these URLs directly in your apps/websites.

For non-commercial use – Respect copyrights of reciters.

## 🤝 Contributing
To add more recitations:

Fork this repo

Add files (follow naming conventions)

Submit a Pull Request

## 📜 License
This project is dedicated to the public domain (Unlicense). Verify reciter permissions for redistribution.
