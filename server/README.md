# Run Server
Either run the shell file:
```
./run.sh
```

or directly run the server like this:
```
json-server --watch db.json -d 2000 -p 3001
```

to make the server accessible outside of localhost, add your IP address:
```
json-server --watch db.json -d 2000 -p 3001 --host 192.168.0.100
```


You can also have it listen on any address with --host 0.0.0.0
```
json-server --watch db.json -d 2000 -p 3001 --host 0.0.0.0
```

Use static for static files (images)
```
json-server --watch db.json --static public -d 2000 -p 3001 --host 0.0.0.0
```