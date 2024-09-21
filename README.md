Zensus 2022: Datenarchitektur für Bildung und Erwerbstätigkeit

Projektbeschreibung
Dieses Projekt zielt darauf ab, die Daten des Zensus 2022 in eine strukturierte Form zu überführen, um Analysen zu Bildung und Erwerbstätigkeit in Deutschland durchzuführen. Die Daten werden mithilfe eines ETL-Prozesses (Extract, Transform, Load) aus einer Excel-Datei extrahiert, transformiert und in eine relationale PostgreSQL-Datenbank geladen. Anschließend werden die Daten in einem Sternschema organisiert, um schnelle und effiziente OLAP-Abfragen (Online Analytical Processing) zu ermöglichen.
Das Projekt ist Teil der Studienarbeit im Rahmen des Moduls Dateninfrastruktur an der Digital Business University of Applied Sciences.

Features
ETL-Prozess: Extrahiert Daten aus Excel-Dateien, transformiert sie und lädt sie in eine PostgreSQL-Datenbank.
Normalisierung: Die Daten werden in die 2. Normalform (2NF) überführt, um Redundanzen zu minimieren und die Datenintegrität zu maximieren.
Sternschema: Die Datenbank wurde mit einem Sternschema modelliert, das eine Faktentabelle und mehrere Dimensionstabellen enthält.
OLAP-Analyse: Die Organisation der Daten erlaubt schnelle analytische Abfragen, um Erkenntnisse über die Bildungs- und Erwerbssituation in Deutschland zu gewinnen.

Technologien
Python: Wird verwendet, um die Daten zu extrahieren und zu transformieren (Libraries: pandas, numpy, sqlalchemy, psycopg2).
PostgreSQL: Relationale Datenbank zur Speicherung und Analyse der Daten.
pgAdmin: Verwaltung der PostgreSQL-Datenbank.
Sweetviz: Für Profiling Reports und visuelle Analysen der Daten.
VS Code: Entwicklungsumgebung.

Installationsanweisungen
1. Repository klonen: git clone <repository-url>
2. Erforderliche Pakete installieren: Stelle sicher, dass du alle benötigten Python-Pakete aus der requirements.txt installierst: pip install -r requirements.txt
3. PostgreSQL einrichten:
Installiere und starte einen PostgreSQL-Server.
Erstelle eine neue Datenbank und richte einen Benutzer ein.
4. Datenbank-Schema erstellen: Verwende das mitgelieferte Skript, um das Sternschema in PostgreSQL zu erstellen.

Nutzung
ETL-Prozess starten: Verwende das Jupyter-Notebook main.ipynb, um den ETL-Prozess zu starten. Dies extrahiert die Daten, transformiert sie und lädt sie in die PostgreSQL-Datenbank.

Analysen durchführen: Nachdem die Daten geladen wurden, können SQL-Abfragen oder OLAP-Tools verwendet werden, um Analysen zu Bildung und Erwerbstätigkeit in Deutschland durchzuführen.

Datenquellen
Die verwendeten Daten stammen aus dem Zensus 2022, veröffentlicht von den Statistischen Ämtern des Bundes und der Länder. Sie enthalten Informationen zur Bildung und Erwerbstätigkeit in Deutschland.

Lizenz
Dieses Projekt steht unter der MIT License.

Autorin
Sabine Wildemann
Digital Business University of Applied Sciences

