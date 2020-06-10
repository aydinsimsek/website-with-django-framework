# About
I created this one page, simple website for the remote monitoring part of the "Smart Connected Cat Feeding & Monitoring System" project.
It contains cat profiles, feeding logs of the cats, battery level of the device and remaining food in the device.
It can be accessed with electronic devices that are connected to the same LAN with the host device that the django server is turned on.  

## How to access the website?
* Download all of the files
* Install Django
* Go to line 28 in catfeeding/settings.py and add your computer's IPv4 Address to the "ALLOWED_HOSTS" as below:
`ALLOWED_HOSTS = ['IPv4 Address']`

    
