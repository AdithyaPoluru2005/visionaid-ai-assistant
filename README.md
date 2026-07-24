# visionaid-ai-assistant
AI-powered OCR and multilingual Text-to-Speech assistant that extracts key information from printed documents to help visually impaired users.
# 🦯 VisionAid - AI-Powered Document Reader for the Visually Impaired

VisionAid is an AI-powered accessibility application that helps visually impaired and illiterate users understand printed documents. Using Optical Character Recognition (OCR), Natural Language Processing (NLP), and Text-to-Speech (TTS), the application extracts meaningful information from documents and reads it aloud in multiple languages.

---

## ✨ Features

- 📄 Extract text from printed documents using OCR
- 🧠 Automatically identify key information such as:
  - Dates
  - Amounts
  - Medicines
  - Dosage Instructions
  - Prices
- 🔊 Convert extracted information into natural speech
- 🌐 Supports multiple languages:
  - English
  - Hindi
  - Telugu
  - Tamil
  - Odia
- 🖥️ Interactive Streamlit web interface
- ⬇️ Download generated audio as MP3

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Framework
- Streamlit

### OCR
- Tesseract OCR
- pytesseract

### Natural Language Processing
- spaCy

### Text-to-Speech
- Google Text-to-Speech (gTTS)

### Image Processing
- Pillow (PIL)

### Other Libraries
- Regular Expressions (re)
- io

---

## 📂 Project Structure

```
visionaid-ai-assistant/
│
├── app.py
├── requirements.txt
├── README.md
├── images/
│   ├── home.png
│   ├── uploaded_document.png
│   └── output.png
├── audio/
│   └── sample_output.mp3
└── sample_documents/
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/visionaid-ai-assistant.git

cd visionaid-ai-assistant
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Install spaCy Model

```bash
python -m spacy download en_core_web_sm
```

### Run Application

```bash
streamlit run app.py
```

---

## 📋 How It Works

1. Upload an image of a printed document.
2. OCR extracts the text.
3. The application cleans and processes the text.
4. NLP identifies important entities such as medicines, dates, and prices.
5. Text-to-Speech converts the extracted information into audio.
6. Users can listen to or download the generated speech.

---

## 🌍 Supported Documents

- Medical Prescriptions
- Bills
- Product Labels
- Receipts
- Printed Notices
- Educational Documents

---

## 🎯 Key Functionalities

- OCR Text Extraction
- Text Cleaning
- Named Entity Recognition
- Information Extraction
- Multilingual Speech Generation
- Audio Download

---

## 🔮 Future Enhancements

- Handwritten document recognition
- Real-time camera scanning
- Offline speech synthesis
- Mobile application
- AI-powered document summarization
- QR code detection
- Currency recognition
- Voice commands

---

## 👨‍💻 Developer

**P. Adithya**

---

## 📜 License

This project is intended for educational and research purposes.
