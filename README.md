# Map Animation Program

## Overview

The Map Animation program visualizes a journey between specific bus stops on a Mapbox map. By clicking a button, users can see a marker move sequentially through predefined bus stop coordinates, providing an animated representation of the route.

## Features

- **Interactive Map**: Utilizes Mapbox GL JS to render a customizable map.
- **Dynamic Marker Movement**: A marker moves between specified bus stops, showcasing a simple animation.
- **User-Friendly Interface**: A button allows users to start the animation with a single click.

## Technologies Used

- HTML
- CSS
- JavaScript
- Mapbox GL JS

## How to Use

1. **Set Up Your Environment**: Make sure you have an internet connection, as the program relies on the Mapbox API.
2. **Obtain a Mapbox Access Token**: Replace the placeholder token in the script with your own Mapbox access token.
3. **Open the HTML File**: Save the code as an `.html` file (e.g., `map_animation.html`) and open it in a web browser.
4. **Start the Animation**: Click the "Show stops between Gandhipuram and Sulur" button to initiate the marker movement across the bus stops.

## Code Explanation

- **Bus Stops Array**: The `busStops` array contains longitude and latitude pairs for the defined bus stops.
- **Map Initialization**: A Mapbox map instance is created and centered at the first bus stop.
- **Marker Setup**: A marker is added to the map at the starting bus stop's coordinates.
- **Movement Logic**: 
  - The `move()` function updates the marker's position every 1000 milliseconds based on the coordinates in the `busStops` array.
  - It increments a counter to access the next bus stop until all stops have been visited.

## Customization

You can customize the following aspects of the program:

- **Bus Stops**: Add or modify the coordinates in the `busStops` array to change the route.
- **Marker Style**: Customize the marker appearance using additional Mapbox Marker options.
- **Animation Speed**: Adjust the timing in the `setTimeout` function to speed up or slow down the marker movement.

## Conclusion

This Map Animation program is a practical example of using Mapbox for interactive mapping and animation in web applications. Feel free to enhance the code or integrate it into larger projects as you explore more functionalities of the Mapbox API!
