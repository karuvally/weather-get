#weather-get
weather-get, a weather retrieval program for *NIX<br>
Copyright 2014-2015, Aswin Babu K
Released under GNU General Public License
Thanks to SleepyHarry for cleaning up the code
Thanks to novel_yet_trivial and 04h for suggestions

weather-get is a weather retireval program for Unices, but one that prints
the result to the terminal. It uses WeatherUnderground API for retrieving
weather information. It can be easily modified to retirieve more information
from the WeatherUnderground website.

#Installation
There is no installation required.
Just copy the files of the program to the desired location, and start using it.
You can link the executable to somewhere along PATH, like /usr/local/bin,
if you wish to run it from anywhere in the system.

#Files
weather-get is a single executable. But it creates a directory inside your
home folder, '.weather' and two files 'config' and 'weather' to store the 
location details and current weather information respectively.

#Usage
Run the command from terminal to use the program. Please set up the location,
using the '-e' switch, if you are running the program for the first time.
If the City you inserted fails to retrieve data, try another nearby city.
Run the program using '-u' switch to update the weather. Once the weather is
retrieved, it is stored locally in '~/.weather/weather' file so that you can
display it even while you are offline. The '-h' switch will present you with the
help screen, which is basically the above stuff in a more readable format.
