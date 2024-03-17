# YouTube Video Search App

This is a simple React application that allows users to search for YouTube videos using the YouTube API and display them in a list. It also provides a video detail view when a video is selected.

## Features

- **Search Bar**: Users can input search terms to find YouTube videos.
- **Video List**: Displays a list of videos fetched from YouTube based on the search term.
- **Video Detail**: Shows details of the selected video, including its title, description, and an embedded video player.

## Preview of Webpage


<img width="774" alt="image" src="https://github.com/SiddharthaChakrabarty/Youtube-Video-Search-App/assets/119057806/6730bc8e-deb6-45a4-86ad-ffa522e837e1">

## Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine using `git clone`.
2. Navigate to the project directory.
3. Install dependencies by running `npm install`.
4. Obtain a YouTube Data API key from the Google Developer Console.
5. Replace `API_KEY` in `index.js` with your YouTube Data API key.
6. Run the application using `npm start`.
7. Open your web browser and go to `http://localhost:8080`.

## Components

This project consists of the following components:

- **App**: The main component that manages the state of the application, including the list of videos and the selected video.
- **SearchBar**: A component for users to input search terms and trigger video searches.
- **VideoList**: A component that displays a list of videos fetched from YouTube.
- **VideoDetail**: A component that displays details of the selected video, including its title, description, and embedded video player.

## Dependencies

This project relies on the following dependencies:

- `react`: JavaScript library for building user interfaces.
- `react-dom`: Provides DOM-specific methods that can be used at the top level of a web app to interact with the DOM.
- `youtube-api-search`: A package for searching YouTube videos using the YouTube API.
- `lodash`: A JavaScript utility library for manipulating arrays, objects, and strings.
- `bootstrap`: A popular CSS framework for building responsive and mobile-first websites.

## Usage

1. Enter search terms in the search bar to search for videos.
2. Click on a video from the list to view its details and watch it in the embedded player.

## Styling

Styling for this project is done using CSS. The main styles are defined in `style.css` and applied to various components to improve the visual presentation and user experience.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.



