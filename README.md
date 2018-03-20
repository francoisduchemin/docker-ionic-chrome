# Latest Ionic
### based on the latest Cordova with the latest Android, the latest Node.js and the latest Chrome
----
### Pull from Docker Hub
```
docker pull francoisduchemin/ionic-chrome:latest
```

### Build from GitHub
```
docker build -t francoisduchemin/ionic-chrome github.com/francoisduchemin/docker-ionic-chrome
```

### Run image
```
docker run -it francoisduchemin/ionic-chrome bash
```

### Use as base image
```Dockerfile
FROM francoisduchemin/ionic-chrome:latest
```


----

![One does not simply use latest](https://i.imgflip.com/1fgwxr.jpg)