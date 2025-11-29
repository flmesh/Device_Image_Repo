# This the repo for the Flmesh meshtastic map devices to allow for easier intergration in other regional groups maps

I'll be updating it periodically with new images, as new devices come online with firmware support. <br>
Pull requests with new images and updated images are welcome.


* The goal is to keep this up to date with the highest quality images for each device available, preferably with fully transparent backgrounds, to improve map quality when using with dark mode browers.


## How to use
This data is provided for users that run variations of Liam Cottle's [Meshtatic Map](https://github.com/liamcottle/meshtastic-map)<br>
When there is updates to hardware or roles, please copy and replace the data in the files of <br> `meshtastic-map\src\json` & `meshtastic-map\src\public\images` with those that are found here.
Then also update the portbuf files under `meshtastic-map\src\protos\meshtastic` <br>
That will then update the images and roles to display correctly with the new additions added to the map.
