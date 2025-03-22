# SmolDocling OCR Application

This project implements an Optical Character Recognition (OCR) application using the SmolDocling model from Hugging Face. It allows users to extract text, tables, formulas (in LaTeX), and other elements from images. The application features a user-friendly web interface built with Gradio, supporting both single and batch image processing, and runs on GPU/CPU hardware for efficient inference.

## **Features**
- Extract text, tables, code, charts, and formulas from images.
- Convert mathematical formulas into LaTeX format.
- Support for single and multiple image uploads.
- Intuitive Gradio-based UI with tabs, icons, and dynamic visibility.
- Batch processing with detailed results displayed in a table.
- Performance timing for each processing task.

## **Prerequisites**
Before running the application, ensure you have the following installed:
- Python 3.8 or higher
- A compatible GPU (optional but recommended for faster inference) with CUDA support
- Required Python libraries (listed in `requirements.txt`)
