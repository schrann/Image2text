# Image2text
Generative AI based Image to Text application
# Image to Text Application using Gemini AI

![Screenshot 2024-09-27 114828](https://github.com/user-attachments/assets/9385c66b-edf8-4662-88a3-8c2fb9be078d)


## Project Overview

This project is a simple **Image to Text Application** built using **Streamlit** and **Google Gemini AI** (via the Google Generative AI API). The application allows users to upload an image and provide a text prompt, which is then processed by Google's Gemini model to generate relevant text content.

## Features

- Upload an image in `.jpg`, `.jpeg`, or `.png` format.
- Provide a text prompt to assist the model in generating responses based on the image.
- Automatically displays the uploaded image on the interface.
- Uses Google's **Gemini-1.5-flash** model for content generation.
- Displays the generated text output based on the user's input and image.

## Prerequisites

To run the project, ensure you have the following dependencies installed:

1. **Python 3.7+**
2. **Streamlit**
3. **Google Generative AI SDK** (Gemini)
4. **Pillow** for image handling
5. **python-dotenv** for environment variable management

### Install the required packages:

```bash
pip install streamlit google-generativeai Pillow python-dotenv
```

## Environment Setup

Make sure to set up your **Google API Key** for accessing the Gemini model by creating a `.env` file in the project root with the following content:

```bash
GOOGLE-API-KEY=your_api_key_here
```

## Running the Application

To run the app locally, use the following command in your terminal:

```bash
streamlit run app.py
```

Once the app is running, you can:

1. Enter a text prompt.
2. Upload an image (supported formats: `.jpg`, `.jpeg`, `.png`).
3. Click the **Begin** button to generate and view the text output.

## Project Structure

```bash
.
├── app.py           # Main application script
├── .env             # Environment variables file (Google API Key)
├── requirements.txt # List of dependencies
└── README.md        # This readme file
```

## Acknowledgments

This project uses Google's **Gemini-1.5-flash** model via the Generative AI API to generate text responses. Special thanks to the Google AI team for providing access to this powerful technology.

---

Feel free to reach out for any queries or improvements!
