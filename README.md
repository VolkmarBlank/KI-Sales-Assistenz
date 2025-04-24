# KI-Assistenz für den IT-Vertrieb (SalesGPT)

Ein Open-Source-Tool, das den gesamten Vertriebs-Workflow im IT-Bereich automatisiert – von der E-Mail-Anfrage bis zum Versand personalisierter Angebote.

---

## 📖 Inhalt

- [Über das Projekt](#über-das-projekt)  
- [Features](#features)  
- [Repo-Struktur](#repo-struktur)  
- [Installation](#installation)  
- [Konfiguration](#konfiguration)  
- [Usage](#usage)  
- [Technologie-Stack](#technologie-stack)  
- [Contributing](#contributing)  
- [Lizenz](#lizenz)  
- [Kontakt](#kontakt)  

---

## Über das Projekt

SalesGPT integriert:
1. **E-Mail-Listener (IMAP)** zur automatischen Erkennung und Klassifizierung eingehender Anfragen.  
2. **ERP-Client** (z. B. NetSuite-Simulation) zum Abruf von Kunden- und Produktdaten.  
3. **Offer Generator** mit Rabattstaffel und Formatierung.  
4. **SMTP-Sender** zum automatischen Versand der Angebote.  
5. **Earned-Value-Dashboard** zur Kontrolle von PV, EV, AC, SV und CPI.

Geplant und umgesetzt in vier Scrum-Sprints, bietet das Projekt End-to-End-Automatisierung für den IT-Vertrieb.

---

## Features

- 📨 **IMAP-basiertes E-Mail-Parsing**  
- 🔍 **Lead Scoring & Gesprächsanalyse** (Machine Learning & Speech-to-Text)  
- ⚙️ **ERP-Datenabruf** via REST-API  
- 🧾 **Dynamische Angebotsgenerierung** mit Staffelrabatten  
- 📤 **SMTP-Versand** der Angebote  
- 📈 **Earned-Value-Kennzahlen** PV, EV, AC, SV, CPI  
- 📑 **Dokumentation** als PDF/PPTX  
- 📓 **Jupyter-Notebooks** für Data-Science-Teile  

---

## Repo-Struktur

```text
/
├── docs/
│   ├── KI-Assistenz-fur-den-IT-Vertrieb.pdf  
│   ├── KI-Assistenz-fur-den-IT-Vertrieb.pptx  
│   └── Projektkennzahlen.docx  
│
├── notebooks/
│   ├── ml_block_4_uebung_1.ipynb  
│   └── Machine_Learning_Tag_2_Projekt_4_Automatisches_Angebot.ipynb  
│
├── src/
│   ├── email_listener.py       # IMAP abfragen & E-Mails parsen  
│   ├── erp_client.py           # NetSuite-API-Simulation  
│   ├── offer_generator.py      # Rabattlogik & Angebotsformat  
│   └── email_sender.py         # SMTP-Versand  
│
├── data/
│   ├── task_dataset.csv        # Beispiel-Datensatz  
│   └── task_dataset_mod.csv    # Modifizierter Datensatz  
│
├── requirements.txt  
└── README.md
