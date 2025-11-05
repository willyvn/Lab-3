Task 2.1 – Weather Dashboard
🎯 Objective: Build a web application that displays current weather and a 5-day forecast for any city using the OpenWeatherMap API.
Technologies Used
HTML5, CSS3, JavaScript (ES6), Fetch API (async/await), OpenWeatherMap API, LocalStorage
APIs Used
Current Weather: 
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
5-Day Forecast:
https://api.openweathermap.org/data/2.5/forecast?q={city}&appid={API_KEY}&units=metric
API key: fe1fbd3fdaa4d931375c54f2ffbff5d9
Main Features
• Enter a city name → fetch weather data from API.
• Display temperature, humidity, wind speed, weather description, and emoji.
• Display 5-day forecast.
• Save recent searches using LocalStorage.
• Handle errors, loading state, and provide responsive UI.
Test Result
Input 'London' → displays current weather and 5-day forecast.
You can also test with cities such as Paris, Tokyo, Hanoi, etc.
Completion Evaluation
✅ Fully meets the lab requirements, uses real API data, and displays accurate results.
Task 2.2 – GitHub Repository Finder
🎯 Objective: Create a web app that searches for GitHub repositories and displays repository information (name, description, stars, forks, language).
Technologies Used
HTML5, CSS3, JavaScript (ES6), Fetch API, GitHub REST API.
API Used
https://api.github.com/search/repositories?q={query}&sort={sort}&page={page}&per_page=10
Main Features
• Search repositories by keyword.
• Display repository name, description, stars, forks, and language.
• Sort results by Stars, Forks, or Recently Updated.
• Include a Load More button for pagination.
• Handle errors and show loading state.
Test Result
Search for 'react' → displays ReactJS repositories. Sorting and loading additional pages work properly.
Completion Evaluation
✅ Fully meets all requirements, API works correctly, clear UI, and proper error handling.
Conclusion
Both Task 2.1 and Task 2.2 are fully completed, using real APIs, handling errors, displaying dynamic data, and providing user-friendly interfaces.
