# geoip-query
Look up IP addresses in MaxMind database from the command line and get back geographical location information.

Requires MaxMind GeoIP2 Python API
https://github.com/maxmind/GeoIP2-python

# Usage
Look up one IP address using -i
./geoip-query -i 127.0.0.1  

Lookup many IP addresses using a csv file
./geoip-query -f file.csv
