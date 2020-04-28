# MADH: Math for Digital Humanities students

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/realjanpaulus/madh/master)

# Bedienungsanleitung

Um die Tutorials nutzen zu können, gibt es zwei Möglichkeiten: Die Offline-Nutzung (empfohlen) und die Online-Nutzung mithilfe von **Binder**. Die folgende Installationsanleitung bezieht sich nur auf die Offline-Nutzung. Für die Online-Nutzung muss lediglich auf das [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/realjanpaulus/madh/master) Logo geklickt werden. Sollte diese Option genutzt werden, überspringen Sie den nächsten Schritt "Installationsanleitung (Anfänger)".

Offline-Nutzung mit Jupyter Lab wird nicht unterstützt. Bei der Benutzung von Jupyter Lab können Javascript Befehle wie in Quizzen nicht dargestellt werden. Für die Verwendung mit Jupyter Lab muss eine Erweiterung installiert werden (siehe <a href="https://stackoverflow.com/questions/49542417/how-to-get-ipywidgets-working-in-jupyter-lab">Stackoverflow</a>).

## Installationsanleitung (Anfänger)

### Download

Über Button <img src="src/img/clone_download.png" alt="clone_download-icon" width="60" height="12"/> in der rechten oberen Ecke dieser Seite kann das Projekt geklont oder gedownloadet werden ("Download ZIP"). Sollte es gedownloadet werden, muss das ZIP-Archiv entpackt werden. Mit dem Terminal muss in das entsprechende Verzeichnis navigiert werden (Tutorial dafür: TODO).


### Installation des gedownloadeten Projekts

Erforderlich: Python 3.6+

#### Installation mit conda (empfohlen für Anfänger)
Diese Option wird für Anfänger empfohlen, die **Anaconda** installiert haben.

`conda install -r requirements.txt` (TODO: requirements installieren)

#### Installation mit pip

`pip install -r requirements.txt` (TODO: requirements installieren)

#### Installation mit pipenv

Pipenv erstellt und verwaltet automatisch eine Virtuelle Umgebung für dieses Projekt. Installation erfolgt folgendermaßen:

```
$ pip install pipenv
```

Um die Abhängigkeiten des Projekts zu installieren:

```
$ pipenv install
```

Sie können eine Shell mit folgendem Befehl erzeugen:

```
$ pipenv shell
```




TODO:
- Anleitung, wie man Requirements installiert
- BESSER: alles in einem installieren (vllt zu aufwendig?)
- binder? ja