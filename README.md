# smp3-logviewer

<p><b>SMP 3 Extension - Log Viewer</b><br>
The SMP Management Cockpit Extension at hand is purposed to visualize existing SMP server log information within a SAP UI5 Web Application. Moreover, upcoming log messages are added to the user interface in real-time. Several filter and search options are provided. Thus, an efficient error and log message analysis is facilitated.
<br><br>
<p><b>Introduction</b><br>
If you are using SAP Mobile Platform 3 you are likely also using the Management Cockpit which provides you functionality by a browser-based admin UI. Unfortunately, one very important component is not visualized: the SERVER LOG<br><br>

Especially, when debugging problems or developing client/server applications I am looking quite frequently into the server log file. If you cannot open the file itself on the file system (maybe because you do not have file access to the server's log folder), you always have to download the server log as a ".log" file and then open it in a text editor. This process is highly inefficient, because you have to perform the same steps every time you want to see new information in the log...<br><br>

Alina Pollklaesener was working in our team on a solution for this "problem". She developed a SMP Management Cockpit Extension which can be used to visualize the server log. When initially called the SAPUI5 web app is parsing the existing server log and visualizing it in a searchable and filterable table structure. Additionally a "Live Monitoring" can be enabled which establish a Web Socket connection to the SMP server, so that new log entries will be displayed almost in real time inside the web app (without the need to manually refresh the webpage). <br><br>
In following blog entry this scenario is described in detail: <br>
<a href="http://scn.sap.com/docs/DOC-74237">SMP 3 Management Cockpit Extension - Log Viewer</a>
</p>
<p></p>


