# Image-analysis-and-captioning
This repository contains the code for an image captioning model using the VisionEncoderDecoderModel from the transformers library, specifically the ViT-GPT2 model. The model is trained to generate descriptive captions for images.


## 🧪 How to Run the Project

1. **Clone the repo**
```bash
git clone https://github.com/Drishti-Mishra/Image-Analysis-and-Captioning-System.git
cd Image_caption-main

env\Scripts\activate     # For Windows
# OR
source env/bin/activate  # For Linux/macOS

pip install -r requirements.txt

streamlit run app.py

uvicorn api:app --host 127.0.0.1 --port 8000

Image_caption-main/
├── app.py # Streamlit frontend
├── api.py # FastAPI backend
├── model/ # Pretrained or trained model files
├── env/ # Python virtual environment
├── utils/ # Image processing and helper functions
├── data/ # Sample images or Kaggle dataset
└── requirements.txt # Python dependencies




