# Chroma Frame AR

An interactive augmented reality web application using MediaPipe Hand Tracking to create real-time stylized camera effects.

## Features

- **Double-Triangle / L-Frame Detection**: Tracks index fingers and thumbs across both hands. When fingers are aligned, it creates an framing box; flipping one hand upside down transforms it into an hourglass/double-triangle shape.
- **Retro Halftone Duotone Effect**: Clips a high-contrast mustard yellow base with deep indigo blue halftone dots inside the hand-formed frame.
- **Enhanced Camera Background**: Live camera stream rendered with vibrant saturation and contrast.
- **Smart Fit / Fill Modes**: 
  - `FIT`: Shows the full, uncropped camera view with zero zoom on mobile devices, complete with ambient blurred margins.
  - `FILL`: Expands edge-to-edge for borderless full-screen experience.
- **Mobile Responsive & Fullscreen**: Touch-optimized controls with notch safe-area support and full-screen toggle.

## Tech Stack

- HTML5 Canvas & Web API
- MediaPipe Hands
- WebRTC `getUserMedia`
