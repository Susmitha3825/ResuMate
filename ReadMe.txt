# ResuMate: SkillSync - Perfect Your Resume Fit

ResuMate is an advanced Applicant Tracking System (ATS) designed to analyze resumes and provide suggestions based on the uploaded resume and the provided job description. The system aims to help candidates optimize their resumes to better match job requirements, enhancing their chances of getting noticed by employers.

## Features

- **Resume Analysis**: Upload your resume and get an in-depth analysis of how well it matches the job description.
- **Job Description Matching**: Paste a job description to see which skills and qualifications are required.
- **Suggestions and Improvements**: Receive suggestions on how to improve your resume to align better with the job description.
- **Interactive Interface**: User-friendly interface built with Streamlit.

## Technologies Used

- **[Streamlit](https://streamlit.io/)**: For creating an interactive web application.
- **[PyPDF2](https://pypi.org/project/PyPDF2/)**: For extracting text from PDF resumes.
- **[google.generativeai](https://pypi.org/project/google-generativeai/)**: For generating content and suggestions.
- **[python-dotenv](https://pypi.org/project/python-dotenv/)**: For managing environment variables.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ResuMate.git
    cd ResuMate
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv env
    source env/bin/activate   # On Windows, use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the root directory and add your Google API key:
    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Open your browser and go to `http://localhost:8501`.

3. Follow the instructions on the web app:
    - Paste the job description in the provided text area.
    - Upload your resume in PDF format.

4. Click the "Submit" button to get analysis and suggestions.

## Project Structure

```
ResuMate/
│
├── app.py              # Main application script
├── requirements.txt    # List of required packages
├── .env                # Environment variables
└── README.md           # Project documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to modify this README file as needed to better suit your project's specifics and structure.