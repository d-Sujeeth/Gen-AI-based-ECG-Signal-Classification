# ECG Analyzer - AI-powered ECG Analysis Tool

ECG Analyzer is an AI-driven platform designed to automate the analysis of ECG images, generate detailed medical reports, and assist healthcare professionals in diagnosing cardiac conditions efficiently and accurately. This tool leverages Google’s Generative AI model to interpret ECG images and provide actionable insights.

---

## Features

- **ECG Image Upload:** Upload ECG images in PNG, JPG, or JPEG formats.
- **AI-powered ECG Analysis:** Automated analysis of ECG images to identify patterns and abnormalities.
- **Report Generation:** Generate a comprehensive ECG report including patient details, findings, and interpretation.
- **Downloadable Report:** Download the ECG report as a Word document for further review or sharing.
- **User-friendly Interface:** Simple and intuitive web interface for seamless interaction.

---

## Installation

### Requirements
- Python 3.x
- Streamlit
- Pillow
- python-docx
- google-generativeai

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecg-analyzer.git
   cd ecg-analyzer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up Google API keys:
   - Obtain an API key from Google Cloud and set it as an environment variable:
     ```bash
     export GEMINI_API_KEY=your_api_key_here
     ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Upload an ECG image.
2. Click "Generate ECG Report."
3. View the AI-generated analysis.
4. Download the generated ECG report as a Word document.
