npm i
this will install all dependencies for your project.
this only needs to be done once during project initialization. (unless the package.json has changed).
ng serve -o
this will run the project and open a new tab in chrome.

--------------------

Choosing your local backend:
ng serve -c local (calls http://localhost:8080/Metaproject/)

Choosing test server backend:
ng serve (calls http://metaproject-tst.in.fhkn.de:8080/Metaproject/)