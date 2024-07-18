# Arcade Hall 

Arcade Hall ist eine Spielewebsite mit integrierter Datenbank, die sowohl in PHP als auch in Node.js verfügbar ist. Nutzer können verschiedene Spiele und Anwendungen nutzen, wobei jeder neu registrierte Benutzer zu Beginn Tickets erhält, die zum Spielen und Gewinnen weiterer Tickets eingesetzt werden können. Zusätzlich können durch das Spielen weitere Tickets gewonnen werden.

Die README-Datei erklärt, worum es in diesem Projekt geht und wie man es benutzt. Sie hilft neuen Nutzern und Entwicklern, sich schnell zurechtzufinden und loszulegen.

## Installation

### Visual Studio Code

Visual Studio Code ist ein leistungsstarker und plattformübergreifender Code-Editor. Du kannst Visual Studio Code von der offiziellen Website herunterladen und installieren: [Visual Studio Code](https://code.visualstudio.com/)

### Installation von XAMPP

XAMPP ermöglicht das Installieren und Konfigurieren des Webservers Apache mit der Datenbank. Hier zum Download von [XAMPP](https://www.apachefriends.org/de/index.html)

### Installation von node.js

Über den folgenden Link, kannst du dir von der offiziellen Website, node.js herunterladen. [Node.js](https://nodejs.org/en)

1. Starte den Installer: Doppelklicke auf die heruntergeladene .msi-Datei, um die Installation zu starten.
2. Folge den Anweisungen: Der Installationsassistent führt dich durch den Installationsprozess.
3. Zielverzeichnis: Wähle das Zielverzeichnis oder lass die Standardeinstellungen unverändert.
4. Node.js-Komponenten auswählen: Lass alle Standardkomponenten ausgewählt, insbesondere npm package manager.
5. Installationsort festlegen: Wähle das Zielverzeichnis oder lass die Standardeinstellungen unverändert.
6. Installation abschließen: Klicke auf "Installieren" und warte, bis der Installationsprozess abgeschlossen ist.

## Projektordner öffnen

1. Lade den Projektordner herunter oder klone ihn von diesem Repository.
2. Öffne Visual Studio Code.
3. Wähle "Datei" und dann "Ordner öffnen" aus dem Menü.
4. Navigiere zum heruntergeladenen Projektordner und wähle ihn aus.

## Datenbank einrichten

1. Die Datei arcade.sql herunterladen.
2. Stellen Sie sicher, dass XAMPP mit Apache und MySQL gestartet ist.
3. Gehen sie auf die Datenbank Seite mit der URL: http://localhost/phpmyadmin/
4. Einloggen und Datenbank auswählen: Melde dich bei phpMyAdmin an und wähle die Datenbank aus, in die du importieren möchtest.
5. Importieren auswählen: Klicke auf "Importieren" oben im Menü.
6. Datei auswählen: Klicke auf "Datei auswählen" und suche die SQL-Datei auf deinem Computer, die du importieren möchtest.
7. Import starten: Klicke auf "OK", um den Importvorgang zu starten. phpMyAdmin wird die Datei hochladen und die darin enthaltenen SQL-Befehle ausführen.

## Website aufrufen (PHP Version)

Um die PHP-Version zu starten, folgen Sie diesen Schritten:

1. Stellen Sie sicher, dass XAMPP mit Apache und MySQL gestartet ist.
2. Öffne den Projektordner namens "Aracde Hall Project PHP" in Visual Studio Code.
3. Navigiere in den Unterordner `arcade php`.
4. Doppelklicke auf die `index.php`-Datei, um die Website in deinem Standardbrowser zu öffnen.

## Website aufrufen (Node Version)

Um die Node.js-Version zu starten, folgen Sie diesen Schritten:

1. Stellen Sie sicher, dass XAMPP mit Apache und MySQL gestartet ist.
2. Öffnen Sie ein Terminal und navigieren Sie zum Projektordner.
3. Navigieren in der Visual Studio Code Anwendung zu der Kategorie Terminal, und gebe den folgenden Command ein (bei Punkt 4 -> ganz wichtig!), um die notwendigen Packages herunterzuladen
4. -> npm install express body-parser mysql express-session multer ejs
5. Geben Sie den Befehl node server.js (falls es nicht funktioniert: node .\server.js) ein, um den Server zu starten.
6. Die Webseite ist unter localhost:3000 erreichbar.

## Quellen

Folgende Quellen haben bei der Entwicklung und beim Erlernen der Website geholfen:

- [W3Schools](https://www.w3schools.com/)
- [ChatGPT](https://www.chatgpt.com/)
- [YouTube](https://www.youtube.com/)

## Erstellt von

Lukas Zasada & Dominik Pawel Jurczak
