# micamino 🚲
**Mi camino** is a little project for tracking my daily progress during my *Camino de Santiago* on bike. It will consist of several Python scripts that perform the following actions:

- Download all files in a *Google Drive* folder (gpx files and pictures) at set intervals.
- Parse the gpx files.
- Obtain the location of the pictures using the metadata.
- Display the latest location (parsed gpx files) on a map via *Folium*.
- Host the pictures on my *Raspberry* and display them on the map with a marker on the point they were taken.
- Display the current progress (km).

For my convenience I chose to use a *Google Drive* folder to store all gpx files and pictures that I want to upload during the route. This way I can limit the data uploads to once/twice a day and I can keep the scripts *relatively* simple, with just a few lines of web scraping.

# Checking the progress

The project can be found on the following [**url**](http://www.fresquito.es/micamino/map.html), once you access it you'll see somehting similar to this:

![](https://i.imgur.com/MU0oXog.png)

You'll see three main markers, which contain the following information:

🔵**Blue marker**: Starting point of the route (Roncesvalles).

![](https://i.imgur.com/YB0GxGa.png))

🟢**Green marker**: my latest position. It will be automatically updated every time I upload a new *gpx* file, once or twice a day. Displays the nearest town (calculated via haversine distance) as well as my current progress in Km.

![](https://i.imgur.com/6JjSLGp.png))

🔴**Red marker**: End of the journey, Santiago de Compostela. Displays how many Km I have left until I complete my trip.

![](https://i.imgur.com/ZfPXIZg.png))

📷**Photos**: Any pictures that I take and upload along the way will be geolocated and automatically added on the map. You can simply click on the marker and a thumbnail of the picture will appear. Click the thumbnail to see the image in full size.

![](https://i.imgur.com/u5vPhnS.png)



For any inquiries or feedback on the project feel free to send me an [**email**](info@xesteban.com) 📧 😊
