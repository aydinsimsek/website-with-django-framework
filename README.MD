# About
I created this one page, simple website for the remote monitoring part of the "Smart Connected Cat Feeding & Monitoring System" project.
It contains cat profiles, feeding logs of the cats, battery level of the device and level of the remaining food in the device.
It can be accessed with electronic devices that are connected to the same network with the host device that the Django server is turned on.  

## How to access the website? 
* Download all of the files.
* Install Django.
* Go to line 28 in catfeeding/settings.py and add your computer's IPv4 Address to the "ALLOWED_HOSTS" as below:
`ALLOWED_HOSTS = ['your computer's IPv4 Address']`
* If your firewall is enabled then allow python.exe through the firewall to let python communicate on your network.
* Use the following command to turn on the Django server:
`python manage.py runserver your computer's IPv4 Address:port_number`
* Finally, open up your browser on any electronic device that is connected to the same network with your computer and type `http://your computer's IPv4 Address:port_number` to the address bar. 

So, let's say you have cats at your home, bought this product, have a smart fridge and before grabbing some food from your smart fridge, you wondered when was the last time your cats ate their food then **yes you can access this website even with your smart fridge** :)                     


    
