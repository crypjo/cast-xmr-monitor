###### crypjo's 
# Cast-XMR-Monitor - Mining rigs monitor based on Cast XMR's remote access JSON data

HTML document that can be loaded locally, using javascript and Google Charts API
<br>
Pulls JSON data from mining rigs specified as HTTP request parameters
<br>
Plots Hashrate, Temperature, Fan speed
<br>
Drop down selection of polling interval, number of points to plot and theme
<br>
<p align="center">
<img src="https://github.com/crypjo/cast-xmr-monitor/blob/master/img/cast-xmr-monitor-theme-dark.png" width="600">
<br><br>
<img src="https://github.com/crypjo/cast-xmr-monitor/blob/master/img/cast-xmr-monitor-theme-light.png" width="600">
</p>

Enable --remoteaccess for cast-xmr to enable JSON data retrieval

To use open local file in browser and pass mining rigs IPs or names
<br><br>
&nbsp;&nbsp;file:///d:/Path/cast-xmr-monitor.html?miner=miner1&miner=miner2&miner=miner3
<br><br>
&nbsp;&nbsp;file:///d:/Path/cast-xmr-monitor.html?miner=192.168.1.225&miner=192.168.1.102
<br><br>
Supports specifying initial values for chart parameters.  These are specified by the 0 based index of the item in the drop down
<br><br>
&nbsp;&nbsp;file:///d:/Path/cast-xmr-monitor.html?interval=2&points=3&theme=1&fitToPage=true&miner=miner1&miner=miner2&miner=miner3
<br><br>
Parameters Supported:
<ul>
<li>miner - IP or machine name</li>
<li>interval - 0 based index</li>
<li>points - 0 based index</li>
<li>theme - 0 based index</li>
<li>fitToPage - true or false</li>
</ul>
<br>
Added theme select for night view support
<br>
Added Fit to Page option to enable scrolling for large number of miners

v0.4 
<ul>
<li>Fixed multiple refresh of miner stats</li> 
<li>Added Total hashrate for all miners</li> 
</ul>