# Web Phishing Detection with Python

This project is aimed at detecting phishing websites using Python. It utilizes a trained dataset to analyze input URLs provided by the user. The application performs various actions such as DNS lookup, URL analysis, API scans, content analysis, and hyperlink analysis to determine the likelihood of a website being a phishing site. Additionally, it integrates with APIs such as VirusTotal for enhanced analysis.

## Features

- **User Input**: Users can provide the URL of the website they want to scan.
- **Data Analysis**: The application analyzes the target site using techniques such as DNS lookup, URL analysis, content analysis, and hyperlink analysis.
- **Trained Dataset**: Utilizes a pre-trained dataset to classify websites as phishing or legitimate.
- **API Integration**: Integrates with external APIs such as VirusTotal for additional analysis.
- **Result Generation**: Produces a result indicating the likelihood of the provided website being a phishing site.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/sandiyochristan/Web-Phishing-Detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd web-phishing-detection
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:

    ```bash
    python main.py
    ```

2. Enter the URL of the website you want to scan when prompted.

3. Wait for the analysis to complete and view the results.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or create a pull request.

## Acknowledgements

- Special thanks to [VirusTotal](https://www.virustotal.com/) for providing their API for analysis.

## Contact

For any inquiries or support, please contact [sandichrist6@gmail.com](mailto:sandichrist6@gmail.com).
