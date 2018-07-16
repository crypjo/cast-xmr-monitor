###### crypjo's 
# Cast-XMR-Monitor - Mining rig monitor based on Cast XMR's remoteaccess JSON data

HTML page that can be loaded locally, using javascript and Google Charts API
Pulls JSON data from mining rigs specified as HTTP request parameters

Plots Hashrate, Temperature, Fan speed
Drop down selection of polling interval and number of points to plot
<p align="center">
<img src="https://github.com/crypjo/cast-xmr-monitor/blob/master/img/cast-xmr-monitor-theme-dark.png" width="600">

<img src="https://github.com/crypjo/cast-xmr-monitor/blob/master/img/cast-xmr-monitor-theme-light.png" width="600">
</p>

Enable --remoteaccess for cast-xmr to enable JSON data retrieval

To use:
Open local file in browser and pass mining rigs IPs or names

file:///d:/Path/cast-xmr-monitor.html?miner=miner1&miner=miner2&miner=miner3
or
file:///d:/Path/cast-xmr-monitor.html?miner=192.168.1.225&miner=192.168.1.102

It supports specifying initial values for chart parameters.  These are specified by the 0 based index of the item in the drop down
file:///d:/Path/cast-xmr-monitor.html?interval=2&points=3&theme=1&miner=miner1&miner=miner2&miner=miner3

Added a simple theme select for night view support
