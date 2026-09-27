# Buchhaltungen

> Modern accounting software built around automation, document intelligence, and reliable bookkeeping workflows.

[English](#english) · [Deutsch](#deutsch)

---

## English

### About

**Buchhaltungen** is building modern accounting software designed to reduce repetitive bookkeeping work and make financial document processing easier, faster, and more reliable.

Our goal is not to hide accounting behind a black box.

Instead, we combine automation, document processing, deterministic accounting logic, and human review into one practical system.

The project is currently under active development.

### What we are building

The platform is designed around a complete accounting workflow:

- Receipt and invoice capture
- Mobile document scanning
- OCR and document text extraction
- Supplier recognition
- Invoice number and date recognition
- Net, VAT and gross amount extraction
- Multiple VAT rate support
- Automatic validation
- Accounting suggestions
- Account and tax suggestions
- Human review and corrections
- Supplier management
- Booking and transaction workflows
- Audit trails
- Multi-company support
- Role and permission management
- Bank integrations
- POS / cash register integrations
- Automated document ingestion

Future components may include dedicated scanner hardware and additional integrations for accounting workflows.

### Architecture

The project currently includes:

**Backend**

- FastAPI
- PostgreSQL
- Alembic
- REST API
- Authentication and refresh tokens
- Multi-tenant isolation
- Accounting validation
- OCR and document processing
- Audit logging

**Mobile**

- Flutter
- Android
- iOS
- Receipt and invoice capture
- Review and correction workflows

**Desktop / Web Application**

- Next.js
- React
- TypeScript
- Desktop-first accounting workspace
- Document review
- Suppliers
- Accounts
- Bookings
- Transactions
- Team and company management

### Core principles

We are building the platform around a few important principles:

**Accounting logic must be deterministic.**  
AI may suggest values, mappings, accounts, or corrections, but accounting rules and validations should remain predictable and testable.

**Humans stay in control.**  
Low-confidence results should be reviewed instead of being silently accepted.

**Security and tenant isolation matter.**  
Company data must stay separated and access must be controlled through explicit roles and permissions.

**Automation should reduce work, not create uncertainty.**  
Every automated step should be understandable, reviewable, and auditable.

**Financial values require precision.**  
Money is handled using precise decimal representations instead of floating-point arithmetic.

### Project status

The project is currently in active development.

Current development includes:

- Authentication
- Company and membership management
- Document uploads
- OCR processing
- Invoice extraction
- Supplier workflows
- Invoice review
- Accounting suggestions
- Posting workflows
- Audit events
- Android application
- Desktop accounting application
- Staging infrastructure
- Automated CI checks

Some integrations and production features are still under development.

### Repositories

Our repositories cover different parts of the platform, including:

- Accounting backend
- Mobile application
- Desktop application
- Infrastructure and deployment
- Public website
- Documentation

Some repositories may remain private while the platform is under development.

### Technology

Technologies currently used across the project include:

`Python` · `FastAPI` · `PostgreSQL` · `Flutter` · `Dart` · `Next.js` · `React` · `TypeScript` · `Docker` · `Nginx` · `GitHub Actions`

### Development

The project uses automated checks for areas such as:

- Formatting
- Linting
- Type checking
- Backend tests
- Mobile tests
- Web tests
- Production builds
- Deployment validation
- Security-sensitive accounting workflows

### Contact

Website: **https://aufgekaut.de**

Email: **kontakt@aufgekaut.de**

> `aufgekaut.de` is currently used as the project website domain and may change as the project evolves.

### License

Unless explicitly stated otherwise in an individual repository, the source code and project materials are **not provided as open-source software**.

All rights reserved.

---

<details id="deutsch">
<summary><strong>🇩🇪 Deutsch anzeigen</strong></summary>

<br>

## Deutsch

### Über uns

**Buchhaltungen** entwickelt moderne Buchhaltungssoftware, die wiederkehrende Arbeit reduziert und die Verarbeitung von Belegen und Rechnungen einfacher, schneller und zuverlässiger machen soll.

Unser Ziel ist nicht, Buchhaltung in einer undurchsichtigen KI-Blackbox zu verstecken.

Stattdessen kombinieren wir Automatisierung, Dokumentenverarbeitung, deterministische Buchhaltungslogik und menschliche Prüfung in einem gemeinsamen System.

Das Projekt befindet sich aktuell in aktiver Entwicklung.

### Was wir entwickeln

Die Plattform soll einen vollständigen Buchhaltungsworkflow abbilden:

- Beleg- und Rechnungserfassung
- Mobiles Scannen von Dokumenten
- OCR und Texterkennung
- Lieferantenerkennung
- Erkennung von Rechnungsnummern und Datumsangaben
- Erkennung von Netto-, Umsatzsteuer- und Bruttobeträgen
- Unterstützung mehrerer Umsatzsteuersätze
- Automatische Plausibilitätsprüfung
- Buchungsvorschläge
- Konto- und Steuervorschläge
- Manuelle Prüfung und Korrektur
- Lieferantenverwaltung
- Buchungs- und Transaktionsworkflows
- Audit-Trail
- Unterstützung mehrerer Unternehmen
- Rollen- und Rechteverwaltung
- Bankintegrationen
- Kassen- und POS-Integrationen
- Automatisierte Dokumenteneingänge

Später können außerdem eigene Scanner-Hardware und weitere Integrationen für Buchhaltungsprozesse hinzukommen.

### Architektur

Das Projekt besteht aktuell unter anderem aus:

**Backend**

- FastAPI
- PostgreSQL
- Alembic
- REST API
- Authentifizierung und Refresh Tokens
- Multi-Tenant-Isolation
- Buchhaltungsvalidierung
- OCR und Dokumentenverarbeitung
- Audit-Logging

**Mobile**

- Flutter
- Android
- iOS
- Beleg- und Rechnungserfassung
- Prüfung und Korrektur erkannter Daten

**Desktop / Web-Anwendung**

- Next.js
- React
- TypeScript
- Desktop-orientierter Buchhaltungsarbeitsplatz
- Dokumentenprüfung
- Lieferanten
- Konten
- Buchungen
- Transaktionen
- Team- und Unternehmensverwaltung

### Grundprinzipien

Bei der Entwicklung orientieren wir uns an einigen wichtigen Prinzipien:

**Buchhaltungslogik muss deterministisch bleiben.**  
KI darf Werte, Zuordnungen, Konten oder Korrekturen vorschlagen. Buchhaltungsregeln und Validierungen sollen jedoch vorhersehbar und testbar bleiben.

**Der Mensch behält die Kontrolle.**  
Ergebnisse mit niedriger Sicherheit sollen geprüft werden, statt unbemerkt übernommen zu werden.

**Sicherheit und Mandantentrennung sind zentral.**  
Unternehmensdaten müssen sauber getrennt bleiben. Zugriffe werden über Rollen und Berechtigungen kontrolliert.

**Automatisierung soll Arbeit reduzieren und keine neue Unsicherheit schaffen.**  
Automatisierte Schritte sollen nachvollziehbar, prüfbar und auditierbar bleiben.

**Finanzwerte benötigen Genauigkeit.**  
Geldbeträge werden mit präzisen Dezimalwerten verarbeitet und nicht mit ungenauen Fließkommazahlen.

### Projektstatus

Das Projekt befindet sich derzeit in aktiver Entwicklung.

Bereits entwickelt beziehungsweise aktuell in Arbeit sind unter anderem:

- Authentifizierung
- Unternehmens- und Mitgliederverwaltung
- Dokumenten-Uploads
- OCR-Verarbeitung
- Rechnungsextraktion
- Lieferantenworkflows
- Rechnungsprüfung
- Buchungsvorschläge
- Buchungsworkflows
- Audit Events
- Android-App
- Desktop-Buchhaltungsanwendung
- Staging-Infrastruktur
- Automatisierte CI-Prüfungen

Einige Integrationen und Funktionen für den späteren Produktivbetrieb befinden sich weiterhin in Entwicklung.

### Repositories

Unsere Repositories decken unterschiedliche Bereiche der Plattform ab:

- Accounting Backend
- Mobile App
- Desktop-Anwendung
- Infrastruktur und Deployment
- Öffentliche Website
- Dokumentation

Einige Repositories können während der Entwicklung privat bleiben.

### Technologien

Aktuell verwenden wir projektübergreifend unter anderem:

`Python` · `FastAPI` · `PostgreSQL` · `Flutter` · `Dart` · `Next.js` · `React` · `TypeScript` · `Docker` · `Nginx` · `GitHub Actions`

### Entwicklung

Automatisierte Prüfungen decken unter anderem folgende Bereiche ab:

- Formatierung
- Linting
- Typechecking
- Backend-Tests
- Mobile-Tests
- Web-Tests
- Production Builds
- Deployment-Prüfungen
- sicherheitsrelevante Buchhaltungsworkflows

### Kontakt

Website: **https://aufgekaut.de**

E-Mail: **kontakt@aufgekaut.de**

> `aufgekaut.de` wird aktuell als Projekt-Website verwendet und kann sich im weiteren Verlauf des Projekts ändern.

### Lizenz

Sofern in einem einzelnen Repository nicht ausdrücklich anders angegeben, werden Quellcode und Projektmaterialien **nicht als Open-Source-Software bereitgestellt**.

Alle Rechte vorbehalten.

</details>

---

<p align="center">
  Built with a focus on reliable accounting workflows, automation and human control.
</p>
