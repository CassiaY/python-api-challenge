# python-api-challenge
Module 6 challenge  
Contributor: Cassia Yoon  

Assignment Background:  
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests,APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?" Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?  

- APIs used: https://openweathermap.org/api, https://www.geoapify.com/
- Also used the citypy Python library: https://pypi.org/project/citipy/

My scripts (WeatherPy.ipynb and VacationPy.ipynb) can be found in the folder 'WeatherPy'. To run the scripts, it is necessary to have an api key from the above APIs. The WeatherPy script analyzes weather as it relates to latitudes. The VacationPy script creates a map of cities with subjectively ideal weather and their nearest hotel within a 10,000meter radius.  

The output_data folder contains a csv file of the data (random list of cities and their coordinates, temperature, wind speed, and other details) obtained from the open weather API at the time of writing script and output png files of the graphs/plots created based on the city data collected.  

Resources:  
- https://stackoverflow.com/questions/8213522/when-to-use-cla-clf-or-close-for-clearing-a-plot
- https://openweathermap.org/current
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html
- regarding hover_cols = https://hvplot.holoviz.org/user_guide/Customization.html
- Also referenced related class exercises.

Thank you:  
To my instructor, TA's and central graders.
