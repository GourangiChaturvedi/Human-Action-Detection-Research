# Non-Verbal Human Action Detecting Machine

## 📌 Project Overview
This project is a research prototype developed to explore the intersection of Computer Vision and Human-Computer Interaction (HCI). The goal is to detect and interpret human gestures in real-time, providing a foundation for non-verbal communication between humans and machines.

## 🛠️ System Architecture & Logic
The project utilizes a structured pipeline to transform raw video input into actionable gesture data. 

### Implementation Flowchart:
```mermaid
graph TD
    A[Webcam Video Input] --> B[Frame Pre-processing & RGB Conversion]
    B --> C[Mediapipe Holistic Landmark Detection]
    C --> D[Spatial Coordinate Mapping - 33 Points]
    D --> E[Custom Gesture Recognition Logic]
    E --> F[Real-time Visual Feedback & Output]
