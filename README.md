# Mario Kart DS - Webcam Edition

Play Mario Kart DS with your hands or your phone! 🏎️💨

## Features
- **Webcam Gesture Control** - Steer using hand movements detected by OpenCV/MediaPipe
- **Phone Touch Controller** - On-screen touch controls for continuous gameplay
- **4-Player Local Multiplayer** - Play with friends in local multiplayer mode
- **melonDS Fork** - Based on the official melonDS Nintendo DS emulator

## How It Works
1. Open your hand near the camera - the tracker locks on
2. Move your hand left/right to steer
3. Use phone touch controls for acceleration/braking
4. Race against AI or friends in multiplayer mode

## Controls
- **Hand Gestures**: Steering (left/right)
- **Phone Touch**: Accelerate, Brake, Item buttons

## Installation
```bash
# Clone the submodule
git submodule update --init --recursive

# Install dependencies
pip install -r requirements.txt

# Run
python main.py
```

## Building from Source
```bash
# Build the melonDS fork
# Follow instructions in the repository

# Or build the webcam controller
make build
```

## Playing
1. Start the application
2. Open your hand near the camera
3. Select race mode
4. Start racing! 🏁

## License
GPL-3.0 - See LICENSE file for details.

## Acknowledgements
- [melonDS](https://github.com/melonDS-emu/melonDS) - Nintendo DS emulator
- [OpenCV](https://opencv.org/) - Computer vision library
- [MediaPipe](https://mediapipe.dev/) - Hand tracking solution
