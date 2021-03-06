# vdb.js

Visual debuggger js (vdb.js) is a flexible library for visualizing data structures written in Javascript. 
 
With vdb.js you can:
* View data structures in a more intuitive way
* Share snapshots of your variable instances

## Quick Start
Download vdb.js:    
```sh
https://github.com/regonics/vdb.js/client/vdb.js
```

Include vdb.js before your source file:
```sh
<script src="vdb.js">
```
##Example Usage
```sh
//tree points to the head node of a binary tree
drawTree(tree);
//Go to console to get URL to visit
```

##Installing a local server
Users also have the option of creating their own server instead of querying ours
```sh
git clone https://github.com/ericsong/vdb.js
cd vdb.js/
npm install
//change vdb.js address to localhost
```

##Run the server
```sh
sudo PORT=80 node server.js
```

##Running Examples

__visual:__ http://ec2-54-242-13-238.compute-1.amazonaws.com/getData?key=19xtf1tu

__code:__ https://raw.githubusercontent.com/ericsong/vdb.js/master/demos/index.html

------------

__visual:__ http://ec2-54-242-13-238.compute-1.amazonaws.com/getData?key=19xtf1u0

__code:__ https://raw.githubusercontent.com/ericsong/vdb.js/master/demos/node1.html

------------

__visual:__ http://ec2-54-242-13-238.compute-1.amazonaws.com/getData?key=19xtf1u1

__code:__ https://raw.githubusercontent.com/ericsong/vdb.js/master/demos/node2.html

------------

__visual:__ http://ec2-54-242-13-238.compute-1.amazonaws.com/getData?key=19xtf1u2

__code:__ https://raw.githubusercontent.com/ericsong/vdb.js/master/demos/node3.html
