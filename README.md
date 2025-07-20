# Ambient Mode Video Player

A dynamic ambient mode video player inspired by Google’s Ambient Mode and YouTube reels.

## Description

This project recreates an ambient mode experience by analyzing the video content in real-time and changing the background color to match the dominant colors of the video frames. The ambient background smoothly transitions as the video plays, enhancing the viewing experience with immersive visuals.

## How It Works

1. **Video Playback:** The user watches a video or reel within the player.
2. **Color Extraction:** Frames from the video are periodically captured and processed to extract dominant colors.
3. **Background Update:** The background color dynamically changes to match the extracted dominant color, with smooth transitions.
4. **Continuous Sync:** The process repeats to keep the background color synced with the video content in real-time.

## Features

- Real-time color extraction from video frames.
- Smooth color transitions to enhance immersion.
- Responsive design suitable for reels and short videos.
- Lightweight and easy to integrate into any web project.

## Demo

[Insert link to live demo or screenshots here]

## Technologies Used

- HTML5 Video Element
- JavaScript (with Canvas API for frame capture)
- Color extraction algorithms / libraries (e.g., `color-thief`)
- CSS3 transitions and animations

## Getting Started

### Prerequisites

- Modern web browser with HTML5 and JavaScript support
- Optional: Node.js if you want to run a local server

### Installation

1. Clone the repository:

```bash
git clone https://github.com/gnew123/ambient-mode.git
