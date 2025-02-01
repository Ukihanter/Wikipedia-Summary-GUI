# Wikipedia Summary GUI

## Overview

This is a simple Tkinter-based GUI application that fetches Wikipedia summaries based on user input. The program allows users to enter a topic, retrieve a short summary from Wikipedia, and even listen to the text using text-to-speech (TTS) functionality.

## Features

- **User Input:** Enter a topic to search for on Wikipedia.
- **Summary Fetching:** Retrieves a brief summary of the topic using the Wikipedia API.
- **Error Handling:** Provides feedback if no results are found or if multiple results exist.
- **Text-to-Speech:** Reads the Wikipedia summary aloud using `pyttsx3`.
- **Graphical Interface:** Built using Tkinter with a visually appealing design.

## Dependencies

Ensure you have the following dependencies installed before running the program:

```sh
pip install wikipedia pyttsx3
```

## Installation & Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/wiki-summary-gui.git
   ```
2. Navigate to the project directory:
   ```sh
   cd wiki-summary-gui
   ```
3. Run the Python script:
   ```sh
   python main.py
   ```

## Project Structure

```
|-- wiki-summary-gui/
    |-- build/assets/gui.py                 # UI assets (images, icons, etc.)
```

## How It Works

1. The user enters a topic in the text field.
2. Clicking the "Search" button fetches a short summary from Wikipedia.
3. If multiple results exist, a suggestion list is displayed.
4. The "Read Aloud" button triggers text-to-speech for the summary.

## Error Handling

- **Page Not Found:** If no Wikipedia page exists, the user is informed.
- **Disambiguation:** If multiple pages match the query, a list of suggestions is provided.

## Future Enhancements

- Add more customization options for text-to-speech (voice selection, speed adjustment, etc.).
- Implement a history feature to store past searches.
- Improve UI design with additional themes and responsiveness.

## License

This project is licensed under the MIT License.

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

my name is uki

