# 📄 Easy OCR Tool 

This tool is designed to easily convert images and scanned documents into editable text using Optical Character Recognition (OCR).

Using [fhswf/TrOCR_Math_handwritten](https://huggingface.co/fhswf/TrOCR_Math_handwritten) Model

[🇰🇷 (kr)한국어로 보기](README_kr.md)

### Input
Hand-Written images

![70_miguel](https://github.com/user-attachments/assets/353552f1-6791-48f8-862c-834d8aeeb990)

### Output
```
cos\theta=\frac{x}{\sqrt{x^{2}+y^{2}}}
```

![latex_output](https://github.com/user-attachments/assets/eb36d27a-f247-4848-b922-1b67fb6bee91)

<img src="https://github.com/user-attachments/assets/eb36d27a-f247-4848-b922-1b67fb6bee91" width="400">

### Input
Hand-Written images

![Image](https://github.com/user-attachments/assets/462cd86c-b884-4c60-addd-c6593d1659f1)

### Output

```
e^{i\pi}+1=0.
```
![Image](https://github.com/user-attachments/assets/373f8046-da29-46d4-8e95-c7547c0b5196)

<img src="https://github.com/user-attachments/assets/373f8046-da29-46d4-8e95-c7547c0b5196" width="400">

## ✨ Features
- ✅ Simple drag-and-drop interface.
- 📷 Supports multiple image formats.
- ⚡ Quick and accurate text extraction.

## 🔧 Installation
-MacTex: If you're on macOS, you'll need to install MacTeX.
```
brew install --cask mactex
```
* **Windows:** Install [MiKTeX](https://miktex.org/download) or [TeX Live](https://www.tug.org/texlive/acquire-iso.html). Follow their respective installation guides.

-Python Dependencies
```
pip install torch torchvision torchaudio
```

## 🚀 Getting Started
1. Copy and put your image file path.
2. Click the Run.
3. Download the extracted text!

## Reference
**Model:**

TrOCR_Math_handwritten by fhswf
License: afl-3.0

**Paper:**

Li, M., Lv, T., Cui, L., Lu, Y., Florencio, D., Zhang, C., Li, Z., & Wei, F. (2021).
TrOCR: Transformer-based Optical Character Recognition with Pre-trained Models.
arXiv preprint arXiv:2109.10282.

**BibTeX:**
```
text
@misc{li2021trocr,
  title={TrOCR: Transformer-based Optical Character Recognition with Pre-trained Models},
  author={Minghao Li and Tengchao Lv and Lei Cui and Yijuan Lu and Dinei Florencio and Cha Zhang and Zhoujun Li and Furu Wei},
  year={2021},
  eprint={2109.10282},
  archivePrefix={arXiv},
  primaryClass={cs.CL}
}
```

---

