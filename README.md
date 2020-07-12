# WebDataCovid19
## Web Data dashboard mit streamlit

Streamlit - eine Python Bibliothek zum Erstellen von Web-(Daten-) Apps.

## Pandemie-Datenexploration
Mit den entsprechenden Daten und Techniken interaktiver Visualisierungen können wir in Python mit der Streamlit Bibliothek sehr schnell ein Daten-Dashboard erstellen.
Folgendes wurde mit ein paar Codezeilen erstellt!

## Laden des Dashboards
Das Laden des Dashboards ist sehr schnell und einfach. Wir installieren zunächst die Bibliothek auf typische Weise:
* pip install streamlit

Erstellen dann ein Python-Skript:
Streamlit als st importieren
* st.title ('Hallo da')

und führen es dann über eine Befehlszeile aus:
* streamlit run yourScriptsFileName.py 

Dadurch wird die Adresse zurückgegeben, die wir in unserem Browser verwenden müssen, um die Webdaten-App anzuzeigen.

z. B.: http://192.168.0.22:8501

## Einführung in die eingebauten Funktionen
### Text anzeigen
Es gibt verschiedene Möglichkeiten, wie wir Text in der Web-App anzeigen können:

# Dies ist ein Titel
## Ein Header ..
### Ein Subheader ..
#### .. oder ein Markdown.

```python
   import streamlit as st
   st.title ('Dies ist ein Titel')
   st.header ('Ein Header ..')
   st.subheader ('Ein Subheader ..')
   st.markdown ('.. oder ein Markdown.')
```
### Mehrfachauswahl
Wir können ganz einfach ein Dropdown-Mehrfachauswahl-Steuerelement einbauen.

```python
   x = multiselect ('anzuzeigender Text', Liste der verfügbaren Optionen, Liste der Standardoptionen)
   # wobei x am Ende dann wieder eine Liste der gewählten Optionen ist
```
### Auswahlfeld

### Schieberegler

### Grafiken

### Interaktive Karte

### Cache für schnellere Ergebnisse


A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A


