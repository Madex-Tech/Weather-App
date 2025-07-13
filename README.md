# TASK 1 – Build a Webpage that Fetches and Displays Data from a Public API

*COMPANY*: CODTECH IT SOLUTIONS  
*NAME*: MAADESHWAR D V  
*INTERN ID*: CITS0D500  
*DOMAIN*: FULL STACK DEVELOPMENT  
*DURATION*: 4 WEEKS  
*MENTOR*: NEELA SANTOSH  

## Description:

In this task, I was assigned to build a fully functional and responsive webpage that fetches and displays live data from a public API. The purpose of the task was to gain hands-on experience with JavaScript-based data fetching methods, such as the Fetch API, and understand how to work with external data sources over the internet using HTTP protocols. The project aimed to enhance my skills in creating dynamic user interfaces that reflect real-time data and user input without reloading the entire page.

For implementation, I used HTML5 to structure the webpage, CSS3 for styling and layout design, and Vanilla JavaScript for logic and interactivity. The API I selected was the OpenWeatherMap API, which returns live weather data in JSON format. When a user enters a city name in the input field, the webpage sends an API request in the background, processes the response, and dynamically displays the temperature, weather condition, humidity, and wind speed, along with an appropriate weather icon.

To achieve a smooth user experience, I focused on creating a clean UI using Flexbox and Grid systems. The layout was designed to be mobile-responsive and adaptable across various screen sizes. I used JavaScript event listeners to trigger actions based on user input, such as button clicks or pressing Enter in the search field.

The Fetch API was the core feature here. I used it to make asynchronous GET requests to the weather API endpoint. I implemented promises to handle the asynchronous nature of network requests. Additionally, I included error handling to manage situations such as invalid input, city not found, or network issues. Users receive proper messages in such cases, improving the robustness and reliability of the application.

This task also introduced me to the concept of JSON parsing and DOM manipulation. Once the data is retrieved and parsed, JavaScript dynamically updates the HTML content using `innerText` and `innerHTML` properties. I kept the code modular by writing separate functions for fetching data, rendering results, and clearing the interface.

Beyond the technical implementation, I learned the importance of user feedback, real-time validation, and fail-safes in web applications. I added a loading spinner that appears during the API call, which disappears once the data is successfully loaded or an error message is displayed.

From a learning perspective, this task was foundational. It helped me understand how the frontend of an application communicates with external data sources, how asynchronous programming works in JavaScript, and how to use the data to manipulate the UI dynamically. I also gained deeper insights into REST APIs, query parameters, API keys, and HTTP response codes.

This project has many real-world applications, not only for weather apps but also for stock market tickers, cryptocurrency trackers, news feeds, or any interface that depends on real-time external data. Completing this task gave me the confidence to build more complex and feature-rich applications in the future that involve external data sources and real-time updates.

In summary, Task 1 was a comprehensive and practical experience that strengthened my frontend development skills, deepened my knowledge of JavaScript and RESTful APIs, and taught me how to design responsive and interactive user experiences based on live data. It was a strong start to my journey as a full-stack developer.

##Output

👉 [Click here to view](https://madex-tech.github.io/Weather-App/)
