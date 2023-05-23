# IDOR-Lab

## WebGoat
```
docker pull webgoat/webgoat
docker run -p 127.0.0.1:8080:8080 -p 127.0.0.1:9090:9090 -e TZ=Europe/Amsterdam webgoat/webgoat
```
Vitkigt att ange 127.0.0.1 vid port mappningen, vi vill inte exponera webbsidan på internetet.  
WebGoat kan nu nås på: http://127.0.0.1:8080/WebGoat
