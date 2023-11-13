# SEOAnalyzer

SEOAnalyzer is a Python script that analyzes a webpage for basic SEO aspects and generates a report.

## Features

- Fetches HTML content from a given URL.
- Extracts and displays page title and meta description.
- Checks the presence of specified keywords in the webpage's content.
- Measures the page load speed.
- Checks if the webpage is mobile-friendly using the Google Mobile-Friendly Test API.
- Generates a comprehensive SEO report in a Word document.

## Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/SEOAnalyzer.git
    cd SEOAnalyzer
    ```

2. **Install dependencies:**

    ```bash
    pip install requests beautifulsoup4 python-docx
    ```

3. **Run the script:**

    ```bash
    python app.py
    ```

4. **Follow the prompts to enter the URL and keywords.**

5. **View the generated SEO report in the current directory.**

## Project Structure

- `app.py`: Main application file containing the SEO analysis script.
- `SEO_Report_[url].docx`: Generated SEO report in Word document format.

## Author

Maharshi Kushwaha
