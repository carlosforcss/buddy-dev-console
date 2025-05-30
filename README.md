# Buddy Development Console

## Overview
Buddy is an AI-powered voice assistant specifically designed for the low vision and blind community. This development console provides a real-time interface for testing and monitoring Buddy's voice interactions, making it easier for developers to debug and improve the assistant's capabilities.

## Purpose
The Buddy project aims to create a more accessible digital world by providing a voice-first interface that understands and responds to users' needs naturally and efficiently. This development console is a crucial tool for:
- Testing voice interactions in real-time
- Monitoring WebSocket connections
- Debugging audio processing
- Analyzing AI responses
- Ensuring high-quality voice output

## Technologies Used

### Frontend
- **HTML5/CSS3** - Modern, semantic markup with advanced CSS features
- **JavaScript** - Pure vanilla JavaScript for optimal performance
- **Web Audio API** - For high-quality audio processing and playback
- **WebSocket** - Real-time bidirectional communication
- **CSS Grid/Flexbox** - Responsive and accessible layout
- **Backdrop Filter** - Modern glass-morphism UI effects

### Audio Processing
- **PCM Audio** - 16-bit audio processing
- **Sample Rate Control** - Dynamic audio playback speed adjustment
- **Float32 Audio Processing** - High-precision audio manipulation
- **MediaRecorder API** - Native browser audio recording

### Real-time Communication
- **WebSocket Protocol** - Enables real-time voice streaming
- **Binary Data Transfer** - Efficient audio chunk transmission
- **JSON Message Format** - Structured data exchange

## Features

### Voice Recording
- One-click voice recording activation
- Real-time audio streaming
- PCM 16-bit audio capture
- Automatic silence detection

### Audio Playback
- Adaptive playback speed control
- Chunk-based audio processing
- Seamless audio streaming
- Buffer management for smooth playback

### Development Tools
- Real-time console logging
- Connection status monitoring
- Audio processing visualization
- Error tracking and reporting

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/buddy_test_console.git
```

2. Navigate to the project directory:
```bash
cd buddy_test_console
```

3. Start a local server (e.g., using Python):
```bash
python -m http.server 8000
```

4. Open your browser and navigate to:
```
http://localhost:8000
```

## Usage

1. **Connection Status**
   - Green dot indicates active WebSocket connection
   - Status text shows current state

2. **Voice Recording**
   - Click the microphone button to start recording
   - Click again to stop and send audio
   - Visual feedback shows recording state

3. **Console Output**
   - Color-coded message types
   - JSON formatting for structured data
   - Timestamps for all events
   - Clear button for console cleanup

## Accessibility Features

The console itself is designed with accessibility in mind:
- High contrast UI elements
- Clear visual feedback
- Keyboard navigation support
- Screen reader compatible
- Semantic HTML structure

## Contributing

We welcome contributions to make Buddy more accessible and useful for the low vision and blind community. Please feel free to:
- Report issues
- Suggest features
- Submit pull requests
- Improve documentation

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions, suggestions, or collaboration opportunities, please reach out to:
[Your Contact Information]

---

**Note**: This console is part of the larger Buddy AI Assistant ecosystem, designed to make technology more accessible for everyone. 