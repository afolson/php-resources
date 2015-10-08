# PHPamily

[![Join the chat at https://gitter.im/afolson/php-resources](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/afolson/php-resources?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The aim of this project is to show the connection between people, projects, 
companies, podcasts and all the other bits and pieces of the PHP-Family.

The main idea is to show how all of the parts are connected with one another
by parsing freely available datasources like twitter or github or ... and 
adding those connections to a central datasore. The data can then be adapted 
and searched and serve as raw-data for displaying the connections using d3.

My original idea was to randomly select some node and display any connection 
around it for 2 levels. The user can then click onto a node and then the 2 
levels around that node would be retrieved and added to the display. And 
there should be a search-field to select a different (or additional?) node 
to show the conections for (and the connection to the previously shown one)

## Setup

You will need bower to setup the external libraries. If you do not have
bower installed yet, have a look at http://bower.io for instructions on 
how to install it.

With bower installed you will need to run ```bower install``` inside the
directory where this README-file lies in.

After that you should be up and running and should see the first effort by 
pointing your webbrowser to the ```index.html```-file. Due to the way 
d3 uses AJAX you will need to call the ```index.html```-file through a
webserver!

## Questions

Feel free to open an issue or ping me directly via email, Gitter or IRC
