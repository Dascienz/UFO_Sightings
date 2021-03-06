# UFO Sightings Data

#### About:
Scraped ufo sightings data from http://www.nuforc.org. 
Repo contains routines for scraping, cleaning, analyzing and visualizing the results.

## DATA FILES

### nuforcReports.csv
Run the following commands on the zipped data files (Apologies if there is any loss, I haven't checked thoroughly.): 

1.  `zip -F archive.zip --out unsplit.zip` 
2.  `unzip unsplit.zip`

Now you can go into the new folder `Files` and find nuforcReports.csv to import into `ufoProcessing.py`. The script should output a file named `ufoData.csv` which contains structured U.F.O. sightings data which you can use for analysis and modeling. You're welcome to scrape your own files using `ufoSpider.py`, but obtaining geographic coordinates can be annoying since server requests can take a long time and you have the potential of getting kicked.

### locationData.csv
Contains latitude and longitude coordinates for sightings. These results were obtained using `geopy`.

### airportData.csv
Latitude and longitude coordinates for airports, heliports, and seaplane bases across the United States. Spreadsheet sliced from data obtained from <https://www.faa.gov/airports/airport_safety/airportdata_5010/>.

### militaryData.csv
Latitude and longitude coordinates for military bases across the United States. Obtained from <https://www.google.com/maps/d/viewer?mid=1hvB-oq9gE0H8gEwKJ4XHFOKaY5k&hl=en_US&ll=49.67042577190774%2C-117.29381349999994&z=2>

Download the KML file and convert it to CSV using software of your choice.

