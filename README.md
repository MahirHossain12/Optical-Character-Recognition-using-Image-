# 🖼️ Optical Character Recognition (OCR) using Tesseract & OpenCV

This project demonstrates how to extract text from images using **Tesseract OCR** along with **OpenCV** for image preprocessing. It aims to improve OCR accuracy by cleaning and preparing the image before passing it to the OCR engine. It can be used for automating tasks such as digitizing documents, extracting information from forms, or reading printed signs.

---

## 🚀 Key Features

* Extract text from images using Tesseract OCR
* Download and use custom `.traineddata` language models (e.g., Indic script support)
* Preprocess images using OpenCV (grayscale, thresholding, denoising)
* Live image input and flexible file handling
* Easy to adapt for handwritten text, receipts, forms, or printed materials

---

## 🖥️ Technologies Used

* Python 3.x
* OpenCV
* PyTesseract (Python wrapper for Tesseract OCR)
* Requests
* Jupyter Notebook

---

## 🧪 Getting Started

1. **Clone the Repository**
   Download or clone this repository to your local machine.

2. **Install Required Libraries**
   Install Python dependencies using pip:

   ```
   pip install opencv-python pytesseract requests
   ```

3. **Install Tesseract OCR Engine**

   * On **Windows**, download and install from: [https://github.com/tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract)
   * On **Linux (Ubuntu/Debian)**, run:

     ```
     sudo apt install tesseract-ocr
     ```

4. **Run the Jupyter Notebook**
   Open the notebook file `Optical_Character_Recognition_using_Image.ipynb` using Jupyter Notebook or Google Colab and execute the cells step by step.

---

## 📸 Example Output

You can use any image with printed or typed text. The notebook will output recognized text and show preprocessed images.

Example image:

```
[Insert sample input image in the images/ folder]
```

Recognized text:

```
[The text detected from the image will be printed in the output cell]
```

---

## ✍️ Author

* **Mahir Hossain** – [GitHub Profile](https://github.com/MahirHossain12)
---

## 📃 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 📌 Notes

* Make sure the Tesseract engine is installed and its path is configured correctly in your environment.
* Additional `.traineddata` models for different languages can be downloaded from [Tesseract tessdata GitHub](https://github.com/tesseract-ocr/tessdata).

---
