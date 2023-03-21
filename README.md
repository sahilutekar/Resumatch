# Resumatch
A combination of "resume" and "match," this name highlights the project's focus on comparing the similarity between a job description and a resume
This code is an example of a resume parser that uses docx2txt to extract the text from a job description and a resume in .docx format. It then uses CountVectorizer and cosine_similarity from the scikit-learn library to compare the similarity between the two documents.
Dependencies

    docx2txt: a Python package that extracts plain text from Microsoft Office .docx files.
    scikit-learn: a Python library for machine learning.

Usage

    Install the required packages by running !pip install docx2txt in your Python environment.
    Import the docx2txt package and extract the text from the job description and resume files using docx2txt.process().
    Concatenate the extracted text into a list.
    Convert the text into vectors using CountVectorizer.
    Calculate the similarity between the vectors using cosine_similarity.
    Print the similarity score between the two documents.
