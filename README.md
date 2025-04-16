# 🌐 3D Circle Animation with HTML & CSS

This project demonstrates a beautiful 3D-like animation effect using only **HTML** and **CSS** — no JavaScript required! A series of concentric circles animate upwards with a hue rotation, creating a glowing futuristic vibe.

## ✨ Features

- Pure CSS animation
- 3D illusion using `transform-style: preserve-3d`
- Smooth infinite loop
- Hue rotation for a dynamic color shift
- Lightweight and responsive

## 🚀 Technologies Used

- HTML5  
- CSS3 (Flexbox, Custom Properties, Keyframe Animations)

## 🎥 Preview

![Animation Preview](./preview.gif) <!-- Optional: replace with your preview gif or image -->

## 🛠️ How It Works

Each `.circle` uses a custom property (`--i`) to:
- Adjust size dynamically (`width: calc(var(--i) * 2.5vmin)`)
- Delay animations with `animation-delay`
- Add depth with `rotateX` and `translateZ`

The animation moves the circles vertically and applies a color shift using `hue-rotate`.
