# express-stormpath-project

1. go to stormpath.com and make an account.
2. log in and create an api key. then download it and put it somewhere safe.
3. git clone this repository. (also unzip any file)
4. go to the directory and type in $npm install
5. type this and replace the xxx with the api key id you got (no spaces between the = and x) 
6. $export STORMPATH_CLIENT_APIKEY_ID=xxx
7. replace the xxx with your api-key secret $export STORMPATH_CLIENT_APIKEY_SECRET=xxx
8. go to the application tab on your stormpath account. click my application then use that href in place of the xxx 
9. $export STORMPATH_APPLICATION_HREF=xxx
10. thats it just type this! $node server.js


(havent put how I got google authentication in)
