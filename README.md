# Plagiarism-Detection-System
🎨 Frontend (Standalone Web App)
A fully interactive, glassmorphism-designed single-page application with:
Drag & drop file upload (TXT, PDF, DOCX, HTML, CSV)
4 Detection Modes: Standard, Deep AI, Semantic, Paraphrase
Real-time text comparison (Side-by-side + Diff view)
Animated similarity gauge with color-coded risk levels
Interactive charts (Chart.js) for distribution & source analysis
Scan history with localStorage persistence
PDF export using jsPDF
Responsive design with dark theme & gradient animations
🐍 Backend (Flask API)
A robust Python backend featuring:
5 Detection Algorithms: Jaccard, Cosine (TF-IDF), Sequence Matching, N-gram, Semantic Analysis
RESTful API with 8 endpoints (/api/detect, /api/compare, /api/batch, etc.)
Multi-format file parsing (PDF, DOCX, HTML, CSV, TXT)
Configurable thresholds & detection settings
Health checks, stats, and report generation
Full test suite with pytest
🐙 GitHub Repository Description
A comprehensive README.md with badges, feature comparisons, installation guides, API docs, algorithm explanations, screenshots, Docker deployment, and contribution guidelines.
📥 Download Your Files
Table
File	Description	Link
plagiarism_system.html	Complete frontend application	Download
app.py	Flask backend with detection engine	Download
config.py	Application configuration	Download
utils.py	Helper utilities	Download
requirements.txt	Python dependencies	Download
README.md	GitHub repo description & docs	Download
Dockerfile	Container build file	Download
docker-compose.yml	Docker orchestration	Download
test_app.py	Unit tests	Download
.gitignore	Git ignore rules	Download
LICENSE	MIT License	Download
🚀 Quick Start
bash
Copy
# 1. Install dependencies
pip install flask flask-cors nltk scikit-learn numpy PyPDF2 python-docx

# 2. Download NLTK data
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"

# 3. Run the backend
python app.py

# 4. Open plagiarism_system.html in your browser
# The frontend works standalone OR connect it to the Flask API
The HTML frontend is fully functional standalone — it simulates detection with realistic algorithms. For production use, wire it to the Flask backend by updating the API calls in the JavaScript.

for more contact (professorshami435@gmail.com)
