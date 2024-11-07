##Spotify Music Finder

Spotify Music Finder is a simple web application that allows users to search for their favorite artists and view their albums. Built with React, Vite, and the Spotify API, this app provides a quick and easy way to discover music and access album details directly from Spotify.

##Features

	•	Artist Search: Users can enter an artist’s name to find and select them.
	•	Album Display: Once an artist is selected, their albums are displayed with album covers, release dates, and links to listen on Spotify.
	•	Interactive UI: Built with React-Bootstrap for a responsive and interactive user experience.

##Tech Stack

	•	React: For building the user interface and managing component state.
	•	Vite: As the build tool for a fast, optimized development experience.
	•	Spotify API: To fetch artist and album data, using client credentials for authentication.
	•	React-Bootstrap: For styling and layout.

##Installation and Setup

	1.	Clone the repository:

    git clone https://github.com/yourusername/spotify-music-finder.git
    cd spotify-music-finder


	2.	Install dependencies:

    npm install


	3.	Set up Spotify API credentials:
	•	Go to the Spotify Developer Dashboard and create an app.
	•	Obtain your Client ID and Client Secret.
	•	Create a .env file in the root of your project and add your credentials:

    VITE_CLIENT_ID=your_client_id
    VITE_CLIENT_SECRET=your_client_secret


	4.	Run the app:

    npm run dev

    This will start the app in development mode, usually available at http://localhost:5173.

##Usage

	1.	Enter the name of an artist in the search box and press “Enter” or click the “Search” button.
	2.	The app will display a list of albums by the artist, including album artwork, release dates, and a link to listen on Spotify.

##Code Highlights

	•	API Authentication: Uses client credentials to obtain an access token from Spotify.
	•	React Hooks: useEffect is used to handle API calls and useState to manage search input, access token, and album data.
	•	Dynamic Styling: Styled with React-Bootstrap for a polished and user-friendly interface.

