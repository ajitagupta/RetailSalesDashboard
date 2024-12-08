
# **Retail Sales Dashboard**

Ein interaktives Power BI-Dashboard zur Analyse von Verkaufsdaten. Dieses Dashboard bietet Einblicke in den Gesamtumsatz, die regionale Verkaufsleistung, monatliche Trends und die Performance einzelner Produkte.

---

## **Inhalt**

- [Überblick](#überblick)
- [Funktionen](#funktionen)
- [Voraussetzungen](#voraussetzungen)
- [Installation](#installation)
- [Datensatz](#datensatz)
- [Verwendung](#verwendung)
- [Screenshots](#screenshots)
- [Geplante Erweiterungen](#geplante-erweiterungen)
- [Lizenz](#lizenz)
- [Autor](#autor)

---

## **Überblick**

Dieses Projekt wurde entwickelt, um Verkaufsdaten eines fiktiven Einzelhandelsunternehmens interaktiv zu analysieren. Es bietet nützliche Einblicke, wie Umsätze nach Regionen, Produkten und Zeiträumen aufgeschlüsselt werden können. Es ist ideal für Anfänger in Power BI oder für diejenigen, die ein Portfolio-Projekt erstellen möchten.

---

## **Funktionen**

- **Gesamtumsatz**: Darstellung des gesamten Umsatzes in einer leicht verständlichen Kennzahl.
- **Regionale Verkaufsanalyse**: Ein gruppiertes Balkendiagramm zeigt die Verkaufszahlen nach Regionen.
- **Monatliche Trends**: Ein Liniendiagramm visualisiert Umsatztrends über die Monate hinweg.
- **Produktanalyse**: Ein Kreisdiagramm stellt die Performance einzelner Produkte dar.
- **Interaktive Filter**: Nutzen Sie Slicer, um Daten nach Region und Produkt zu filtern.

---

## **Voraussetzungen**

- Power BI Desktop (Version 2024 oder neuer)
- Ein grundlegendes Verständnis von Power BI
- CSV-Datensatz (bereitgestellt in diesem Repository)

---

## **Installation**

1. Laden Sie das Repository herunter:
   ```bash
   git clone https://github.com/ajitagupta/RetailSalesDashboard.git
2. Öffnen Sie Power BI Desktop.
3. Importieren Sie die Datei ```RetailSalesDashboard.pbix```.
4. Überprüfen Sie die Datenverbindungen und stellen Sie sicher, dass der Datensatz ```SalesData.csv``` korrekt eingebunden ist.

---

## **Datensatz**

Der Datensatz `SalesData.csv` enthält Verkaufsinformationen und folgende Felder:

| **Feldname**           | **Beschreibung**                        |
|-------------------------|------------------------------------------|
| **Datum**              | Verkaufsdatum                           |
| **Region**             | Verkaufsregion (z. B. Nord, Süd)        |
| **Produkt**            | Produktkategorie (z. B. Laptop)         |
| **Verkaufte Einheiten** | Anzahl der verkauften Produkte          |
| **Einzelpreis**        | Preis pro Einheit                       |
| **Gesamtumsatz**       | Umsatz pro Verkaufseintrag              |

---

## **Verwendung**

1. Öffnen Sie die Power BI-Datei `RetailSalesDashboard.pbix`.
2. Importieren Sie den bereitgestellten Datensatz `SalesData.csv`.
3. Stellen Sie sicher, dass die Datentypen korrekt sind:
   - **Datum**: Datum/Uhrzeit
   - **Region**: Text
   - **Produkt**: Text
   - **Verkaufte Einheiten**: Ganzzahl
   - **Einzelpreis**: Dezimalzahl
   - **Gesamtumsatz**: Dezimalzahl
4. Nutzen Sie die interaktiven Filter (Slicer), um Daten dynamisch zu analysieren:
   - **Region**: Filtert die Daten nach Regionen.
   - **Produkt**: Zeigt die Umsätze für ausgewählte Produkte an.
5. Passen Sie das Dashboard nach Bedarf an:
   - Ändern Sie Farbschemata und Diagrammeinstellungen.
   - Fügen Sie zusätzliche Visualisierungen oder Filter hinzu.
6. Exportieren Sie das Dashboard als PDF oder veröffentlichen Sie es im Power BI Service.


