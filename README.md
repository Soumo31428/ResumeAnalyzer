# Smart Resume Analyzer

[![Made with Python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/)

An intelligent resume analysis application built with Streamlit that provides comprehensive resume evaluation, skill recommendations, and career guidance.

## 🚀 Features

- **Resume Analysis**: Upload PDF resumes for comprehensive analysis
- **Skill Detection**: Intelligent skill extraction and recommendations
- **Career Guidance**: Personalized career field predictions
- **Course Recommendations**: Curated learning resources based on skills
- **Resume Scoring**: Detailed scoring with improvement suggestions
- **Admin Dashboard**: Analytics and user data management
- **Video Resources**: Educational content for resume writing and interviews

## 🛠️ Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python 3.11
- **Database**: SQLite3
- **NLP**: spaCy, NLTK
- **Data Processing**: Pandas, NumPy
- **PDF Processing**: pdfminer3
- **Visualization**: Plotly
- **UI Components**: streamlit-tags, Pillow

## 📋 Prerequisites

- Python 3.11 or higher
- pip package manager

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Soumo31428/ResumeAnalyzer.git
   cd ResumeAnalyzer
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download spaCy language model**
   ```bash
   python -m spacy download en_core_web_sm
   ```

4. **Run the application**
   ```bash
   streamlit run App.py
   ```

5. **Access the application**
   - Open your browser and go to `http://localhost:8501`

## 💻 Usage

### For Users
1. Upload your resume in PDF format
2. View comprehensive analysis including:
   - Basic information extraction
   - Skills analysis and recommendations
   - Resume scoring and improvement tips
   - Career field predictions
   - Relevant course suggestions
   - Educational video resources

### For Administrators
- Username: `machine_learning_hub`
- Password: `mlhub123`
- Access analytics, user data, and generate reports

## 📊 Key Improvements

This version includes several enhancements over the original:

- ✅ **SQLite3 Integration**: No MySQL server setup required
- ✅ **Custom Resume Parser**: Reliable parsing without external API dependencies
- ✅ **Enhanced Compatibility**: Fixed spaCy and NumPy version conflicts
- ✅ **Robust Error Handling**: Comprehensive safety checks and user feedback
- ✅ **Modern Dependencies**: Updated to work with Python 3.11
- ✅ **Simplified Setup**: Zero-configuration database and streamlined installation

## 🎯 Skill Detection

The application can detect skills across multiple domains:
- Programming Languages (Python, JavaScript, Java, etc.)
- Web Technologies (React, Angular, Django, etc.)
- Databases (MySQL, MongoDB, PostgreSQL, etc.)
- Cloud Platforms (AWS, Azure, GCP)
- DevOps Tools (Docker, Kubernetes, Jenkins)
- Data Science (Machine Learning, TensorFlow, etc.)
- Design Tools (Photoshop, Figma, Adobe XD)

## 📁 Project Structure

```
ResumeAnalyzer/
├── App.py                 # Main application file
├── Courses.py            # Course recommendations data
├── requirements.txt      # Python dependencies
├── README.md            # Project documentation
├── .gitignore           # Git ignore file
├── Logo/                # Application logos
├── Uploaded_Resumes/    # Sample resume files
└── resume_analyzer.db   # SQLite database (created automatically)
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with Streamlit for the amazing web framework
- spaCy for natural language processing capabilities
- The open source community for various libraries used

---

**Developed by Soumo31428** 🚀