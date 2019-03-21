# gsoc-phoenix-task1
This repository contains the task1 of evaluation assignment for the <b>Phoenix, interactive data visualization - Development of an experiment independent javascript event display framework and data format</b> project posted by Phoenix under CERN HSF organization.

This repository contains one html file that contains the required Java script and html code to:
1. load and rotate the object in Pix.obj file.
2. show an overlay text over the rotating object.
3. select the object on a mouse click and show the information of object on the overlay.

This repository contains a static folder:
1. create a folder three in it and put all the resources of Three.js into it.
2. create a folder obj in it and the obj file into it.

Now, we are all set to use this html file. There is a "python_server.sh" file along with the html file.
This file will start a local server that is necessary to serve the html file to the browser.
To start the server:
1. Open terminal and browse to folder containing the html file. 
2. Type- <i>chmod +x python_server.sh</i> (this will give shell script rights to run)
3. Type- <i>./python_server.sh</i>
4. now open the browser window and type <i>http://localhost:8000</i> and browse to the html file.

for downloading and documentation of three.js please visit <i>https://threejs.org/</i>
