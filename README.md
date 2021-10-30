# Travel Brewery Guide

[Live GitHub Page](https://matildabrantley.github.io/brewery-travel-guide/)
## Team 
* Matilda Brantley
* Andrew Koster
* Eagle Le
* Rakheem Smith
* Sergio Navarrete

![banner](assets/components/breweryReadme.gif)
```
## Project Description:
```
This project will allow users to search for Breweries based on cities and states. In addition, the user will have access to the Wikipedia pages of the breweries (if it exists), cities and states.
```
## User story: 
```
As an avid drinker that likes to travel, I want to know which breweries are in the areas I am traveling too
```
## Wireframe or sketch of the design:
![Wireframe](../components/wireframe.png)
## APIs to be used:
```
OpenBreweries and Wikipedia
```
## Breakdown of Roles:
```
* Matilda: Javascript/jQuery, API calls, designing layout
* Andrew: Detailed search results, API calls
* Eagle: CSS, Top 9 page, wire frame, README
* Sergio: CSS, debugging code, functionality
* Rakheem: Presentation, GitHub requests
```
## Features:
* Fetch nation-wide brewery information with OpenBrreweryDB API, searching by city or state.
* Retireve, parse, format Wikipedia pages with ajax call to MediaWiki API. Queries formatted to avoid article ambiguity.
* Search history held with localStorage.
* Search information passed to search-html via localStorage.
* Page for Top 9 Breweries in entire country with Google Maps built in.
* Page for full detailed search results, with alternating styles.
* Responsiveness throughout the entire website. Focus indicators for many elements.

