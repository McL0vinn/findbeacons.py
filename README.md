To tell findbeacons.py what time interval to look for use the -i argument. 
To specify a minimum number of beacon requests (to reduce false positives) use the -c argument. This is shown below:

./findbeacons.py -i 5 -c 10 192.168.10.17 access.log

The findbeacons.py command breaks down as follows:

-i 5 – look for beacons that are at 5‑second intervals

-c 10 – look for a minimum of 10 beacons

192.168.10.17 – look for beacon traffic from host 192.168.10.17

access.log – search through the file access.log
