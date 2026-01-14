# webrtc-random-video-chat-demo
"A lightweight, mobile-first WebRTC video chat implementation compatible with Safari iOS and 4G networks. Live production demo running at https://videochatcouple.com"
# WebRTC Random Video Chat (Mobile Ready)

A modern implementation of peer-to-peer video chat using WebRTC, Socket.io, and optimized STUN/TURN configurations for mobile networks (4G/5G).

## 🚀 Live Demo

See the production version in action (works on iOS Safari & Android):
👉 **[Launch VideoChatCouple.com](https://videochatcouple.com)**

## ✨ Features

This architecture solves common WebRTC issues:
- **Mobile-First:** 100% compatible with iOS Safari (15+) and Android Chrome.
- **NAT Traversal:** Handles symmetric NAT on mobile carrier networks (LTE/5G).
- **Zero Latency:** P2P direct connection using optimized ICE candidates.
- **No Registration:** Anonymous signaling flow.

## 🛠 Tech Stack

- **Frontend:** Vanilla JS (Lightweight)
- **Signaling:** Node.js + Socket.io
- **Transport:** WebRTC (UDP/TCP fallback)

## 📱 Mobile Compatibility

Unlike standard WebRTC examples, this implementation handles the `playsinline` policy on iOS and manages connection drops when switching from WiFi to Mobile Data.

## 🔗 Try it out

The best way to test the performance is to try the live platform:
[Start Random Chat](https://videochatcouple.com)

---
*Developed by [Grigoli Carmelo Alessandro]*
