# AdvancedML
## Voraussetzungen
Auf GitHub ist der gesamte Code mit den gespeicherten Modellen. Die hier angehängte Abgabe dient lediglich zum Abgleich. Hier sind keine Modelle gespeichert! (https://github.com/sobu02/AdvancedML/tree/main)

!!! In der kaggle.json muss zum Herunterladen der Daten der Nutzername und der Key eingetragen werden. Dafür wird ein Kaggle Account benötigt (https://www.kaggle.com). Über die **Settings** beim Nutzer kann bei **API** ein Token erstellt werden. In der erstellten kaggle.json können der Nutzername und der Key kopiert und eingefügt werden, bzw. die ganze kaggle.json kann ersetzt werden.

## Beschreibung

Bei diesem Projekt handelt es sich um eine Abgabe im Modul Advanced Applied Machine Learning. Alle genutzten Quellen sind direkt im Code angegeben, nach den neuen Zitierrichtlinien für Code der DHBW. Die Begründung des Themas und die ethische Betrachtung finden nach der Datenanalyse statt. Die Modelle sind alle gespeichert. Der Code kann so auskommentiert werden, dass er lauffähig ist. Die Ausführzeit im aktuellen Zusatnd (Training des Neuronalen Netzes / SVM / XGBoost auskommentiert) beträgt 18 Minuten.

Der Datensatz basiert auf dem Kaggle-Datensatz https://www.kaggle.com/datasets/farjanakabirsamanta/skin-cancer-dataset und wird im Code weiter angepasst.

Nach der Datenbetrachtung wurde sich dafür entschieden den Datensatz zu nutzen, da hierbei ein relevantes Thema behandelt wird. Eine frühe Erkennung von Hautkrebs ist sehr wichtig, da Hautkrebs bei früher Erkennung gut behandelbar ist. Wurde eine auffällige Stelle gefunden, bei der es sich um Hautkrebs handelt, muss dieser zunächst klassifiziert werden.

Die Fragestellung dieses Projekts lautet daher: ***Mit welcher machine learning Methode lassen sich Hautkrebsarten anhand Bilder mit zusätzlichen Informationen am genausten und effizientesten klassifizieren?***

Der ausgewählte Datensatz enthält bereits einige zusätzliche Metadaten, wie das Geschlecht und das Alter der Patienten. Diese Metadaten werden im Projekt berücksichtigt und in die Analyse und die Klassifizierung als zusätzliche Features mit einbezogen. Der Datensatz kann von Kaggle heruntergeladen werden, oder über die Kaggle-API genutzt werden. Die zusätzlichen Features, wie die Form und die Farbe des Hautkrebs, werden durch den Code erstellt und hinzugefügt. Im folgenden Code werden die Daten vorbereitet und zusätzliche Features extrahiert. Anschließend werden drei Methoden verglichen, wie der Hautkrebs klassifiziert werden kann.


