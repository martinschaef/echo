# echo
For controlling local devices with the Amazon Echo.

###See original instructions below.

## Control your sony smart tv.
Edit the file `netflix.py` and enter the correct IP address of your Sony TV.
My version can be started with `python netflix.py`. Discover the device 
from the Alexa app and then say 

"Alexa, trun on Netflix" 

to start netflix, or 

"Alexa, turn off Netflix"

to turn off the TV. The thing emulates a light switch that triggers 
executes arbitrary code when receiving the Alexa command.

----

Instructions for installation and usage [available on Instructables here](http://www.instructables.com/id/Hacking-the-Amazon-Echo/)

Brought to you by [FabricateIO](http://fabricate.io)

## Quick Start

1. Create a [Python Virtual Environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
2. git clone *this_repo*
3. cd *this_repo*
4. pip install -r requirements.txt
4. python example-minimal.py
6. Tell Echo, "discover my devices"
7. Use Echo's "turn off device" and "device on" to see True/False script output

