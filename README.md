# Spotify Clone Project

This project is a simple web-based music player that emulates basic functionalities of the popular music streaming service Spotify. It allows users to play, pause, skip, and control the progress of songs. The project is built using HTML, CSS (with Tailwind CSS), and JavaScript.

## Project Structure

- **index.html:** The main HTML file containing the structure of the web page, including navigation, song list, and player controls.

- **style.css:** The custom styles for the project, enhancing the visual appeal of the web page.

- **script.js:** The JavaScript file responsible for handling user interactions, managing the audio player, and updating the UI dynamically.

## Usage

To run the project locally, simply open the `index.html` file in a web browser. The web page will display a Spotify-like interface with a list of songs and player controls. Click on songs to play them, use the play/pause button to control playback, and navigate through the playlist.

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework used for styling.

- [Font Awesome](https://fontawesome.com/): Icons used for player controls.

## Song Data

Song information is stored in the `songs` array in the `script.js` file. Each song has a name, file path, and cover image path. You can customize the playlist by modifying or adding entries in the `songs` array.

    ```javascript
        let songs = [
            {songName: "دايلر - كثير ناس", filePath: "songs/1.mp3", coverPath: "covers/1.jpg"},
            {songName: "وسام قطب-اخطاء", filePath: "songs/2.mp3", coverPath: "covers/2.jpg"},
            {songName: "مع العشران", filePath: "songs/3.mp3", coverPath: "covers/3.jpg"},
            // Add more songs as needed
        ];

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Bug fixes, new features, and improvements are welcome.

## Credits

The project uses Tailwind CSS for styling.
Icons are provided by Font Awesome.