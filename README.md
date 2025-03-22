# AI-Powered Resume Screening and Ranking System

## Overview
This project is an AI-powered resume screening and ranking system that extracts text from PDF resumes, compares them with job descriptions using **TF-IDF Vectorization** and **cosine similarity**, and ranks resumes based on relevance scores. The system is implemented using **Streamlit**.

## Features
- Upload and process multiple PDF resumes.
- Extract text using **PyPDF2**.
- Vectorize resumes and job descriptions using **TF-IDF**.
- Compute similarity scores using **cosine similarity**.
- Display ranked resumes based on relevance.

## Tech Stack
- **Backend:** Python
- **Frontend:** Streamlit
- **Libraries:**
  - `PyPDF2` (PDF text extraction)
  - `scikit-learn` (TF-IDF and cosine similarity)
  - `pandas` (data handling)
  - `streamlit` (UI framework)

## Installation

### Step 1: Clone the Repository
```
git clone <repository_link>
cd AI_Resume_Ranking
```

### Step 2: Create a Virtual Environment (Optional but Recommended)
```
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### Step 3: Install Dependencies
If you have `requirements.txt`, run:
```
pip install -r requirements.txt
```

If not, manually install dependencies:
```
pip install PyPDF2 scikit-learn pandas streamlit
```


## Usage
1. Run the Streamlit app:
  ```
   streamlit run app.py
   ```

2. Enter a job description and Upload resumes.
3. View ranked resumes based on relevance.

## Folder Structure

```
AI_Resume_Ranking/
│── app.py               # Main Streamlit app
│── requirements.txt      # Dependencies
│── data/                # Sample resumes
│── models/              # Trained models (if any)
│── README.md            # Project documentation
```

## Screenshots
![resumeranking](output/Screenshot 1)
![resumeranking](output/Screenshot 2)
![resumeranking](output/Screenshot 3)

## Contributors
- **Saomya Chaudhury** (Supervisor/Mentor)
- **Pavan Kumar** (Program Manager)
- **Priyanka Balla** (Developer)
