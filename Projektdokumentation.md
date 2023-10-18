# Projekt-Dokumentation

Blentin, Gian-Marco

## 1 Informieren

### 1.1 User Stories



| US-№ |   Beschreibung                       |
| ---- |   ---------------------------------- |
| 1     | Als User möchte ich, dass ich von einem Block zum nächsten springen kann.                                     |
| 2    | Als User möchte ich, dass wenn der Spieler stirbt, er schnell respawnt.                           |
| 3     | Als User möchte ich, dass es Checkpoints gibt, wo der Spielfortschritt gespeichert wird.                |
| 4    | Als User möchte ich, dass das Spiel schön aussieht.              |
| 5    | Als User möchte ich, dass nach jedem Checkpoint das Level steigt.              |
| 6  | Als User möchte ich, dass jedes Level schwieriger wird.              |
### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |Spieler steht|W+Space|Spieler ist auf dem nächsten Blocks.        |
| 2.1 |Spieler stirbt |-         |Spieler spawnt am Checkpoint.               |
|3.1 |Spieler steht auf Checkpoint | -      |Fortschritt wird gespeichert.          |
|4.1 |- | -      |-        |
|5.1 |Spieler erreicht neuen Checkpoint | -      |Level wird gespeichert.        |
|6.1 |Spieler erreicht neuen Checkpoint  | -      |Nächstes Level wird schwieriger.       |

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |18.10.2023|Gian-Marco, Blentin|Spieler kann von einem Block zum nächsten springen.| 135 min              |
| 2.A  |18.10.2023|Blentin| spawnen            |    45 min           |
| 6.A  |25.10.2023|Blentin, Gin-Marco| Level wird schwieriger.          |    45 min           |
| 5.A  |25.10.2023|Blentin, Gian-Marco| Level steigt nach jedem Checkpoint            |    45 min           |
| 4.A  |25.10.2023|Blentin| Design           |    45 min           |
| 5.A  |25.10.2023|Blentin, Gian-Marco| Level steigt nach jedem Checkpoint            |    45 min           |
| 1.A  |25.10.2023|Gian-Marco, Blentin|Spieler kann von einem Block zum nächsten springen.| 135 min              |
| 6.A  |01.11.2023|Blentin, Gin-Marco| Level wird schwieriger.          |    45 min           |
| 1.A  |01.11.2023|Gian-Marco, Blentin|Spieler kann von einem Block zum nächsten springen.| 135 min              |
| 3.A  |01.11.2023|Gian-Marco| Spielfortschritt        |    45 min           |

Total: 715 min



## 3 Entscheiden
Wir möchten ein Spiel auf Roblox erstellen und mit Lua programmieren.




## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 23.08.2023|Blentin Tosuni|45 min  | 20 min                    |
| 2.A  |23.08.2023       | Blentin Tosuni          |45 min               | 25 min                  |
| 3.A  |30.08.2023       | Blentin Tosuni          |45 min               | 20 min                  |
| 4.A  |30.08.2023       | Blentin Tosuni          |45 min               | 20 min                  |
| 5.A  |30.08.2023       | Blentin Tosuni          |45 min               | 90 min                  |
| 6.A  |30.08.2023       | Blentin Tosuni          |45 min               | 90 min                  |

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |30.08.2023|OK |Blentin Tosuni        |
| 2.1  |30.08.2023|OK |Blentin Tosuni        |
| 3.1  |30.08.2023|OK |Blentin Tosuni        |
| 4.1  |30.08.2023|OK |Blentin Tosuni        |
| 5.1  |30.08.2023|OK |Blentin Tosuni        |
| 6.1  |30.08.2023|OK |Blentin Tosuni        |



## 6 Code
