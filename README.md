# AraBrailleNet - An End-to-End Arabic Braille Recognition System

An end-to-end deep learning–based system for **Arabic Braille detection, recognition, and sentence reconstruction**, designed to support accessible reading for visually impaired users.  


## ✨ Highlights
- 45-class Arabic Braille recognition (letters, diacritics, ligatures)
- Robust to noise, skew, and spacing variations
- Right-to-left Arabic sentence reconstruction
- **95.76% accuracy**
- Real-time inference (~25 FPS on GPU)

---

## 🧠 Pipeline
1. **YOLOv8** detects Braille cells  
2. IoU filtering + adaptive grid formation  
3. CNN classifies each cell  
4. Post-processing reconstructs valid Arabic text  

---

## 📊 Performance
- **Accuracy:** 95.76%  
- **GPU:** ~25 FPS (real-time)  
- **CPU:** ~2 FPS (offline)  

---

## 🗂️ Dataset
- Extended Arabic Braille Grade-1 dataset  
- **45 balanced classes** including diacritics & ligatures  

---

## 🖼️ Output
- Detected Braille cells  
- Recognized Arabic characters  
- Fully reconstructed Arabic sentence  


![AraBrailleNet Output](https://github.com/ashfaq099/Arabraille/blob/master/Assets/Figure%204.jpg)

---

## 📌 Note

This work was presented at the **28th International Conference on Computer and Information Technology (ICCIT 2025)**.  
The source code is currently **private**, and the **full implementation will be released after the official publication**.
