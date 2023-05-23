### IP Details App
This is a simple web application that retrieves and displays details about an IP address. It uses the IP geolocation API to fetch the information and presents it in a user-friendly format.

### Features
Retrieves IP details such as IP address, location, timezone, and organization.
Displays the IP address, address details (city, region, country), timezone, and organization on the webpage.
Shows the location of the IP address on a map using Mapbox.
### Prerequisites
To run this application, you need the following:

### A modern web browser.
Internet connectivity to fetch IP details and map data.
### Usage
Clone the repository or download the code files.
Open the index.html file in a web browser.
Enter an IP address in the input field.
Click the "Go" button to retrieve and display the IP details.
The IP address, address details, timezone, and organization will be shown on the webpage.
A map will be displayed with a marker indicating the location of the IP address.
Code Explanation
The code consists of two files: index.html and script.js.

### index.html: 
Contains the HTML structure of the web application, including the input field, button, IP details display elements, and map container.
script.js: Implements the functionality of the web application. It handles the button click event, fetches the IP details using the IP geolocation API, updates the webpage with the retrieved information, and displays the IP location on a map using Mapbox.
The code uses the Fetch API to make HTTP requests to the IP geolocation API and retrieve the JSON response. It then updates the HTML elements with the fetched data and creates a map using Mapbox's JavaScript library to display the IP location.

### APIs Used
IP Geolocation API: The application uses an IP geolocation API to fetch the details of the entered IP address. It retrieves information such as the IP address, location, timezone, and organization. The API endpoint used in the code is https://ipapi.co/{ip}/json/, where {ip} is the entered IP address.
### Map Provider
Mapbox: The application uses Mapbox to display the IP location on a map. The map is initialized with a default center and zoom level, and the marker representing the IP location is added to the map.
Please note that you may need to provide your own API key for Mapbox to use the map functionality. The API key used in the code is a placeholder and may not work.