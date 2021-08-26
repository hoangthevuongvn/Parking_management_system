Parking_management
==================

Parkingmanagement with node server NODE-RED

### About

This is your project's README.md file. It helps users understand what your
project does, how to use it and anything else they may need to know.

Getting started:

Prerequisites
To install Node-RED locally you will need a supported version of Node.js.

Installing with npm
To install Node-RED you can use the npm command that comes with node.js:

sudo npm install -g --unsafe-perm node-red
If you are using Windows, do not start the command with sudo.

That command will install Node-RED as a global module along with its dependencies.

You can confirm it has succeeded if the end of the command output looks similar to:

+ node-red@1.1.0
added 332 packages from 341 contributors in 18.494s
found 0 vulnerabilities

Installing with docker
To run in Docker in its simplest form just run:

docker run -it -p 1880:1880 --name mynodered nodered/node-red
/////////////////////////////////////////////////////////////
Running
Once installed as a global module you can use the node-red command to start Node-RED in your terminal. You can use Ctrl-C or close the terminal window to stop Node-RED.

$ node-red

Welcome to Node-RED
===================

30 Jun 23:43:39 - [info] Node-RED version: v1.3.5
30 Jun 23:43:39 - [info] Node.js  version: v14.7.2
30 Jun 23:43:39 - [info] Darwin 19.6.0 x64 LE
30 Jun 23:43:39 - [info] Loading palette nodes
30 Jun 23:43:44 - [warn] rpi-gpio : Raspberry Pi specific node set inactive
30 Jun 23:43:44 - [info] Settings file  : /Users/nol/.node-red/settings.js
30 Jun 23:43:44 - [info] HTTP Static    : /Users/nol/node-red/web
30 Jun 23:43:44 - [info] Context store  : 'default' [module=localfilesystem]
30 Jun 23:43:44 - [info] User directory : /Users/nol/.node-red
30 Jun 23:43:44 - [warn] Projects disabled : set editorTheme.projects.enabled=true to enable
30 Jun 23:43:44 - [info] Creating new flows file : flows_noltop.json
30 Jun 23:43:44 - [info] Starting flows
30 Jun 23:43:44 - [info] Started flows
30 Jun 23:43:44 - [info] Server now running at http://127.0.0.1:1880/red/
You can then access the Node-RED editor by pointing your browser at http://localhost:1880.

The log output provides you various pieces of information:

The versions of Node-RED and Node.js
Any errors hit when it tried to load the palette nodes
The location of your Settings file and User Directory
The name of the flows file it is using.
Node-RED uses flows_<hostname>.json as the default flows file. You can change this by providing the flow file name as argument to the node-red command.

  
 

