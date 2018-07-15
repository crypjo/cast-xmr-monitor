###### crypjo's 
# Cast-XMR-Monitor - Mining rig monitor based on Cast XMR's remoteaccess JSON data

HTML page that can be loaded locally, using javascript and Google Charts API
Pulls JSON data from mining rigs specified as HTTP request parameters

Plots Hashrate, Temperature, Fan speed
Drop down selection of polling interval and number of points to plot

<img src="https://github.com/crypjo/cast-xmr-monitor/blob/master/cast-xmr-monitor.png" width="260">

Enable --remoteaccess for cast-xmr to enable JSON data retrieval

To use:
Open local file in browser and pass mining rigs IPs or names

file:///d:/Path/cast-xmr-monitor.html?miner=miner1&miner=miner2&miner=miner3
or
file:///d:/Path/cast-xmr-monitor.html?miner=192.168.1.225&miner=192.168.1.102

It supports specifying initial values for chart parameters (although the drop downs do not indicate these values, yet).
file:///d:/Path/cast-xmr-monitor.html?interval=5000&points=200&miner=miner1&miner=miner2&miner=miner3
