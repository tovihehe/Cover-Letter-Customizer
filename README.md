# Cover Letter Customizer📋

## Overview

**Cover Letter Customizer** is a Python script designed to automate the process of tailoring cover letters for job applications. This script replaces placeholders in a template cover letter with predefined values such as the company name, position, date, and job function. By automating this process, the script helps create personalized cover letters efficiently, ensuring that each letter is specifically tailored to the job and company. The final customized cover letter is then converted to a PDF file, ready to deliver!

## Features

- **Replace Placeholders**: Automatically replace placeholders in a cover letter template with specific values.
- **Customizable Fields**: Easily set predefined values for key fields like `COMPANY`, `POSITION`, `FUNCTION`, and `DATE`.
- **Preserve Formatting**: Maintain the original formatting and structure of the cover letter.
- **PDF Conversion**: Convert the customized cover letter to PDF format for professional presentation.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/Cover-Letter-Customizer.git
   cd Cover-Letter-Customizer
   ```

2. **Install Dependencies**:

   This script requires Python to run. Install the necessary packages using `pip`:

   ```bash
   pip install requirements.txt
   ```

## Usage

1. **Prepare Your Template**:
   - Create a Word document (`template.docx`) with placeholders for `COMPANY`, `POSITION`, `FUNCTION`, and `DATE`.

2. **Modify the Script**:
   - Open `customize_cover_letter.py` and update the placeholders with the desired values.

   ```
   # Path to the original document
   doc_path = 'Template.docx'  
   
   # Path to save the modified document
   output_path = 'Cover-Letter.docx' 
             
   # Dictionary of words to be replaced          
   dictionary_replacement = {
       'DATE': '21st July 2024',
       'POSITION': 'Software Engineer',
       'COMPANY': 'Google',
       'FUNCTION': 'provide innovative software solutions'
   }
   ```

4. **Run the Script**:

   ```bash
   python customize_cover_letter.py
   ```

   The script will generate a customized cover letter and convert it to PDF format as `Cover-Letter.pdf`.

## Example Template

Your `Template.docx` should include placeholders like:

```
I am very thrilled to be working with COMPANY on your top-notch projects.

I am eager to contribute as much as possible in the POSITION position.

I would really like to FUNCTION and help growth of the COMPANY.

Date: DATE
```

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements. Contributions are always welcome!


