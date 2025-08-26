# Mini Docker Flask

Απλή Flask εφαρμογή που έγινε containerized με χρήση Docker και ανέβηκε στο Docker Hub.

## Περιγραφή
- Εφαρμογή: Flask (επιστρέφει μήνυμα: "Hello from Flask in Docker!!")
- Dockerfile: χρησιμοποιεί `python:3.12-slim`
- Port: 8000
- Εκτελεί την εφαρμογή με `python app.py`

## Οδηγίες εκτέλεσης

Για να τραβήξει κάποιος το image και να τρέξει την εφαρμογή:

```bash
docker pull ekalomoiri/mini-docker-flask:latest
docker run --rm -p 8000:8000 ekalomoiri/mini-docker-flask:latest
