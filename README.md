
<p align="center">
  <img src="https://raw.githubusercontent.com/MBoustani/GeoParser/master/logo.png"  width="250"/>
</p>
# GeoParser
Geoparser extracts locations, such as cities or geographic coordinates expressed as latitude-longitude from any file and visualizes the points on a map. 

##How to Install 

###Requirements
-Python 2.7 

-pip 

-Girder

###Instructions

1. Install python requirements
```
pip install -r requirements.txt
```
2. [Install Girder] (http://girder.readthedocs.org/en/latest/prerequisites.html)

###How to Run the Application

1. Run MongoDB
```
Mongod &
```

2. Run Solr
Change directory to where you cloned the project
```
Solr/solr-5.3.1/bin/solr start
```

3. Run Girder
```
girder-server -p 8081
```

4. Run the app
```
python app.py
```

5. Open in browser [http://localhost:8080/](http://localhost:8080/)

## Technologies we Use
- [Apache Tika](https://github.com/chrismattmann/tika-python)
- [Geograpy](https://github.com/ushahidi/geograpy)
- [Geopy](https://github.com/geopy/geopy)


