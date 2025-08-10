# API-INTEGRATION-AND-DATA-VISUALIZATION1

Company : CODETECH IT SOLUTIONS

Name : Bhati Mehar Mansoor Akhtar

Intern ID : CT04DH2154

Domain : Python 

Duration : 4 weeks

Mentor : Neela Santosh

****************************************

**Task 1 – API Integration and Data Visualization**

In Task 1 of my CODTECH Python internship, I was assigned to create a Python program that connects to a public API, retrieves data in real time, and presents it through clear and informative visualizations. I chose to work with a widely used public API such as **OpenWeatherMap**, which provides live and forecasted weather data in JSON format.

The project began with **API Integration**. Using Python’s built-in `requests` library, I sent HTTP GET requests to the API endpoint with appropriate query parameters, such as the city name, units of measurement, and my unique API key. Once the API responded with JSON data, I parsed the data using Python’s built-in methods and the **Pandas** library for structured handling. This allowed me to store the information—such as temperature, humidity, wind speed, and weather descriptions—into DataFrames, making further analysis more efficient.

Next, I focused on **Data Cleaning and Processing**. Public API responses often contain more information than needed, so I filtered the data to extract relevant fields and converted timestamps into human-readable formats using Python’s `datetime` module. In some cases, I also handled missing values or converted units (e.g., from Kelvin to Celsius) to ensure clarity in the results.

The **Data Visualization** stage was implemented using **Matplotlib** and **Seaborn**, two powerful Python libraries for creating graphs and charts. I designed visualizations that could display trends over time—such as a line chart for temperature changes during the day, a bar chart for humidity levels, or even a scatter plot to analyze the correlation between wind speed and temperature. Seaborn’s aesthetic styles made the graphs more visually appealing, while Matplotlib allowed fine-grained customization, such as labeling axes, adding legends, and adjusting figure sizes.

To make the solution user-friendly, I structured the script so that the user could input the location or city name and instantly get both the raw API data in a readable table and the corresponding visualizations. This interactive element ensured flexibility and usability for different scenarios.

Throughout the development, I followed **best coding practices** by adding comments for each significant code block, making the logic easier to understand. I also incorporated error handling to manage issues such as invalid city names, incorrect API keys, or network failures. This ensured the program would provide informative error messages instead of simply crashing.

**Tools and Technologies Used:**

* **Python** – core programming language.
* **Requests** – for API calls and HTTP communication.
* **Pandas** – for structured data storage and manipulation.
* **Datetime** – for converting and formatting timestamps.
* **Matplotlib & Seaborn** – for data visualization.
* **Development Environment** - Visual studio code.


***Output***

img width="1678" height="1182"< alt="Image" src="https://github.com/user-attachments/assets/2f1f3937-7957-4e76-8606-0dbc54b4afa2" />

















