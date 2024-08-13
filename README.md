# Einfacher Notenrechner für die Sek 1 in Numbers
(Angepasster Rechner auf der Grundlage des Notenrechners von T. Weh)

## Was kann der Notenrechner?
Mit diesem Notenrechner lassen sich die Halbjahresnote und die Ganzjahresnote auf Grundlage zweier schriftlicher Bewertungen und einer für die sonstige Mitarbeit mittels einer eigenen Gewichtung berechnen. Ein weiteres Tabellenblatt berechnet die Note für die sonstige Mitarbeit aus einer optional detaillierten Eingabe von mehreren Leistungen. Daraus lässt sich einfach ein Notenrückmeldungszettel an die Schüler mithilfe des Pages-Dokumentes erstellen (z.B. für Projekte oder Zwischenstände).

- Die Noteneingabe und die Notenausgabe erfolgt dabei mit Tendenznoten (+/-). 
- Gewichtungen können vorgenommen werden (schriftlich/mündlich, ggf. unterschiedliche Gewichtungen der Klassenarbeiten, ggf. unterschiedlichen Gewichtung der Halbjahre)
- Leistungstendenzen in Bezug auf Vornoten werden angezeigt.
- Notensprünge werden angezeigt.
- Statistiken werden angezeigt.

## Empfohlene Vorgehensweise
Vorsicht: Nur Eingaben in die blau hinterlegten Felder machen, es besteht sonst die Gefahr des Überschreibens von Formelfeldern.

Die beiden Dateien *sek1_Notenverwaltung.numbers* und *sek1_sMA_Info.pages* als Vorlagen herunterladen, anschließend kopieren und umbenennen (z.B. Noten_8b_Mathe.numbers und Noten_8b_Mathe.pages).

