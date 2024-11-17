# Text-to-Speech  
A simple Python application to convert text into audio using Google Text-to-Speech (gTTS) with a user-friendly GUI.  

---

## Features  
- Input text directly or load text from a `.txt` file.  
- Choose from multiple languages for text-to-speech conversion.  
- Save the generated audio as an MP3 file.  

---

## Prerequisites  
Ensure that Python (version 3.7 or later) is installed on your system. You can download Python [here](https://www.python.org/downloads/).  

---

## Installation  
1. Clone this repository or download the project files:  
   ```bash  
   git clone https://github.com/karimazan/text-to-speech.git  
   cd text-to-audio-converter  
   ```  

2. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

---

## Usage  
Run the script:  
   ```bash  
   python text_to_audio.py  
   ```  

The application window will open. You can:  
- Enter text manually in the text field.  
- Load a `.txt` file using the **Load a File** button.  
- Select a language from the dropdown menu.  
- Click on **Convert to Audio** to generate and save the MP3 file.  

---

## Supported Languages  
The application supports the following languages:  
- French (`fr`)  
- English (`en`)  
- Spanish (`es`)  
- German (`de`)  
- Italian (`it`)  
- Portuguese (`pt`)  

---

## Troubleshooting  
- **Missing dependencies:** Ensure all dependencies are installed using `pip install -r requirements.txt`.  
- **Permission issues:** Run the script with administrative privileges if required.  
- **Unsupported languages:** Only the listed languages are supported. To add more languages, update the `available_languages` dictionary in the code.  

---

## Contributing  
Contributions are welcome! Feel free to submit issues or pull requests to improve this project.  
