## Setting the port no
Go to apache-folder-name/conf and open ```server.xml``` search 'connector port' replace 8080 by desired port number.

## Starting the server
Go to apache-folder-name/bin run ```sh startup.sh```

## Where to store html files?
Store all web files in the folder apache-folder-name/webapps/ROOT/

## How to access the files in ROOT?
- Open browser
- Go to ```localhost:8080/path_to_your_file```
  - here ```8080``` can be replaced by the port number you've specified
  - ```path_to_your_file``` means relative path from the ```ROOT/``` folder. 
  Ex. if path is ROOT/hello.html url will be localhost:8080/hello.html. 
  Similarly if present inside a folder say test( i.e. ROOT/test/hello.html) url will be localhost:8080/test/hello.html

