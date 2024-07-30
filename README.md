# Speech-to-Text-with-PHPMyAdmin-Integration
 This JavaScript code integrates speech recognition with a PHP backend that interacts with a MySQL database via PHPMyAdmin. It captures spoken words, converts them to text, and stores the transcribed data in a MySQL database using PHP.

 This project allows users to speak text, which is then converted to speech and stored in a database.

## Features:

- Uses Web Speech API for real-time speech recognition.
- Provides a user-friendly interface for recording and displaying transcribed speech.
- Stores the transcribed text in a MySQL database using a dedicated PHP script.
  
## Setup:

- Create a MySQL database:
- Set up a MySQL database on your server and create a table named speech with a column named text to store the transcribed speech.
  
### Database Connection Details:
- Update the connection details in insert.php with your specific database server, username, password, and database name.
  
## How to Use:

- Open the application in a web browser.
- Click the "Start" button (represented by a play icon) to enable speech recognition.
- Speak your desired text.
- The transcribed text will appear in the textarea box below the button.
- As you speak continuously, the text will be updated with interim results.

![Screenshot 2024-07-28 225758](https://github.com/user-attachments/assets/eaeedb22-71e4-4b11-b947-2f7799204a95)
