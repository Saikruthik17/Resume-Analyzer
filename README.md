AI Resume Critiquer is a Streamlit web application that uses OpenAI's GPT models to provide smart, structured, and actionable feedback on resumes. Simply upload your resume and optionally specify a job role—get instant critique to help you stand out in the job market!


🚀 Features

Upload your resume in PDF or TXT format
Optional input of the target job role for personalized feedback
AI-driven analysis focusing on:
✅ Content clarity and professionalism
✅ Skills presentation and alignment with job requirements
✅ Description of work experience and impact
✅ Suggestions for improving structure, wording, and formatting
Clean, user-friendly interface built with Streamlit

Clone the repository:
```git clone https://github.com/your-username/ai-resume-critiquer.git
cd ai-resume-critiquer```

🧩 Tech Stack

Python
Streamlit - UI framework
PyPDF2 - PDF text extraction
OpenAI API - AI-powered feedback
dotenv - Secure environment variables management

Create and activate a virtual environment:
```python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate```

Set your OpenAI API key:
Create a .env file in the root directory:
```OPENAI_API_KEY=your_openai_api_key_here```

Run the Streamlit app:
```streamlit run app.py```
