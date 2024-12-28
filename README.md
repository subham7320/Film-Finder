Film Finder 🎬

Overview:
Film Finder is a dynamic web application that helps users discover movies based on their preferences, moods, and interests. Built with vanilla JavaScript, this app leverages The Movie Database (TMDB) API to provide users with a rich, interactive movie browsing experience.

Features:
Core Functionality-
Movie Search: Search for movies using keywords
Genre Filtering: Filter movies by specific genres
Rating Filter: Filter movies based on minimum rating requirements
Mood-Based Recommendations: Get movie suggestions based on your current mood
Random Movie Picker: Discover random movies when you're feeling adventurous

Movie Sections:

Trending Movies: Stay updated with currently trending films
Latest Releases: Browse the newest movie releases
Popular Movies: Explore widely popular movies
Search Results: View customized search results

Interactive Features:

Movie Details: Click on any movie to view detailed information including:

Plot overview
Release date
Rating
Runtime
Cast information
Similar movies
Trailer links (redirects to YouTube)



User Features-

User Profiles:

Customizable avatars
Editable usernames
Personal watchlists


Movie Reviews: Add and view user reviews for movies
Watchlist Management: Add/remove movies to/from your watchlist

UI/UX Features

Dark Mode: Toggle between light and dark themes
Infinite Scroll: Seamless loading of more content
Responsive Design: Works on both desktop and mobile devices
Dynamic Background: Color-cycling background for enhanced visual appeal
Loading Animations: Visual feedback during content loading
Scroll-to-Top: Easy navigation for long pages

Technical Details
API Integration

Uses TMDB API for movie data
Implements error handling and retry logic for failed API calls
Caches responses for better performance

Local Storage

Stores user preferences
Saves watchlists
Maintains user reviews
Preserves user profile information

Performance Features

Lazy loading of images
Infinite scroll implementation
Optimized API calls
Responsive image loading

Installation & Setup

Clone the repository
Update the apiKey in script.js with your TMDB API key
Open index.html in a web browser

javascriptCopyconst apiKey = 'YOUR_TMDB_API_KEY';
Dependencies

Font Awesome 5.15.3 (via CDN)
TMDB API

Browser Support

Chrome (recommended)
Firefox
Safari
Edge

Performance Considerations

Implements retry logic for failed API calls
Uses lazy loading for images
Includes loading states for better user experience
Handles offline scenarios

Security Features:

API key protection
Input sanitization
Secure external links

Future Enhancements:
Advanced sorting options
User authentication
Social sharing features
Enhanced movie recommendations
Personal movie ratings
Watch history tracking

Creator:-
Created by SUBHAM

Notes:
Requires active internet connection
TMDB API key required for functionality
Some features may require modern browser support

Contributing:
Feel free to fork the repository and submit pull requests for any improvements.
License
This project is open for use and modification with proper attribution.