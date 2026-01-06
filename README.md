# Image Analyzer using Gemini3 LLM
A Streamlit-based AI application that analyzes uploaded images (such as doctor prescriptions) and generates clear, human-readable explanations using Google Gemini-3 Large Language Model
## Project Overview
This project demonstrates the use of multimodal AI (Text + Image) by integrating Google Gemini-3 LLM with a Streamlit web interface.
Users can upload an image (for example, a handwritten doctor prescription) and optionally provide a text prompt. The application then intelligently understands the image and generates a meaningful textual response.
This project highlights real-world usage of Generative AI for image understanding.
## What This Project Does
* Allows users to upload an image (PNG / JPG / JPEG)
* Accepts an optional text prompt from the user
* Uses Gemini-3 LLM to analyze the image
* Generates a human-readable explanation
* Especially useful for:
  Understanding doctor prescriptions
  Medical notes interpretation
  Image-based content explanation
## Technologies Used
* Python
* Streamlit – Web UI
* Google Gemini-3 LLM
* Pillow (PIL) – Image processing
* Generative AI (Multimodal)
## How It Works
* User uploads a prescription image
* Optional prompt is entered (e.g., “Explain this prescription”)
* Image + prompt is sent to Gemini-3
* Gemini-3 analyzes the image content
* App displays a clear textual response
## Key Features
* Image + text based AI interaction
* Clean and simple UI using Streamlit
* Multimodal AI support (Text + Image)
* Real-world use case (medical prescription analysis)
* Fast and accurate response generation
## Example Use Case
Upload a doctor’s handwritten prescription
→ The model explains medicines, dosage hints, or notes in simple language
## How to Run the Project
```
streamlit run app.py
```
## Learning Outcomes
* Working with Generative AI & LLMs
* Image understanding using multimodal models
* Building AI web apps with Streamlit
* Secure API key management
* Real-world AI application development
