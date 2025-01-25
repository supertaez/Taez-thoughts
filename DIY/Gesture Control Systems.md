---
title: "Gesture Control Systems"  
date: 2025-01-21  
tags: #iot #automation #sensors  
related: [[Smart Mirror with Magic Mirror OS]]  
---

## Sensor Types  
1. **Infrared (IR)**:  
   - HC-SR501 PIR motion detector ($2.50).  
   - Range: 7m | Latency: 1–2s.  

2. **ToF (Time-of-Flight)**:  
   - VL53L0X ($15) for precise hand tracking.  
   - Integrates with Raspberry Pi via I²C.  

---

## Software Integration  
- **OpenCV**: Hand landmark detection ([MediaPipe](https://google.github.io/mediapipe/)).  
- **Magic Mirror**: [MMM-Gestures Plugin](https://github.com/EXAMPLE).  

---

## Use Cases  
- **Smart Mirror**: Swipe to cycle widgets.  
- **Digital Art Frame**: Wave to pause slideshow.  

---

## See Also  
- [[Home Assistant Integration]] (automation rules)  
- [[Raspberry Pi Power Management]] (sensor power draw)  