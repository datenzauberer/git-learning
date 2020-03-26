# Erste Schritte mit git

## Installation

Bevor Du mit git starten kannst, musst Du git erst mal installieren:

```
apt-get install git
```

Evtl. musst Du auch `sudo apt-get install git` aufrufen.

Am besten legst Du Dir ein Verzeichnis an, in welchem Du Deine "repositories" ablegst, mit:

```
mkdir -p ~/repositories
cd ~/repositories
```

Nun kannst Du Dir dieses Repository holen mit:

```
git clone https://github.com/datenzauberer/git-learning.git
cd git-learning
# Anzeige dieser Datei
cat README.md
```

## Links
Wie git funktioniert kannst Du hier lesen:

[Buch Pro Git](https://git-scm.com/book/de/v2) Wenn Du das liest bist Du auf dem besten Weg zum Hacker
[kleiner Git Spickzettel](https://github.github.com/training-kit/) Deutsch oder Englisch (für Hacker) auswählen
[Git Übungen und Videos](https://gist.github.com/peterhurford/4d43aa5d6de114c0c741ba664c9c5ff5)


## Kleine Aufgaben

* Erstelle ein eigenes lokales  Repository
* Erstellen eine README.md Datei in diesem Repository
* Erstelle Deinen ersten commit
* Erstelle einen github Account
* Erstelle Dein erstes github repository
