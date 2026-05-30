# 🛡️ ComplianceGuard Pro

> **GDPR & Compliance Checker voor Logistiek & Haven**  
> Een interactief auditinstrument met 24 checkpunten gebaseerd op AVG, CIS Controls v8, ISO 27001:2022, ISPS Code en het Douanewetboek van de Unie.

[![Demo](https://img.shields.io/badge/Demo-Live%20bekijken-blue?style=for-the-badge)](#gebruik)
[![Taal](https://img.shields.io/badge/Taal-Vanilla%20JS%20%2F%20HTML%20%2F%20CSS-yellow?style=for-the-badge)]()
[![Licentie](https://img.shields.io/badge/Licentie-MIT-green?style=for-the-badge)]()
[![Versie](https://img.shields.io/badge/Versie-1.0.0-blue?style=for-the-badge)]()

---

## Overzicht

ComplianceGuard Pro is een **browser-gebaseerde compliance checker** speciaal ontwikkeld voor logistieke bedrijven, havenbedrijven en supply chain organisaties. Het tool helpt IT- en compliance teams om snel de stand van zaken in kaart te brengen op het gebied van privacywetgeving (GDPR/AVG), applicatiebeveiliging, informatiebeveiliging en sectorspecifieke havenregelgeving.

### Waarom dit tool?

Logistieke bedrijven verwerken enorme hoeveelheden persoonsgegevens (chauffeurs, klanten, douanedata, tracking) én opereren in een hoog-risico omgeving met kritische IT-systemen zoals Terminal Operating Systems (TOS), EDI-koppelingen en douanesoftware. Standaard compliance checklists houden geen rekening met deze sector-specifieke context.

---

## Functies

| Functie | Beschrijving |
|---------|-------------|
| **24 Checkpunten** | Verdeeld over 4 categorieën, elk met juridische referentie |
| **Live Scoring** | Compliance score en progress ring updaten in realtime |
| **Risico-indicatoren** | Hoog / Middel / Laag per checkpunt |
| **Status per item** | Niet getoetst / Compliant / Aandacht / Niet OK |
| **Notities** | Vrije notities per checkpunt voor bevindingen & actiepunten |
| **Categorie filters** | Filter op categorie, status, risico of zoekterm |
| **HTML Export** | Volledig opgemaakte rapport met scores, bevindingen en notities |
| **Local Storage** | Voortgang automatisch opgeslagen in de browser |
| **Dark Enterprise UI** | Professioneel design, responsive, geen dependencies |

---

## Categorieën & Checkpunten

### 🛡️ GDPR / AVG (6 items)
| # | Checkpunt | Referentie | Risico |
|---|-----------|-----------|--------|
| 1 | Verwerkingsregister | Art. 30 AVG | Hoog |
| 2 | Rechtsgrond voor verwerking | Art. 6 AVG | Hoog |
| 3 | Privacyverklaring | Art. 13–14 AVG | Hoog |
| 4 | DPIA hoog-risico verwerkingen | Art. 35 AVG | Hoog |
| 5 | Bewaartermijnen & verwijdering | Art. 5 lid 1e AVG | Middel |
| 6 | Functionaris Gegevensbescherming | Art. 37–39 AVG | Hoog |

### 💻 Applicatiebeheer (6 items)
| # | Checkpunt | Referentie | Risico |
|---|-----------|-----------|--------|
| 7 | Patchmanagement & updates | CIS Control 7 | Hoog |
| 8 | Toegangsbeheer & IAM (least privilege) | ISO 27001 A.9 | Hoog |
| 9 | Software Asset Management | ISO 27001 A.8.1 | Middel |
| 10 | Change management procedure | ISO 27001 A.12.1.2 | Middel |
| 11 | Business Continuity & Disaster Recovery | ISO 27001 A.17 | Hoog |
| 12 | Incident Response Procedure | ISO 27001 A.16 / Art. 33 AVG | Hoog |

### 🔒 Beveiliging (6 items)
| # | Checkpunt | Referentie | Risico |
|---|-----------|-----------|--------|
| 13 | Multi-factor Authenticatie (MFA) | CIS Control 6.3 / NIS2 | Hoog |
| 14 | Encryptie data at rest | ISO 27001 A.10.1 | Hoog |
| 15 | Encryptie data in transit | CIS Control 14.4 | Hoog |
| 16 | Vulnerability scanning & pentest | CIS Control 7.1 | Middel |
| 17 | Firewall & netwerksegmentatie | CIS Control 12 | Hoog |
| 18 | Security awareness training | CIS Control 17 | Middel |

### 🚢 Logistiek / Haven (6 items)
| # | Checkpunt | Referentie | Risico |
|---|-----------|-----------|--------|
| 19 | AEO-certificering & documentatie | DWU Art. 38–41 | Hoog |
| 20 | EDI-verbindingen beveiligd | ISO 27001 A.13.1 | Hoog |
| 21 | TOS toegangsbeheer & logging | ISO 27001 A.9.2 | Hoog |
| 22 | GPS/tracking data GDPR-conform | Art. 6 AVG / WP29 | Middel |
| 23 | Verwerkersovereenkomsten carriers | Art. 28 AVG | Hoog |
| 24 | ISPS Code & havenbeveiliging | SOLAS XI-2 / ISPS 2004 | Middel |

---

## Gebruik

### Stap 1 — Open de applicatie
```bash
# Clone de repo
git clone https://github.com/jouw-gebruikersnaam/gdpr-compliance-checker.git
cd gdpr-compliance-checker

# Open direct in browser (geen server nodig)
open index.html
```

### Stap 2 — Voer de audit uit
1. Selecteer per checkpunt de status: **Compliant**, **Aandacht vereist** of **Niet compliant**
2. Voeg optioneel notities toe met bevindingen of actiepunten
3. Filter op categorie, risico of status om te focussen

### Stap 3 — Exporteer het rapport
Klik op **⬇ Export HTML** om een volledig opgemaakte rapport te downloaden, inclusief:
- Compliance score en verdeling per categorie
- Alle bevindingen en notities
- Gebaseerd op officiële wetsreferenties

---

## Technische Specificaties

```
├── index.html          # Volledige applicatie (single-file)
├── README.md           # Documentatie
└── .gitignore
```

- **Geen dependencies** — pure HTML5, CSS3, Vanilla JavaScript
- **Geen build stap** — direct openen in browser
- **Local Storage** — voortgang bewaard tussen sessies
- **Responsive** — werkt op desktop, tablet en mobiel
- **Print-vriendelijk** — header/footer verborgen bij printen

---

## Wettelijke Referenties

| Kader | Volledige naam |
|-------|---------------|
| **AVG / GDPR** | Verordening (EU) 2016/679 — Algemene Verordening Gegevensbescherming |
| **CIS Controls v8** | Center for Internet Security — Critical Security Controls |
| **ISO 27001:2022** | Information Security Management Systems |
| **NIS2** | Richtlijn (EU) 2022/2555 — Beveiliging netwerk- en informatiesystemen |
| **DWU** | Verordening (EU) 2016/952 — Douanewetboek van de Unie |
| **ISPS Code** | International Ship and Port Facility Security Code (SOLAS XI-2) |

---

## Gebruik als Portfolio

Dit tool toont kennis van:
- **GDPR/AVG compliance** — wetsartikelen, FG, DPIA, verwerkersovereenkomsten
- **Enterprise IT beheer** — IAM, patchmanagement, change management, DR/BCP
- **Informatiebeveiliging** — CIS Controls, ISO 27001, MFA, encryptie
- **Logistieke sector** — AEO, EDI, TOS, Portbase, ISPS, douanewetgeving
- **Frontend development** — Vanilla JS, CSS animaties, LocalStorage, Blob export

---

## Disclaimer

Dit tool is bedoeld als **indicatief hulpmiddel** voor interne audits. Voor definitieve compliance-beoordelingen dient een juridisch of privacy-adviseur te worden geraadpleegd. De tool vervangt geen formele DPIA of juridisch advies.

---

## Licentie

MIT License — vrij te gebruiken, aanpassen en distribueren.

---

*Ontwikkeld door [Philippe Godfroy](mailto:philgodf@gmail.com) · Versie 1.0.0*
