GTA IV Radio Player
A simple web-based radio player designed to mimic the station-switching experience found in Grand Theft Auto games. Users can cycle through a predefined list of radio stations, each with its own name, icon, and music. The player also features random start times for music tracks and responsive design.

Features
GTA-Inspired Interface: Visually reminiscent of in-game radio selectors.

Station Carousel: Smoothly displays current, previous, and next station icons.

Dynamic Station Display: Shows the name of the currently playing station.

Play/Pause Functionality: Standard audio controls.

Next/Previous Station Buttons: Easily switch between stations.

Keyboard Navigation: Use the 'Q' key to cycle through stations.

Mouse Wheel Navigation: Scroll up/down over the radio container to change stations.

Random Track Start: Each time a station plays, the music starts from a random position within the track.

Responsive Design: Adapts to various screen sizes (mobile, tablet, desktop).

Toast Notifications: Provides subtle feedback for loading and playback status.

Audio Preloading: Preloads adjacent station audio for smoother transitions.


Open index.html:
Simply open the index.html file in your web browser. No server setup is required for basic functionality.

Customizing Radio Stations
You can easily customize the radio stations by editing the radioStations array in the script section of index.html.

Each station object has three properties:

name: The display name of the radio station (e.g., 'The Beat 102.7').

src: The URL to the MP3 audio file for the station. Ensure these URLs are publicly accessible.

icon: The URL to the station's logo or icon image. For best visual results, use square images.

Example:

const radioStations = [
    { name: 'My Custom Station', src: 'https://example.com/audio/my-song.mp3', icon: 'https://example.com/images/my-icon.png' },
    // Add more stations here
];

Disclaimer
This project is a fan-made creation and is not affiliated with, endorsed by, or sponsored by Rockstar Games or Take-Two Interactive. The logos, music, and station names used in this demonstration are for illustrative purposes only and are inspired by the Grand Theft Auto series. I do not claim ownership of any copyrighted materials (logos, music files) referenced or used within this project. All rights for such materials belong to their respective owners. This project is intended for educational and personal use only.
