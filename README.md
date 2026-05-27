# Kinetic Command: Real-Time Gesture-Based Hand Rehabilitation System

A real-time, webcam-only hand rehabilitation system that converts therapeutic exercises into gamified interactive tasks using computer vision.

## Research Paper
This project is based on the IEEE paper:
> *Kinetic Command: A Real-Time, Gesture-Based System for Gamified Hand Rehabilitation Using MediaPipe and OpenCV*
> Caroline Micheal Manjari, Sajani Sunil Dengle, Debjit Das
> M.Sc. Data Science, VIT Chennai

## Overview
Hand rehabilitation is critical for recovery from neurological and musculoskeletal conditions. Traditional methods lack real-time feedback and engagement. Kinetic Command addresses this using MediaPipe hand landmark detection and a gamified feedback loop.

## Exercises Supported (6)
| # | Exercise | Description |
|---|----------|-------------|
| 1 | Hand Open/Close | Measures fingertip-wrist distance |
| 2 | Wrist Flex/Extend | Tracks wrist joint angle |
| 3 | Finger Spread | Measures inter-finger distance |
| 4 | Thumb Opposition | Thumb tip to each finger sequentially |
| 5 | Wrist Deviation | Radial/ulnar wrist movement |
| 6 | Index Tap | Index finger lift and tap |

## Key Results
- **~30 FPS** real-time performance on CPU-only laptop
- **92.6% average** repetition detection accuracy
- **33ms** end-to-end latency
- **~60-70% reduction** in false triggers via hold-timer hysteresis

## Tech Stack
- **Language**: Python 3.10
- **Libraries**: MediaPipe, OpenCV, NumPy
- **Techniques**: Hand Landmark Detection, State Machine, Computer Vision, Gamification

## How to Run

```bash
git clone https://github.com/Das-Debjit/Kinetic-Command.git
cd Kinetic-Command
pip install -r requirements.txt
python rehab_app.py
```

## Controls
| Key | Action |
|-----|--------|
| `1-6` | Switch exercise |
| `+` / `=` | Increase threshold difficulty |
| `-` | Decrease threshold difficulty |
| `q` | Quit |

## System Requirements
- Python 3.8+
- Webcam (720p recommended)
- CPU only — no GPU required

## Team
| Name | GitHub |
|------|--------|
| Debjit Das | [Das-Debjit](https://github.com/Das-Debjit) |
| Sajani Dengle | [sajanidengle](https://github.com/sajanidengle) |
| Caroline Manjari | [caroline-18](https://github.com/caroline-18) |

## Author Contact
**Debjit Das**
🔗 [GitHub](https://github.com/Das-Debjit)
🔗 [LinkedIn](https://www.linkedin.com/in/debjitdas82/)