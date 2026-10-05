# A Comprehensive System for Arabic Braille Interpretation

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
- **Character Recognition Accuracy:** 95.76%  
- **GPU:** ~25 FPS (real-time)  
- **CPU:** ~2 FPS (offline)  

---

## 🗂️ Dataset
- Extended Arabic Braille Grade-1 dataset  
- **45 balanced classes** including diacritics & ligatures  
- The extended dataset can be found [Kaggle dataset](https://www.kaggle.com/datasets/ashfaq099/arabic-braille-dataset-extended)

---

## 🖼️ Output
- Detected Braille cells  
- Recognized Arabic characters  
- Fully reconstructed Arabic sentence  


![AraBrailleNet Output](https://github.com/ashfaq099/Arabraille/blob/master/Assets/Figure%204.jpg)

---

## 📖 Citation

If you use this code, dataset, or results in your work, please cite our paper:

**A. Rahman and M. S. Sadi**, "A Comprehensive System for Arabic Braille Interpretation," *2025 28th International Conference on Computer and Information Technology (ICCIT)*, Cox's Bazar, Bangladesh, 2025, pp. 2992–2997. [doi: 10.1109/ICCIT68739.2025.11491613](https://doi.org/10.1109/ICCIT68739.2025.11491613)

**BibTeX**

```bibtex
@inproceedings{rahman2025arabraillenet,
  author    = {Rahman, Ashfaqur and Sadi, Muhammad Sheikh},
  title     = {A Comprehensive System for Arabic Braille Interpretation},
  booktitle = {2025 28th International Conference on Computer and Information Technology (ICCIT)},
  address   = {Cox's Bazar, Bangladesh},
  year      = {2025},
  pages     = {2992--2997},
  publisher = {IEEE},
  doi       = {10.1109/ICCIT68739.2025.11491613}
}
```
