---
title: "Smart Mirror with Magic Mirror OS"  
date: 2025-01-21  
tags: #smart-home #raspberry-pi #iot  
related: [[DIY Projects for Repurposing Old Monitors]]  
---


## Components  
- **Monitor**: 24" 1080p LCD panel  
- **Controller**: Raspberry Pi 4 (4GB)  
- **Software**: [MagicMirror²](https://magicmirror.builders/)  
- **Two-Way Glass**: [OneWayGlass](https://onewayglass.com/) 3mm  

---

## Configuration  
```bash
git clone https://github.com/MichMich/MagicMirror  
cd MagicMirror  
npm install  
```

### Popular Modules  
1. **MMM-GoogleCalendar**: Syncs with Google Calendar.  
2. **MMM-NewsFeed**: Displays RSS headlines.  
3. **MMM-Face-Reco-DNN**: Facial recognition for privacy.  

---

## Cost Breakdown  
| Item                | Cost   | Source |  
|---------------------|--------|--------|  
| Raspberry Pi 4      | $65    | [Canakit](https://www.canakit.com/) |  
| Two-Way Glass       | $120   | [Custom Cut](https://www.onedayglass.com/) |  
| Frame               | $45    | [Etsy Woodworker](https://www.etsy.com/) |  

---

## Advanced Mods  
- **Voice Control**: Integrate Alexa via [MMM-Alexa](https://forum.magicmirror.builders/topic/EXAMPLE).  
- **Touch Layer**: IR frame for interactive UI ([Touché Project](https://www.dfrobot.com/)).  

---

## See Also  
- [[Home Assistant Integration]]  
- [[Gesture Control Systems]]  