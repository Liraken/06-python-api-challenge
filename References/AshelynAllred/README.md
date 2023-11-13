# python-api-challenge
Jupyter notebooks to access weather data for nearest-fit cities from randomly generated geodata using citipy and OpenWeatherMap's API. Data was saved to a .csv for later use (and to save the precious few free API credits), then recalled for various graphs (see `/starter_code/WeatherPy.ipynb` and some of the `'Fig-*.png'` files in the `/output_data/` folder). This data was then further filtered through some weather criteria to narrow down the set, used to find the nearest hotel within 10km for the remaining cities, and plotted on a map to see the results geographically (See `/starter_code/VacationPy.ipynb`).


## Citations
Disclaimer: In case it's not already clear from the file structure of this repo, I used the starter code provided to save time.
While I did not directly copy/paste much code, I did reference a repo by @kanamoore to make sure I was on the right track, as well as some course activity code and some of my own previous work for this course. (Primarily the rcParams theme code so that my plots weren't blindingly bright, and to look at prior examples of API syntax for Geoapify and OpenWeatherMap calls)


Moore, K. (2020, September 17). *Kanamoore/Python-API-Challenge: Created a python script to make an API call to get weather data.* GitHub. https://github.com/kanamoore/python-api-challenge 
