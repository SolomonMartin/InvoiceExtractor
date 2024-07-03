# InvoiceExtractor

InvoiceExtractor is a Streamlit application that utilizes LangChain and Google Generative AI to extract information from invoice images and provide interactive query capabilities.

## Features

- **Invoice Upload:** Users can upload JPEG, JPG, or PNG images containing invoice data.
- **Image Preprocessing:** Automatically preprocesses uploaded images for content extraction.
- **Content Extraction:** Uses Google Generative AI to extract textual information from invoice images.
- **Interactive Querying:** Allows users to ask questions based on the extracted invoice content.
- **User-Friendly Interface:** Built with Streamlit, providing a straightforward and intuitive user experience.

## Technologies Used

- **LangChain:** Integrates various language processing tasks such as text extraction and natural language understanding.
- **Streamlit:** Creates interactive web applications directly from Python scripts.
- **Google Generative AI:** Provides advanced text generation capabilities for answering user queries.
- **PIL (Python Imaging Library):** Handles image processing tasks such as opening and manipulating image files.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/InvoiceExtractorApp.git
   cd InvoiceExtractorApp

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt

3. Set up your Google API key:

    Create a .env file in the root directory of the project.
    Add your Google API key to the .env file:

    ```makefile

    GOOGLE_API_KEY=your_api_key_here

4. Run the Streamlit app:

    ```bash

    streamlit run app.py

Usage

    Open the app in your browser.
    Upload JPEG, JPG, or PNG images containing invoice data.
    Enter questions related to the content of the uploaded invoice images.
    View the app's responses based on the extracted information from invoices.
