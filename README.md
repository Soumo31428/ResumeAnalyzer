
<p><small>Best View in <a href="https://github.com/settings/appearance">Dark Mode</a> (Recommended)</small></p><br/>

<img src="https://socialify.git.ci/Soumo31428/Smart-AI-Resume-Analyzer/image?custom_description=6th+Sem+Final+Year+Project+%282024-2025%29&description=1&font=Bitter&language=1&name=1&pattern=Circuit+Board&stargazers=1&theme=Dark&pattern=Transparent" alt="Smart-AI-Resume-Analyzer" width="1150" />

<div align="center">

#  **🏝️ Smart AI Resume Analyzer 🏝️**  
<!--<img src="https://github.com/user-attachments/assets/8a37c282-efa0-45af-8f37-8e564a62ecd2" width="35">-->
**Your Intelligent Career Partner**  
<img src="https://github.com/user-attachments/assets/76906dbc-343d-4267-ace5-048d428fff42" width="20px"> Smart AI Resume Analyzer is your all-in-one tool to analyze, optimize, and craft resumes that stand out, helping you land your dream job.  
</div>  
  
## <img src="https://github.com/user-attachments/assets/a6e4d77f-56d6-4aa8-8278-0f5a18ef5eb9" width="24px"> **What Makes Us Different?**  

**<img src="https://github.com/user-attachments/assets/76906dbc-343d-4267-ace5-048d428fff42" width="20px"> Next-Level Features for Success:**  
1. 🕵️ **Deep Resume Analysis:**  
   - 🛡️ ATS Compatibility Score  
   - 🔑 Keyword Gap Analysis  
   - 🧩 Role-specific Feedback  
   - 📊 Skills Gap Breakdown  


2. 🤖 **AI Optimization Engine:**  
   - 💡 Keyword Highlighting  
   - ✍️ Content Enhancement Tips  
   - 🌟 Industry-Specific Insights  

**🎉 Why Use Smart Resume AI?**  
Get real-time feedback, boost your resume's impact, and maximize your chances of getting shortlisted—all with a sleek and intuitive interface.  