|  |   |
|  :--- |  :---: |
| Das .numbers-Dokument öffnen und den Reiter *Notenübersicht* wählen. Die Überschrift *Notenübersicht Klasse XY / Fach   (Schuljahr 2024/25)* anpassen. In die blau hinterlegten Felder werden die Namen eingefügt oder aus einem anderen Dokument kopiert (nach dem Kopieren mit der Option *Einsetzen und Stil anpassen* unter *Menü-Bearbeiten* einfügen). Diese Namen werden dann automatisch auch auf die anderen Tabellenblätter übertragen. Klasse und Tutor optional eingeben | ![Bild 1](https://github.com/user-attachments/assets/a7045161-289a-4e38-974d-974e457426a6)|
| Unterhalb der eigentlichen Tabelle im Bereich der Gewichtungen ggf. die entsprechenden Prozentwerte in die blau hinterlegten Felder einstellen (ein Wert pro Gewichtung genügt, der zweite wird automatisch zu 100% ergänzt). Die Standardeinstellungen sind:  schriftlich:mündlich = 40:60, Gleichgewichtung der Klassenarbeiten und Gleichgewichtung der Halbjahre | ![Bild 2](https://github.com/user-attachments/assets/0bb64053-e232-4a80-b8a0-25b013948fec) |
| Die Spalte Vorjahresnoten (optional) eingeben, um sich Tendenzen und Notensprünge in Bezug auf das Vorjahr anzeigen zu lassen. Die schriftlichen Leistungen unter KA Nr.1 und Nr. 2 eingeben, die sonstige Mitarbeit unter sonst. MA. Sollten Noten aus anderen Bereichen kopiert und eingefügt werden, wieder auf das Einfügen mittels *Einsetzen und Stil anpassen* unter *Menü-Bearbeiten* achten, um die Farbformatierungen beizubehalten. Die schriftliche Note wird gemäß der angegebenen Gewichtung für die Klassenarbeiten berechnet und anschließend wird die Gesamtnote für das Halbjahr gemäß der angegebenen Gewichtung schriftlich/mündlich ermittelt. Wird die berechnete Note in der Spalte Korr. korrigiert, so wird diese korrigierte Note als Gesamtnote für das Halbjahr übernommen, andernfalls die berechnete Note. (Besonderheiten: Bleibt ein KA-Feld leer, so wird nur das andere für die Berechnung der schriftlichen Note genutzt, bleiben beide Felder leer, so wird die Gesamtnote nur aus der sonstigen Mitarbeitsnote gebildet. Wird keine Note für die sonstige Mitarbeit angegeben, so wird keine Gesamtnote berechnet. Es besteht die Möglichkeit über einen Haken bei n.b. eine Halbjahresnote bei der Berechnung der Jahresnote nicht zu berücksichtigen| ![Bild 3](https://github.com/user-attachments/assets/0c2b3c00-b5f7-4e23-86d1-2f294523cb27) |
| Die Tendenzen (Pfeile) und Notensprünge (Ausrufezeichen) befinden sich immer vor den enstprechenden Halbjahren. Die Spalten F und G beziehen den Stand des Halbjahres somit auf den des Vorjahres, die Spalten P und Q den Stand des zweiten Halbjahres auf den des 1. Halbjahres.  | ![Bild 4](https://github.com/user-attachments/assets/1cac1de9-c122-40c7-940c-81bbd0ce3ee9) |
| Für das zweite Halbjahr verfährt man analog zum ersten Halbjahr und gibt auch hier wieder die beiden schriftlichen Noten und die der sonstigen Mitarbeit ein. Die gemäß der angegebenen Gewichtung berechnete Gesamtnote des zweiten Halbjahres lässt sich auch hier ggf. korrigieren genauso wie die automatisch berechnete Gesamtnote. Die vier letzten Spalten geben noch einmal die Tendenzen der Ganzjahresnote in Bezug auf die Gesamtnote des zweiten Halbjahres und die Vorjahresnote aus.   |  |
| Das Löschen von eingetragenen Zellinhalten geschieht mittels der Delete/Backspace-Taste. Anschließend sollte sich die Zelle wieder blau färben.   |  |

## Details zur sonstigen Mitarbeit
|  |   |
|  :--- |  :---: |
| Die Namen wurden bereits aus dem Tabellenblatt *Notenübersicht* übernommen. Es kann jeweils ein Titel für die sonstige Mitarbeit in den dafür vorgesehenen blau hinterlegten Zellen vergeben werden. Es muss eine Gewichtung für diese vergeben werden. Die Standardeinstellungen sind zwei mündliche Leistungen ohne Titel, die jeweils mit 50% gewichtet werden. Es ist darauf zu achten, dass sich die Gewichtungen in Prozent zu 100 % addieren, andernfalls wird keine Gesamtnote berechnet. Die hier berechnete Gesamtnote zur mündlichen Mitarbeit wird nicht automatisch in die Tabelle *Notenübersicht* übernommen. Sie ist auch nicht in zwei Halbjahre unterteilt. Zunächst wird davon ausgegangen, dass sich die Eintragungen auf das aktuelle Halbjahr beziehen und die Ergebnisse des vorherigen Halbjahres in der sonstigen Mitarbeitsnote im Tabellenblatt *Notenübersicht* übernommen wurden. Falls gewünscht, lässt sich der Tab *Details sMA* kopieren. | ![Bild 5](https://github.com/user-attachments/assets/550e912f-fdcd-4ded-86f7-5fae1d7f00a6) |

## Rückmeldezettel für Schüler generieren
Der Tab *sMA Info* dient der Vorbereitung von Rückmeldzetteln für Schüler (z.B. für Projektnoten oder den derzeitigen Stand der sonstigen Mitarbeit). Die Namen wurden bereits aus dem Tabellenblatt *Notenübersicht* übernommen. 
|  |   |
|  :--- |  :---: |
| In die Spalte Stand werden nun die Noten eingetragen, die zurückgemeldet werden sollen. Sollten diese aus dem Tabellenblatt *Details sMA* kopiert werden, so wieder auf das Einfügen mit der Option *Einsetzen und Stil anpassen* unter *Menü-Bearbeiten* achten. Die Spalte *Notiz* kann für Bemerkungen an die Schüler genutzt werden. Speichern.  | ![Bild 6](https://github.com/user-attachments/assets/23853d20-9b4d-4891-9e62-d533aa7909e3) |
| Die zweite Download-Datei *sek1_sMA_Info.pages* (vorher umbennenen!) öffen. Die blauen Texte ersetzen (Fach, Datum). Gegebenenfalls Anpassungen am Layout vornehmen aber Vorsicht: Die Felder Nachname und Vorname sowie Note und Bemerkung sind Formularfelder. | ![Bild 7](https://github.com/user-attachments/assets/5bb70bf6-2416-4d0a-b709-4cbbd3c0ce06) |
|Diese muss nun noch mit der Tabelle verknüpft werden. Dazu rechts oben auf *Dokument*, unten in der rechten Spalte auf *Serienbrief*  | ![Bild 8](https://github.com/user-attachments/assets/9dbf4fc1-258f-46ce-9da2-2dea63dfbfcb) |
| Anschließend oben auf das schwarz hinterlegte Feld *Verbinden* | ![Bild 9](https://github.com/user-attachments/assets/7b3c81be-7b07-4518-a953-9f13f5286453) |
|Diese muss nun noch mit der Tabelle verknüpft werden. Dazu rechts oben auf *Dokument*, unten in der rechten Spalte auf *Serienbrief*  | ![Bild 8](https://github.com/user-attachments/assets/9dbf4fc1-258f-46ce-9da2-2dea63dfbfcb) |
| | ![Bild 9](https://github.com/user-attachments/assets/ee2e1a9b-8d89-4f52-9cea-ed599403a037) |



