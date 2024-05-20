# Audio Book Documentation
Introduction

The Audio Book project is a Python script that converts text from a specified file into speech, effectively creating an audiobook. It allows users to customize the voice gender and speech rate according to their preferences.

Features

- Converts text from a file into speech.
- Allows users to choose between male and female voices.
- Enables users to set the speech rate (speed) of the narration.
## Cloning the Repository

To clone the Wordle Game project from GitHub, follow these steps:

1. Open your terminal (Command Prompt, PowerShell, or any other terminal emulator).
1. Navigate to the directory where you want to clone the repository.
1. Run the following command: git clone audio\_book
1. Navigate into the cloned repository directory: cd audio\_book
## Dependencies
1. **pyttsx3**: This project utilizes the pyttsx3 library for text-to-speech conversion. You can install it via pip, Python's package manager. 

Install the dependencies using pip: pip install -r requirements.txt
## Running the Program
1. **Setup**: Place the Python script (audiobook.py) and the text file (book.txt) in the same directory.
1. **Running the Script**: Execute the Python script audiobook.py. You can do this by navigating to the directory containing the script in your command line or terminal and then running: python audiobook.py
1. **Interaction**:
   - The script will prompt you to choose the voice gender:
   - Choose voice gender:
   - 1. Male
   - 2. Female
   - Enter your choice (1 or 2):
   - Enter 1 for a male voice or 2 for a female voice.
   - Next, you will be asked to set the speech rate:
   - Enter speech rate (100 to 200, default is 150):
   - Enter a value between 100 and 200 to adjust the speech rate. The default rate is 150.
1. **Output**: The script will then convert the text from the specified file (book.txt) into speech using the chosen voice gender and speech rate. The narration will play automatically.

Limitations

- The text-to-speech conversion quality may vary depending on the chosen voice and speech rate.
- Longer texts or complex sentences may result in slower processing times or less natural-sounding speech.

Future Enhancements

- Implement support for additional languages and accents.
- Integrate with online text-to-speech services for enhanced voice options and better quality.
- Add support for pausing, resuming, and skipping sections during playback.

Conclusion

The Audio Book project provides a convenient way to convert text into speech, making it accessible for users who prefer listening over reading. By allowing customization of voice gender and speech rate, it offers a personalized experience for audiobook creation. With potential future enhancements, it can further improve its functionality and usability.

