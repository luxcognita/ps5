# PS5 Remote Bridge

**Goal:**  
Develop an application that enables connecting a PlayStation 5 to a computer over the network, enabling high-quality, low-latency streaming and control, without the need for a capture card.

## Features
- Connect to PS5 using the Remote Play protocol (or similar).
- Stream video and audio from PS5 to PC.
- Relay controller input from PC to PS5.
- Cross-platform support (Windows, Linux, macOS).
- Optimized for low latency and high performance.

## Optimization Strategies
- Use efficient codecs and hardware acceleration (when available).
- Minimize network round-trip time; prefer wired connections.
- Efficient buffering and adaptive bitrate.
- Prioritize real-time data over reliability when appropriate (e.g., UDP streaming).
- Profile and optimize CPU and memory usage.

## Architecture Overview
See [docs/architecture.md](docs/architecture.md) for details.

## References & Inspiration
- [Chiaki (open source PS Remote Play)](https://github.com/thestr4ng3r/chiaki)
- [Sony Remote Play](https://www.playstation.com/en-us/remote-play/)
