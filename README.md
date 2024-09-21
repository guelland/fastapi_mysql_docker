# FastAPI MySQL Docker

Dieses Projekt bietet eine Beispielanwendung, die FastAPI mit MySQL in einem Docker-Container integriert.

## Inhaltsverzeichnis

- Installation
- Verwendung
- Projektstruktur
- Konfiguration
- Beitragen
- Lizenz

## Installation

1. **Repository klonen:**
    ```bash
    git clone https://github.com/integration-developer-de/fastapi_mysql_docker.git
    cd fastapi_mysql_docker
    ```
2. **Docker-Container starten:**
    ```bash
    docker-compose up --build
    ```

## Verwendung

Nach dem Starten des Docker-Containers ist die Anwendung unter http://localhost:8000 erreichbar.

### API-Tests

Du kannst die API mit Postman oder einem anderen API-Client testen.

- **API Root:** http://localhost:8000
- **Swagger-Dokumentation:** http://localhost:8000/docs/v1
- **Redoc-Dokumentation:** http://localhost:8000/redoc/v1

#### Verwendung von Postman:

1. **API-Sammlung importieren:** Du kannst Anfragen manuell in Postman erstellen oder eine vorhandene Sammlung importieren, falls verfügbar.
2. **Neue Anfrage erstellen:** Methode (GET, POST, etc.) und URL (z.B. http://localhost:8000/items) festlegen.
3. **Anfrage senden:** Die Antwort anzeigen und verschiedene Endpunkte testen.

## Projektstruktur

```plaintext
fastapi_mysql_docker/
├── app/
│   ├── main.py
│   ├── models.py
│   ├── schemas.py
│   ├── crud.py
│   └── database.py
├── docker-compose.yml
├── Dockerfile
└── README.md
```

## Author

Created by integration-developer.de

## License

This project is licensed under the [Feel free to experiment] license.
