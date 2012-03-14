This directory should contain the ``GeoLiteCity-Location.csv`` table.

Here's a sample script of how to get the data:

```bash
wget http://geolite.maxmind.com/download/geoip/database/GeoLiteCity_CSV/GeoLiteCity_20120207.zip
unzip GeoLiteCity_20120207.zip
mv GeoLiteCity_20120207/GeoLiteCity-Location.csv .
rm -Rf GeoLiteCity_20120207
rm GeoLiteCity_20120207.zip
```