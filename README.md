# skwill_project_2
A Streamlit-based web application for recording user video responses. Users can record themselves answering questions, review their recording, and submit. Videos are stored in Google Drive (prototype) and later moved to DigitalOcean Spaces.
# Video Response WebApp 🎥

A prototype web application for recording and collecting user video responses.  
Built with [Streamlit](https://streamlit.io/) and [streamlit-webrtc](https://github.com/whitphx/streamlit-webrtc).

---

## 📌 Features
- Instruction page with pose, lighting, and audio setup tips
- Video recording directly in the browser
- Review and re-record option
- Upload recordings to Google Drive (prototype)  
- Scalable to DigitalOcean Spaces in future versions

---

## 🚀 Tech Stack
- **Frontend**: Streamlit
- **Video**: streamlit-webrtc
- **Storage**: Google Drive API (PyDrive2), later DigitalOcean Spaces
- **Optional Enhancements**: OpenCV for pose & lighting checks

---

## 🛠️ Getting Started

### Prerequisites
- Python 3.9+
- A Google Cloud project with Drive API enabled (for upload)
- Streamlit installed

### Installation
```bash
# Clone the repo
git clone https://github.com/YOUR-ORG/video-response-webapp.git
cd video-response-webapp

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

