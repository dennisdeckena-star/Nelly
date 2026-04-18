# Health – Gesundheits- und Organisationsdaten für Nelly 🐶

Dieser Ordner enthält **alle strukturierten Gesundheits- und Organisationsdaten** für den Nelly‑Agenten.  
Alle Informationen müssen **echt**, **nachweisbar** und **manuell eingetragen** sein.  
Der Agent darf **keine Annahmen**, **keine Diagnosen** und **keine erfundenen Daten** erzeugen.

---

## 📁 Dateien in diesem Ordner

### `veterinarian.yaml`
Enthält die Kontaktdaten der Tierarztpraxis.

Struktur:
- Praxisname  
- Adresse  
- Telefonnummern (normal & Notfall)  
- E‑Mail  
- Hinweise  

Nur echte Daten eintragen. Keine Interpretationen.

---

### `insurance.yaml`
Enthält die Daten der Hundeversicherung.

Struktur:
- Anbieter  
- Versicherungsart  
- Versicherungsnummer  
- Kontakt (Telefon, E‑Mail, Adresse)  
- Hinweise  

Auch hier gilt: Nur reale Informationen eintragen.

---

### `vaccination_record.yaml`
Digitales Impf‑ und Gesundheitsbuch.

Struktur:
- `impfungen`: Liste von Impfungen  
- `entwurmung`: Liste von Entwurmungsbehandlungen  
- `floh_zeckenschutz`: Liste von Schutzbehandlungen  

Ein Eintrag enthält:
- Datum  
- Gültig‑bis‑Datum  
- Erinnerungsvorlauf (z. B. 30 Tage)  

Der Agent darf **nur dann** Erinnerungen oder Kalendereinträge erzeugen, wenn:
- ein echtes Datum vorhanden ist  
- ein echter Erinnerungsvorlauf eingetragen ist  

Keine Berechnungen ohne Daten.

---

## 🧭 Grundregeln

- Keine Diagnosen  
- Keine Vermutungen  
- Keine Ergänzungen ohne reale Grundlage  
- Keine automatischen Berechnungen ohne echtes Datum  
- Der Agent arbeitet **rein organisatorisch**, nicht medizinisch  

---

## 🎯 Zweck dieses Ordners

Der `health/`‑Ordner ermöglicht dem Nelly‑Agenten:

- Gesundheitsdaten strukturiert auszulesen  
- Impf‑ und Behandlungstermine zu verwalten  
- Erinnerungen oder Kalendereinträge zu erstellen (Google/Outlook)  
  – **aber nur**, wenn echte Daten vorhanden sind  

Er bildet die Grundlage für alle organisatorischen Funktionen rund um Nellys Gesundheit.

---

## ✔️ Verantwortliche Nutzung

Alle Daten müssen:
- korrekt  
- aktuell  
- nachvollziehbar  
- manuell gepflegt  

sein.

Der Agent verändert **niemals** bestehende Daten und ergänzt **nichts**, was nicht ausdrücklich eingetragen wurde.
