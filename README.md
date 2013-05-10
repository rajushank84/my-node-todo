
Steps
=====

- git clone the app, cd into the folder where the apps files were cloned


- npm install


- Set up your mongodb:
	1. Run mongo locally and change dataUtils.js -> lib/getDbDetails() -> configuration to 	'local', OR
	2. Create an account in mongolab and enter your credentials, URL and port from mongolab in lib/dataUtils.js -> getDbDetails() 


- node server.js


- go to localhost:8000 using a browser

