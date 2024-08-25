# DynamoDB CSV Importer

# German version
**DynamoDB CSV Importer** ist ein Tool zur einfachen Übertragung von CSV-Daten in eine Amazon DynamoDB-Tabelle. Es ermöglicht die Zuordnung von CSV-Spalten zu den Attributen einer DynamoDB-Tabelle, konvertiert die Datei in UTF-8 (falls erforderlich), und führt anschließend den Import durch.

## Funktionen

- **CSV-Dateien laden:** Wähle eine CSV-Datei aus, die du in eine DynamoDB-Tabelle importieren möchtest.
- **Spaltenzuordnung:** Weise den Spalten der CSV-Datei die entsprechenden Attribute der DynamoDB-Tabelle zu.
- **Datenkonvertierung:** Die CSV-Datei wird automatisch in UTF-8 konvertiert, falls sie nicht bereits in diesem Format vorliegt.
- **Automatischer Import:** Nach erfolgreicher Konvertierung werden die Daten in die angegebene DynamoDB-Tabelle importiert.
- **Versionsprüfung:** Das Tool prüft automatisch auf neue Versionen und bietet ein Update an, wenn eine neue Version verfügbar ist.

## Voraussetzungen

- .NET Framework oder .NET Core
- Zugriff auf eine Amazon DynamoDB-Tabelle
- Gültige AWS-Anmeldeinformationen

## Installation

1. Lade die neueste Version des Tools von der [Releases-Seite](https://github.com/dhartl-devnerds/DynamoDBCsvImporter/releases) herunter.
2. Entpacke die Datei und führe die `.exe`-Datei aus.

## Nutzung

1. Wähle die CSV-Datei aus, die du importieren möchtest.
2. Weise die CSV-Spalten den entsprechenden Attributen in der DynamoDB-Tabelle zu.
3. Konfiguriere, falls nötig, das Trennzeichen und die Startzeile für den Import.
4. Starte den Import und warte, bis der Prozess abgeschlossen ist.

## Lizenz

Dieses Programm ist frei verfügbar und kann uneingeschränkt heruntergeladen, genutzt und vervielfältigt werden. Der Quellcode bleibt jedoch privat und ist nicht für die Öffentlichkeit zugänglich.

## Autor

Dieses Tool wurde von BulliPapa entwickelt. Bei Fragen oder Problemen kannst du mich über GitHub kontaktieren.

# DynamoDB CSV Importer

# English version
**DynamoDB CSV Importer** is a tool designed to easily transfer CSV data into an Amazon DynamoDB table. It allows mapping of CSV columns to DynamoDB table attributes, converts the file to UTF-8 (if necessary), and then imports the data.

## Features

- **Load CSV Files:** Select a CSV file that you want to import into a DynamoDB table.
- **Column Mapping:** Map the CSV columns to the corresponding attributes of the DynamoDB table.
- **Data Conversion:** The CSV file is automatically converted to UTF-8 if it is not already in that format.
- **Automatic Import:** After successful conversion, the data is imported into the specified DynamoDB table.
- **Version Check:** The tool automatically checks for new versions and offers an update if a new version is available.

## Requirements

- .NET Framework or .NET Core
- Access to an Amazon DynamoDB table
- Valid AWS credentials

## Installation

1. Download the latest version of the tool from the [Releases page](https://github.com/dhartl-devnerds/DynamoDBCsvImporter/releases).
2. Extract the file and run the `.exe` file.

## Usage

1. Select the CSV file you want to import.
2. Map the CSV columns to the corresponding attributes in the DynamoDB table.
3. Configure the delimiter and the starting line for the import if necessary.
4. Start the import and wait for the process to complete.

## License

This program is freely available and can be downloaded, used, and distributed without restriction. However, the source code remains private and is not accessible to the public.

## Author

This tool was developed by BulliPapa. If you have any questions or issues, feel free to contact me via GitHub.
