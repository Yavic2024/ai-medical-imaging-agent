# AI Medical Imaging Agent

This project is a Streamlit-based AI agent for analyzing medical images (X-ray, MRI, CT, Ultrasound, etc.) using advanced computer vision and radiological expertise. It integrates Google Gemini models and DuckDuckGo search to generate comprehensive, structured, and patient-friendly diagnostic reports.

---

## Features

- **Secure API Key Management:** Enter and manage your Google API key securely in the sidebar.
- **Image Upload:** Supports JPG, JPEG, PNG, and DICOM formats.
- **Automated Medical Analysis:** Uses a large language model to analyze uploaded images and generate detailed, structured reports.
- **Research Integration:** Fetches recent medical literature and treatment protocols using DuckDuckGo search.
- **Patient-Friendly Explanations:** Provides clear, jargon-free summaries for patients.
- **Educational Use:** Designed for informational and educational purposes only.

---

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Yavic2024/ai-medical-imaging-agent.git
   cd ai_medical_imaging_agent
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **(Optional) Install DICOM support:**
   - For DICOM images, you may need additional libraries such as `pydicom`.

---

## Usage

1. **Run the Streamlit app:**
   ```sh
   streamlit run ai_medical_imaging.py
   ```

2. **Configure API Key:**
   - Enter your Google API key in the sidebar (get one from [Google AI Studio](https://aistudio.google.com/apikey)).

3. **Upload a Medical Image:**
   - Supported formats: JPG, JPEG, PNG, DICOM.

4. **Analyze:**
   - Click "Analyze Image" to receive a detailed diagnostic report, including:
     - Image type & region
     - Key findings
     - Diagnostic assessment
     - Patient-friendly explanation
     - Research context with references

---

## File Structure

- `ai_medical_imaging.py` — Main Streamlit application.
- `requirements.txt` — Python dependencies.

---

## Disclaimer

> ⚠ **DISCLAIMER:** This tool is for educational and informational purposes only. All analyses should be reviewed by qualified healthcare professionals. Do not make medical decisions based solely on this analysis.

---

## License

This project is provided for educational use. See [LICENSE](LICENSE) if present.

---

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [Google Generative AI](https://aistudio.google.com/)
- [DuckDuckGo Search](https://duckduckgo.com/)
- [Agno AI](https://pypi.org/project/agno/)

---

*For questions or contributions, please open an issue
