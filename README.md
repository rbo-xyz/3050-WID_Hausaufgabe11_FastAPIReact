# Koordinatentransformation mit eigener Lokalen API

Mithilfe der WebApp kann eine Transformation von Koordinaten gerechnet werden.

## Getting Started

1. Repository klonen:

   ```
   git clone
   ```

   Alternativ kann auch mithilfe des Github-Desktop das Repository geklont werden

2. benötigte Programme:

   - node.js
   - anaconda
   - VSCode

### API

1. Erstellung eines Anaconda-Enviorment

   ```
   conda create -n 3050WID_backend_py312 python=3.12 -c conda-forge
   ```

2. Installation der benötigten Module:

   ```
   pip install fastapi[standard]
   ```

   ```
   pip install pyproj
   ```

3. API-Server starten:

   In der anaconda-Promt mit `cd <pfad>/api` in den Ordner der API navigieren `(./api)`

   Anschliesen erstelltes Enviorment aktivieren

   ```
   conda activate 3050WID_backend_py312
   ```

   Server starten

   ```
   fastapi dev api.py
   ```

### Frontend-Server

1. `node.js`-Module installieren:

   ```
   npm install
   ```

2. Webserver starten

   ```
   npm run dev
   ```

3. Auf den angezeigten localhost-Link klicken und die Webseite öffnen

## Funktionsweise

Mithilfe des gewählten Transformators können Koordinaten aus den Inputfelder auf Knopfdruck in ein anderes Koordinatensystem gewechselt werden.

Die Transformation funktioniert auf Basis der eigner API im `api`-Ordner

## Info

Diese Aufgabe bassiert auf der Hausaufgabe 6.

<https://github.com/rbo-xyz/3050-WID_Hausaufgabe6>
