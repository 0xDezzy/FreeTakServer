﻿<h1>To run this program you require admin privliges</h1>

#1 allow python.exe in firewall
<br>
#2 open whichever port you will be using for connections in firewall
<br>
#3 kill any program already running on whichever port you've decided to use
<br>
#4 open CMD with admin(advisable to have green text on black background)
<br>
#5 cd into whichever directory this file is located
<br>
#6 type the following "beginProgramAsService.py install"
<br>
#7 type "beginProgramAsService.py start"
<br><br>
TROUBLESHOOTING
<br><br>
if you have any issues don't hesitate to bring it up as this program is still in development
<br><br>
1. ERROR: Could not find a version that satisfies the requirement win32serviceutil
<br>
cmd > pip install pywin32
<br><br>
2. Python windows service “Error starting service: The service did not respond to the start or control request in a timely fashion”
<br>
attempt to add python to the system path
<br><br>
side note TAKFreeServer_running_as_service.py can be run independently without being run as service 
