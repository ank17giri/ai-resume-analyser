# AI Resume Analyzer

An AI-powered resume analysis tool that evaluates a candidate's resume against a job description and provides useful insights to improve the resume's relevance and quality.

## Project Overview

Recruiters often receive a large number of resumes for a single position. Manually comparing resumes with job descriptions can be time-consuming.

This project aims to automate part of this process by analyzing the content of a resume, comparing it with the requirements of a job description, identifying relevant skills, and providing recommendations for improvement.

The project was developed using Python and machine learning/NLP techniques and can be further extended into a web-based application.

## Key Features

* Resume text extraction and preprocessing
* Job description analysis
* Skill extraction
* Resume and job description matching
* Identification of matching and missing skills
* Resume relevance analysis
* Suggestions for improving the resume
* Similarity-based scoring
* Easy-to-use analysis workflow

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* Regular Expressions
* Google Colab
* Jupyter Notebook

## Project Workflow

```text
Resume
   |
   v
Text Extraction
   |
   v
Text Preprocessing
   |
   v
Skill Extraction
   |
   v
Job Description Analysis
   |
   v
Resume-Job Matching
   |
   v
Similarity Score
   |
   v
Missing Skills & Recommendations
```

## How It Works

### 1. Resume Input

The user provides a resume as input.

### 2. Text Processing

The resume content is extracted and processed to remove unnecessary elements and prepare the text for analysis.

### 3. Job Description Analysis

The job description is analyzed to identify important skills, keywords, and requirements.

### 4. Resume Matching

The system compares the resume with the job description and calculates how closely the candidate's profile matches the job requirements.

### 5. Skill Gap Analysis

The system identifies skills that are present in the resume as well as important skills that are missing.

### 6. Recommendations

Based on the analysis, the system provides suggestions that can help improve the resume's relevance to the target position.

## Example Use Case

A candidate applying for a Data Scientist position can provide:

* Their resume
* The Data Scientist job description

The system analyzes both documents and provides information such as:

```text
Resume Match Score: 78%

Matching Skills:
- Python
- Pandas
- NumPy
- Machine Learning
- SQL
- Scikit-learn

Missing or Less Relevant Skills:
- Deep Learning
- Power BI
- Docker

Recommendations:
- Add relevant machine learning projects
- Highlight SQL experience
- Mention model deployment experience
```

The exact results depend on the resume and job description provided to the system.

## Project Structure

```text
ai-resume-analyzer/
│
├── Ai_resume_analyser.ipynb
├── README.md
└── .gitignore
```

## Running the Project

The project was developed in Google Colab.

To run the project:

1. Clone or download this repository.
2. Open `Ai_resume_analyser.ipynb` using Google Colab or Jupyter Notebook.
3. Install the required Python libraries if they are not already available.
4. Run the notebook cells sequentially.
5. Provide the required resume and job description inputs.
6. Review the generated analysis and recommendations.

## Future Improvements

The current project can be extended with several additional features:

* Build a complete Streamlit web application
* Add support for PDF and DOCX resumes
* Improve skill extraction using NLP models
* Add semantic similarity using sentence embeddings
* Integrate a Large Language Model for personalized recommendations
* Add resume section-wise scoring
* Add ATS keyword analysis
* Deploy the application online
* Add authentication and user history
* Improve model evaluation using a labeled dataset

## Learning Outcomes

Through this project, I worked with:

* Text preprocessing
* Natural Language Processing
* Feature extraction
* Similarity-based machine learning
* Resume and job description analysis
* Python data processing
* Machine learning workflows
* Practical application development

## Author

**Ankit Giri**

This project was developed as part of my learning and portfolio development in Data Science and Artificial Intelligence.
