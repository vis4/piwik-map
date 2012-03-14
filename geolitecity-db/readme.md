This directory should contain the ``GeoLiteCity-Location.csv`` table.

Here's a sample script of how to get the data:

```bash
wget http://geolite.maxmind.com/download/geoip/database/GeoLiteCity_CSV/GeoLiteCity_20120207.zip
unzip GeoLiteCity_20120207.zip
mv GeoLiteCity_20120207/GeoLiteCity-Location.csv .
rm -Rf GeoLiteCity_20120207
rm GeoLiteCity_20120207.zip
```

The content of the file should look like this:

```csv
Copyright (c) 2007 MaxMind LLC.  All Rights Reserved.
locId,country,region,city,postalCode,latitude,longitude,metroCode,areaCode
1,"O1","","","",0.0000,0.0000,,
2,"AP","","","",35.0000,105.0000,,
3,"EU","","","",47.0000,8.0000,,
4,"AD","","","",42.5000,1.5000,,
5,"AE","","","",24.0000,54.0000,,
6,"AF","","","",33.0000,65.0000,,
7,"AG","","","",17.0500,-61.8000,,
8,"AI","","","",18.2500,-63.1667,,
```
