# micamino 🚲
**Mi camino** aims to be a little project for tracking my daily progress during my *Camino de Santiago* on bike. It will consist of several Python scripts that perform the following actions:

- Download all files in a *Google Drive* folder (gpx files and pictures) at set intervals.
- Parse the gpx files.
- Otain the location of the pictures using the metadata.
- Display the latest progress (parsed gpx files) on a map via *Folium*.
- Send the pictures to my *Raspberry* and display them on the map with a marker on the point they were taken.
- Display the current progress (km/elevation).

For my convenience I chose to use a *Google Drive* folder to store all gpx files and pictures that I want to upload during the route. This way I can limit the data uploads to once/twice a day and I can keep the scripts *relatively* simple, with just a few lines of web scraping.
