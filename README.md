# AI Mentor

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

**AI Mentor** is an innovative AI-powered platform designed to analyze various types of files—such as Word documents, PDFs, and PPTX presentations—to understand their content and answer any questions you may have about them. Leveraging advanced machine learning and natural language processing techniques, AI Mentor offers users an interactive way to query their documents and receive detailed, contextual responses.

## 🚀 Features

- 📄 **Multi-File Support** – Upload and process Word, PDF, and PPTX files.
- 🤖 **AI-Powered Analysis** – Understands and extracts information from various document types.
- ❓ **Question Answering** – Ask questions about your documents and get precise, contextual answers.
- 🌐 **User-Friendly Interface** – Easy-to-use web interface for uploading files and interacting with the AI.
- 🔄 **Continuous Learning** – Improves responses based on user interactions and feedback.

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Nwwar/AI-Mentor.git
cd AI-Mentor
```

### 2. (Optional) Create a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 🧠 Usage

### Run the Application

```bash
python app.py
```

Then open your web browser and navigate to:  
👉 [http://127.0.0.1:5000](http://127.0.0.1:5000)

### How It Works

- **Upload Files**: Upload your Word, PDF, or PPTX files.
- **Content Analysis**: The AI analyzes the file to extract and understand its content.
- **Ask Questions**: Pose questions related to the content of the file.
- **Receive Answers**: Get detailed answers based on the document's context.

## 🗂 Project Structure

```
AI-Mentor/
├── app.py              # Main application file
├── mentor.py           # Core AI analysis and question answering logic
├── utils.py            # Utility functions and helpers for file processing
├── templates/          # HTML templates for the web interface
├── static/             # CSS, JavaScript, and images
├── requirements.txt    # Python dependencies
├── Procfile            # Deployment configuration (if applicable)
├── runtime.txt         # Runtime configuration (for platforms like Heroku)
└── LICENSE             # Apache License 2.0
```

## 🛠 Customization

- **Analysis Logic**: Customize `mentor.py` to adjust how the AI processes and understands document content.
- **Interface Design**: Modify the HTML/CSS in the `templates/` and `static/` directories to change the UI.
- **File Processing**: Enhance `utils.py` to support additional file formats or improve existing file handling.

## 📄 License

This project is licensed under the **Apache License 2.0**.  
See the [LICENSE](LICENSE) file for full details.

## 🤝 Contributing

Contributions are welcome!  
Fork the repository, make your changes, and submit a pull request. For major changes, please open an issue to discuss your ideas first.

## 🙋‍♂️ Questions?

If you have any questions or need assistance, please open an issue in the repository.
