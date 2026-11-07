# PurrfectBreak 🐱

A delightful, distraction-free macOS menu bar break reminder. No Dock clutter, no intrusive popups — just a quiet status bar timer and an animated feline companion that visits your screen to remind you to rest your eyes and stretch.

Built natively in Swift and SwiftUI for macOS with zero third-party dependencies.

<br>

### ⚠️ A Note From the Developer
This is my very first vibe coding app, so please pardon me if there are any bugs, rough edges, or chaotic code strings hidden under the hood!

Because this is a personal passion project, **no official technical support is provided at this point.** That being said, I would absolutely love to hear from you—advices, feature requests, and future suggestions are incredibly welcome! Feel free to drop them in the repository's Issues tab.

<br>

## 🚀 Installation & Launch

Since this application is distributed independently and signed with an **Ad-Hoc local signature**, macOS will initially protect your system by warning you it's from an "unidentified developer." 

Follow these quick steps to install and open the app:

1. **Download the Installer**: Go to the **Releases** section on the right side of this repository page and download the latest `PurrfectBreak.dmg` file.
2. **Mount and Copy**: Double-click the `.dmg` file and drag the **PurrfectBreak.app** icon directly into your **Applications** folder shortcut.
3. **First-Time Launch (Crucial)**: 
   - Open your `/Applications` folder in Finder.
   - Do **NOT** double-click the app the first time.
   - Instead, **Right-click (or Control-click)** the `PurrfectBreak.app` icon and choose **Open**.
   - A dialog box will appear asking if you are sure. Click **Open**. 

*Note: You only need to do this the very first time. From now on, you can launch the app normally by double-clicking it or using Launchpad!*

Once running, look for the **coffee cup icon** in your macOS menu bar!

<br>

## ✨ Features

- **Menu Bar Native**: Lives quietly in your Mac's menu bar with a live countdown display. No Dock icon, no window clutter.
- **Transparent Desktop Overlay**: High-efficiency HEVC videos with alpha transparency animate directly over your live desktop.
- **Midpoint Pause & Resume**: Each animation seamlessly walks in, settles down to rest for the duration of your break, and walks out when the break completes.
- **Audio Alerts with Custom Sound Effects**: Gentle sound effect cues (5s, 10s, or 15s) ahead of the break so you can wrap up your thoughts. Sound effects automatically match your chosen cat!
- **Meeting & Presentation Detection**: Automatically postpones breaks whenever you're in a presentation, video call, or full-screen app (Keynote, PowerPoint, Zoom, etc.).
- **Multi-Monitor Customization**: Choose whether animations appear across all connected monitors or strictly on your **Main Display Only** (secondary displays dim gently).
- **Top-Center Skip Control**: Unobtrusive Skip button centered beneath the Mac webcam. Pressing **Esc** or clicking **Skip** triggers the exit animation smoothly.
- **Instant Privacy Mode ("Block Screen Now")**: Need to step away from your desk? One click blurs your desktop with an indefinite cat overlay until you return.
- **Timer Presets**: Fast 1-click presets for the **20-20-20 Rule**, **Pomodoro**, and **Deep Work**.

<br>

## 📖 How It Works

### The Daily Flow
1. **Focus Time**: The menu bar displays the minutes remaining until your next break (e.g. `20m`).
2. **Audio Alert**: A few seconds before your break (configurable to 5s, 10s, or 15s), a gentle sound effect plays to let you know a break is approaching.
3. **The Break**:
   - The cat walks onto your screen and gets comfortable.
   - Halfway through the clip, the video rests on a calm looping/paused pose while the break countdown runs.
   - When the break ends, the cat wakes up and smoothly walks off your screen.
4. **Repeat**: If automatic restart is enabled, your next focus timer begins immediately.

### Controls & Shortcuts
- **Skip Break (`Esc` or Skip Button)**:
  - While resting: Pressing **Esc** or clicking the top-center **Skip** button smoothly plays the cat's exit animation.
  - Pressing **Esc** a second time during exit dismisses the overlay immediately.
- **Block Screen Now**:
  - Available in the menu bar menu or Settings.
  - Blurs your desktop and holds the cat on screen indefinitely until dismissed — ideal for privacy when stepping away from your desk.

<br>

## ⚙️ Settings (⌘,)

Click the menu bar item and choose **Settings…** (or press **⌘,**):

### 1. Timers
- **Focus duration**: Slider from 5 to 120 minutes (default: 20 min).
- **Break duration**: Slider from 10 to 300 seconds (default: 20 sec).
- **Start / Stop Timer**: Toggle timer countdowns on or off directly from Settings.

### 2. Presets
Quickly apply proven productivity schedules with a single click:
- **20-20-20 Rule**: 20 min focus / 20 sec break (optimal for eye strain).
- **Pomodoro**: 25 min focus / 5 min break.
- **Deep Work**: 50 min focus / 10 min break.

### 3. Audio Alert
- **Sound Effect**: Choose lead time: **Off**, **5s**, **10s**, or **15s** before break.
- **Preview**: Test the sound effect for your currently selected cat.

### 4. Appearance
- **Overlay Dimming**: Adjust screen dimming from 0% (crystal clear desktop) up to 80% soft dark tint.

### 5. Multi-Monitor Displays
- **Animation on main display only**: When enabled, the cat animation appears strictly on your primary screen, while secondary monitors dim gently without distractions.

### 6. Break Video
- **Animation**: Choose your companion from available video clips (e.g., `Cat - White`, `Cat - Black`, or `Random`).
- **Block my Screen Now**: Instantly tests the animation and blurs your display.

### 7. Meetings & General
- **Postpone during meetings & presentations**: Pauses breaks while Keynote, PowerPoint, Zoom, or full-screen apps are active.
- **Restart cycle automatically**: Continuously loops focus and break cycles throughout your workday.
- **Launch at login**: Automatically starts PurrfectBreak when you log into your Mac.

<br>

## ⌨️ Menu Bar Shortcuts

| Action | Shortcut | Description |
| --- | --- | --- |
| **Settings** | `⌘,` | Open Preferences |
| **Quit** | `⌘Q` | Quit PurrfectBreak |
| **Skip / Exit** | `Esc` | Play exit animation / dismiss break |

<br>

## 🛠️ System Requirements

- **macOS**: 13.0 (Ventura) or newer.
- **Hardware**: Compatible with all Apple Silicon Macs (M1/M2/M3/M4) and Intel Macs with hardware video decoding.
- **Permissions**: Standard user permissions. No Accessibility, Screen Recording, or Administrator privileges required.

<br>

## 📄 License

Copyright (c) 2026. All rights reserved.

PurrfectBreak is distributed free of charge for personal and non-commercial use. Commercial deployment, resale, reverse engineering, or modifications to the distributed binary are strictly prohibited. The software is provided "as is", without warranty of any kind.

<br>

## 🛠️ Developer & Source Code Notice

The source code for PurrfectBreak is currently maintained in a private internal development archive. We plan to open-source the native Swift infrastructure and compilation build tools at a later date. Stay tuned!
