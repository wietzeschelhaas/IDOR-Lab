# IDOR-Lab

## Juice Shop
```
docker pull bkimminich/juice-shop
docker run -d -p 127.0.0.1:3000:3000 bkimminich/juice-shop
```
Vitkigt att ange 127.0.0.1 vid port mappningen, vi vill inte exponera webbsidan på internetet.  
OWASP Juice Shop kan nu nås på: http://127.0.0.1:3000

Det kan va så att man behöver skapa ett konto för att komma åt t.e.x varukorgen, man behöver då inte ange en riktig mejladress.
### Uppgifter
* Få tillgång till andra användares varukorgar
* Gör en kommentar med admin kontot
* Redigera en befintlig kommentar
