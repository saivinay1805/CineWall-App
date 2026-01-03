
https://github.com/user-attachments/assets/3e285e1f-77a1-4065-82a9-6eb61a45b75f
# <img src="https://via.placeholder.com/50?text=+" width="40" align="center"/> CineWall

**The Native "Liquid Glass" Video Wallpaper Engine for macOS.**

[![macOS](https://img.shields.io/badge/Platform-macOS-black?logo=apple)](https://www.apple.com/macos)
[![Release](https://img.shields.io/github/v/release/saivinay1805/CineWall-App?color=blue&label=Latest%20Version)](https://github.com/saivinay1805/CineWall-App/releases/latest)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

### 🎥 Live Demo

https://github.com/user-attachments/assets/cd3b29fd-9c5f-447c-9b2b-b33df9c2dc9f

<br>

https://github.com/user-attachments/assets/d86b8f6b-ca3b-4ff0-b715-84e853954f44

---

### 📖 Overview
**CineWall** is a high-performance, native macOS utility designed to turn your desktop into a cinematic experience.

While many wallpaper engines exist, most restrict users to single-file selection or require importing files into a proprietary library. **CineWall** was built to solve this. It plays your local **Folders**, **GIFs**, and **Videos** directly from your disk (including external SSDs) without duplicating files or requiring uploads.

It features a stunning **"Liquid Glass" UI** (inspired by macOS Tahoe concepts) that blends seamlessly into your desktop environment.

### ✨ Key Features

#### 🌊 Aesthetics & UI
*   **Liquid Glass Interface:** A modern, borderless, refractive menu that blurs the background behind it.
*   **Minimalist Player:** Full playback controls (Previous, Next, Pause) with a live **scrubbing bar**.
*   **Pin Mode:** Keep the menu open and floating above other windows for easy control.

#### 🎛️ Playlist & File Management
*   **Folder Support:** Point CineWall to a folder, and it will auto-play all contained videos and GIFs.
*   **Smart Persistence:** Remembers your last played file and folder, even after a restart.
*   **Drag & Drop:** Simply drag a video file onto the menu to play it instantly without navigating finder.
*   **Zero-Space Favorites:** Add videos to your "Favorites" list without duplicating the file storage.

#### ⚡ Performance & Intelligence
*   **Smart Pause:** Automatically pauses playback when:
    *   An application is maximized/fullscreen.
    *   The desktop is completely covered (Occlusion detection).
    *   (Optional) You focus on another application.
*   **Battery Saver:** Automatically pauses the engine when the MacBook is unplugged.
*   **SSD Auto-Mount:** If your wallpaper library is on an external drive, CineWall detects when the drive connects and auto-loads your playlist.
*   **Native Core:** Built with Swift and `AVFoundation`. Uses negligible CPU (approx 0% when paused, <5% when playing 4K).

#### 🖥️ Desktop Integration
*   **Hide Desktop Icons:** One-click toggle to hide all desktop icons and widgets for a clean look.
*   **Multi-Space Support:** Choose to show the wallpaper on all Spaces or bring it to the current active Space.

---

### 📥 Installation

**CineWall is an unsigned open-source application.** To run it, you must bypass the Gatekeeper warning once.

1.  **[Download the latest ZIP](https://github.com/saivinay1805/CineWall-App/releases/latest)** from the Releases page.
2.  Unzip and move `CineWall.app` to your **Applications** folder.
3.  **Right-Click** the app and select **Open**.
4.  Click **Open** in the dialog box.
5.  *(Optional)* Grant **Accessibility Permissions** in System Settings to enable the "Hide Desktop Icons" feature.

---

### 🗺️ Roadmap & Known Limitations
*   **Current:** Supports the main primary display.
*   **Planned:** Lock Screen support (Currently investigating native APIs to prevent the wallpaper from resetting on lock).
*   **Planned:** Multi-monitor support (Different wallpapers for different screens).

---

### 🤝 Contributing & Feedback
This project was built to scratch a personal itch, but feedback is welcome!
If you encounter bugs or have feature requests, please [open an issue](https://github.com/saivinay1805/CineWall-App/issues).

---

*Built with ❤️ for the Mac Community.*
