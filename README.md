# Prüfungsaufgabe 1: Decision-Tree
## Starten der Umgebung
Das Notebook kann per mybinder (https://mybinder.org/) geöffnet werden.
Folgende Daten müssen in die Felder eingetragen werden:
- Github Repo: https://github.com/simon1805/Decision-Tree.git
- Git ref: main
- File to open: index.ipynb
## Dokumentation
- Ziel dieses Modells ist es, anhand von Unternehmensdaten aus der Zeit vor dem Börsengang vorherzusagen, ob ein Kreditnehmer sein Darlehen zurückgezahlt hat oder nicht
- Dazu folgt zuerst eine "Explorative Daten Analyse"
- Danach werden die Daten für die Random Forest Klassifikation vorbereitet
- Anschließend wird der Datensatz in Trainings‑ und Testdaten aufgeteilt. Zunächst wird der Entscheidungsbaum trainiert und ausgewertet, bevor abschließend das gesamte Modell mithilfe des Random‑Forest‑Classifiers erstellt und beurteilt wird.
## Erwartetes Ergebnis

- Der Entscheidungsbaum liefert eine erste Klassifikationsleistung (Accuracy, Confusion Matrix).
- Der Random‑Forest‑Classifier erzielt eine höhere Genauigkeit als der einzelne Entscheidungsbaum.
- Es werden typische ML‑Ausgaben erzeugt, z. B.:
  - Klassifikationsmetriken (Accuracy, Precision, Recall)
  - Confusion Matrix
  - Feature‑Importance‑Plot
- Die Ergebnisse sollten reproduzierbar sein, wenn alle Zellen des Notebooks ausgeführt werden.
