# Kanye-West-Quote-Generator

## Description
This is a simple desktop application that displays random Kanye West quotes. It uses Python with Tkinter for the GUI and fetches quotes from the "https://api.kanye.rest" API.

## Features
- Fetches and displays random Kanye West quotes
- Simple and intuitive user interface
- Updates quote on button click

## Requirements
- Python 3.x
- Tkinter 
- requests library


## How It Works

### User Interface
- The application uses Tkinter to create a window titled "Kanye Says..."
- It displays a background image and a Kanye West image button.
- The quote is displayed on top of the background image.

### Fetching Quotes
- The `get_quote()` function is called when the Kanye West button is clicked.
- It sends a GET request to "https://api.kanye.rest" using the `requests` library.
- The response is parsed to extract the quote.

### Displaying Quotes
- The fetched quote is displayed on the canvas, replacing any previous quote.
- The text color is set to white for visibility against the background.

### Error Handling
- The application uses `raise_for_status()` to handle any HTTP errors that might occur during the API request.

## File Structure
- `main.py`: The main application script
- `background.png`: Background image for the application
- `kanye.png`: Image used for the button

## API Used
This application uses the [Kanye.rest API](https://kanye.rest/), which provides random Kanye West quotes.

## Contributing
Contributions, issues, and feature requests are welcome. 
