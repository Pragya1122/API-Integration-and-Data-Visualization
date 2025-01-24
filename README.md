# API-Integration-and-Data-Visualization

*Company* : CODETECH IT SOLUTIONS

*Name* : PRAGYA SANTRA

*Intern ID* : CT08NGE

*Domain* : Python

*Duration* : 4 Weeks

*Mentor* : NEELA SANTOSH

## Description 
The task involves integrating an API to fetch real-time weather data and visualizing it in an insightful manner using Python. It utilizes the OpenWeatherMap API to retrieve a 5-day weather forecast for a specified location, demonstrating practical skills in API integration, data processing, and visualization. By leveraging Python libraries such as requests, pandas, matplotlib, and seaborn, the task highlights the ability to handle JSON data, convert it into a structured format, and present it visually to extract meaningful trends.

The process begins with establishing a connection to the OpenWeatherMap API using an API key and a city name. The API request retrieves data in JSON format, which includes weather details for multiple timestamps over five days. The data is parsed to extract essential parameters such as temperature, humidity, and the corresponding timestamps. These parameters are structured into a pandas DataFrame, which allows for easier data manipulation and analysis. This step also includes converting the timestamp values into a proper datetime format, making them suitable for time-series analysis and visualization.

Once the data is structured, the next phase involves creating visualizations to uncover patterns and insights. The script uses Matplotlib and Seaborn, two powerful Python libraries for data visualization. A dual-line plot is generated, displaying temperature and humidity trends over time. The temperature, plotted in blue, provides insights into how the weather fluctuates across different periods, while the humidity, represented in green, helps identify variations in air moisture levels. Both metrics are plotted against the timestamp, offering a clear understanding of weather dynamics for the specified location.

The visualization is designed with clarity and usability in mind. Key elements such as axis labels, a title, and a legend are included to ensure that the graph is easy to interpret. Additionally, the x-axis timestamps are rotated for better readability, especially when dealing with frequent time intervals. Gridlines are added to enhance the graph's precision, enabling users to easily correlate data points with their respective values. The visualizations serve as an intuitive tool to analyze weather patterns, making them valuable for decision-making in areas such as travel planning, agriculture, or event management.

Error handling is incorporated to address potential issues during the API request. If the API call fails, the script outputs the status code, allowing users to troubleshoot issues such as incorrect API keys, invalid city names, or network problems. This ensures the script's robustness and reliability, even when dealing with external dependencies.

This task demonstrates an effective approach to combining data retrieval and visualization, showcasing the importance of Python in data science and analytics. The use of APIs for real-time data highlights its significance in applications that require dynamic and constantly updated information. Furthermore, transforming raw JSON data into meaningful insights emphasizes the value of data preprocessing and analysis in the broader context of data-driven decision-making.

### Screenshot of the output

![Image](https://github.com/user-attachments/assets/5299b69b-57ec-42b9-a4ac-db11977b2612)