## <img src="https://github.com/user-attachments/assets/0cefad05-58a9-4aa0-a070-f75a0c9b0353" height="32px">  Tech Stack 
<details>
  <summary>🌐 Frontend</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**Streamlit**](https://streamlit.io/)   | Builds interactive and user-friendly web apps for resume analysis.     |  
| [**HTML**](https://developer.mozilla.org/en-US/docs/Learn/HTML)  | Provides the basic structure for web pages.                             |  
| [**CSS**](https://developer.mozilla.org/en-US/docs/Web/CSS)      | Adds styling and layouts to the frontend.                               |  
| [**JavaScript**](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) | Enables interactivity and dynamic behavior for the web pages.          |  

</details>

<details>
  <summary>⚙️ Backend</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**Streamlit**](https://streamlit.io/)   | Handles backend logic and integrates machine learning models.           |  
| [**Python**](https://www.python.org/)    | Provides core programming language for implementing functionalities.    |  

</details>

<details>
  <summary>🗄️ Database</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**SQLite3**](https://www.sqlite.org/index.html) | Stores and retrieves resume data for efficient processing.             |  

</details>

<details>
  <summary>📦 Modules</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**spaCy**](https://spacy.io/)          | Enhances NLP for keyword analysis and ATS compatibility checks.        |  
| [**Python-docx**](https://python-docx.readthedocs.io/en/latest/)    | Enables Word document editing for resume customization.                |  
| [**PyPDF2**](https://pypdf2.readthedocs.io/en/latest/)         | Processes PDF files for extracting and analyzing resumes.              |  
| [**scikit-learn**](https://scikit-learn.org/)   | Drives machine learning models for resume optimization.                |  
| [**Plotly**](https://plotly.com/)         | Creates interactive charts for skills gap and keyword analysis.        |  
| [**NLTK**](https://www.nltk.org/)         | Provides tools for tokenization, stemming, and text preprocessing in NLP. |  
| [**openpyxl**](https://openpyxl.readthedocs.io/en/stable/)      | Facilitates reading, writing, and modifying Excel files for data visualization and export. |  

</details>

## 💡 **How It Works**  

1. **Upload or Start from Scratch**  
   - Import your resume in **PDF/Word** or create one from scratch with our AI-powered builder.  

2. **Analyze Your Resume**  
   - **ATS Compatibility**: Ensure your resume meets recruiter expectations.  
   - **Keyword Insights**: Find and fill gaps in your content.  
   - **Skills Gap Analysis**: Discover key skills missing for your target role.  

3. **Build a Stunning Resume**  
   - Select from **4 unique templates** and customize sections like skills, achievements, or hobbies.  

4. **Download & Apply**  
   - Export your resume in **PDF** format, ready for submission.  This project has evolved with significant enhancements to its resume analysis capabilities:


Follow these steps to run Smart Resume AI:  

#### **Setup Instructions** 🛠️

Follow the steps below to set up and run the **Smart AI Resume Analyzer** on your local machine.

1. **Clone the repository:**

Open a terminal and run:

   ```bash
   git clone https://github.com/Soumo31428/Smart-AI-Resume-Analyzer.git
   cd Smart-AI-Resume-Analyzer
   ```

2. **Create a Virtual Environment(Optional)**

Set up a virtual environment to manage dependencies:

```bash
python -m venv venv
```

#### **Activate the Virtual Environment:**

- **Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **MacOS & Linux:**
  ```bash
  source venv/bin/activate
  ```

3. **Install dependencies:**

Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the spaCy model:**

Ensure that the necessary NLP model is installed:

   ```bash
   python -m spacy download en_core_web_sm
   ```
   
``Congratulations 🥳😱 your set-up 👆 and installation is finished 🥳😱``


5. **Configure Environment Variables (Mandatory for AI-Analyzer Functionality):**

To enable access to the **Gemini API** used by the AI Resume Analyzer, you need to set up environment variables securely.

#### ✅ Step-by-Step:

1. **Create a `.env` file** inside the `utils/` directory.
2. **Paste your Google Gemini API key** in the following format:

#### 📄 Example content for `utils/.env`:
```env
GOOGLE_API_KEY=your_google_gemini_api_key
```

#### <img src="https://assets.codepen.io/1468070/Google+G+Icon.png" alt="Google LOGO" width="1.6%" /> Get your Gemini API Key:
Visit  **[Google AI Studio – Gemini API Access](https://aistudio.google.com/app/apikey)** 👉 Grab and use your **own API key** — Since Mine One Have Usage Limits.


6. **Run the application:**

Start the application using Streamlit:

   ```bash
   streamlit run app.py
   ```

<!--### Deploy to Streamlit Cloud

1. Push your code to GitHub
2. Sign up for [Streamlit Cloud](https://streamlit.io/cloud)
3. Create a new app and connect it to your GitHub repository
4. Add your API keys as secrets in the Streamlit Cloud dashboard
5. Deploy the app

### Deploy with Docker

1. Build the Docker image:
   ```bash
   docker build -t smart-resume-analyzer .
   ```

2. Run the container:
   ```bash
   docker run -p 8501:8501 -e GOOGLE_API_KEY=your_key smart-resume-analyzer
   ```

## Project Structure

```
Smart-AI-Resume-Analyzer/
├── app.py                  # Main application file
├── config/                 # Configuration files
│   ├── courses.py          # Course recommendations
│   ├── database.py         # Database operations
│   └── job_roles.py        # Job role definitions
├── dashboard/              # Dashboard components
├── feedback/               # Feedback system
├── jobs/                   # Job search functionality
├── static/                 # Static assets
│   ├── css/                # CSS files
│   └── images/             # Image files
├── style/                  # Style definitions
├── templates/              # Resume templates
├── ui_components/          # UI components
├── utils/                  # Utility functions
│   ├── ai_resume_analyzer.py  # AI analysis logic
│   ├── resume_analyzer.py     # Standard analysis logic
│   └── resume_builder.py      # Resume builder logic
├── .env                    # Environment variables (not in git)
├── .gitignore              # Git ignore file
├── Dockerfile              # Docker configuration
├── LICENSE                 # License file
├── README.md               # This file
└── requirements.txt        # Python dependencies
```

## Troubleshooting

### Common Issues

1. **PDF Extraction Fails**: Ensure Tesseract OCR is properly installed and in your PATH
2. **API Key Errors**: Verify your API keys in the `.env` file
3. **Missing Dependencies**: Run `pip install -r requirements.txt` again

### Getting Help

If you encounter any issues, please [open an issue](https://github.com/yourusername/Smart-AI-Resume-Analyzer/issues) on GitHub.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
-->  
