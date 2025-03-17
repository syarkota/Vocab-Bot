# Vocab-Bot
Vocab Bot is a simple web application that allows users to search for word meanings using an online dictionary API. The app provides definitions and pronunciation audio for searched words.

# TRY : 
(https://vocab-bot.vercel.app/)

## Features
- Search for word meanings instantly
- Displays pronunciation audio (if available)
- Responsive UI with a clean and simple design

## Technologies Used
- **HTML**: For structuring the web page
- **CSS**: For styling and layout
- **JavaScript**: For fetching word definitions from an API and updating the UI
- **Dictionary API**: [Free Dictionary API](https://dictionaryapi.dev/)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/syarkota/vocab-bot.git
   ```
2. Navigate to the project directory:
   ```sh
   cd vocab-bot
   ```
3. Open `index.html` in a browser.

## Usage
1. Type a word in the search box.
2. Press `Enter` to fetch its meaning.
3. If available, the meaning and pronunciation audio will be displayed.

## File Structure
```
Vocab-Bot/
│── index.html       # Main HTML structure
│── style.css        # Styles for the application
│── index.js         # JavaScript logic for fetching and displaying word meanings
│── README.md        # Project documentation
```

## API Integration
Vocab Bot uses the [Dictionary API]

https://github.com/user-attachments/assets/525cbcb5-fe9a-415e-a0a8-417487684f7e

 to fetch word meanings. The API is called dynamically when a user enters a word and presses Enter.

Example API request:
```sh
GET https://api.dictionaryapi.dev/api/v2/entries/en/{word}
```

## Contributing
If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is open-source and available under the MIT License.



