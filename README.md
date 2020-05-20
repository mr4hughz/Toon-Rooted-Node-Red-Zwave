# Toon-Rooted-Node-Red-Zwave
Toon-Rooted-Node-Red-Zwave


original project https://gist.github.com/EvertDekker/a4703e4a63992bbeb80f76219cddc5e4

Node Red Flow to import Zwave data

rooted toon updated to version 5.28.9

it shows 
- gas usage
- city heat (stadsverwarming) 
--- for each following "eletric" ---> Now & today 
- default (single "dail") deliverd 
- default (single "dail") solar (returned) 
- dual (dual "dail") normal & low deliverd 
- dual (dual "dail") normal & low solar 

see example image for full overview (note what is not displayed = not working (for me) 

debug/alterations (if needed) 
turn on --> GetZwaveDevices-debug to see the "internalAddress" 

dev 3.x will show (1 to 8 in this case) will show the value you might need 

you can savely delete the UI parts, I only added them for full overview 

---- todo 
* calculate/beautify the output into more neat figures .. 

ps I am thinking about changing this into a domoticz plugin. 


