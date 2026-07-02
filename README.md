# Blue Prism Objekter

En samling af Blue Prism-objekter (BPA Objects) til automatisering af danske kommunale og velfærdssystemer, gjort offentligt tilgængelig af Odense RPA.

## Indhold

Objekterne er organiseret i fem mapper:

### Basis objekter

Generelle hjælpeobjekter til brug på tværs af automatiseringer:

- **Medcom** – håndtering af Medcom-beskeder
- **ODK JSON** – JSON-behandling
- **ODK LINQ** – LINQ-lignende forespørgsler
- **ODK Generelle hjælpefunktioner** – diverse hjælpemetoder
- **XML** – XML-håndtering

### Momentum

Objekter til borgersaksstyringssystemet Momentum:

- **Borger** – borgersøgning og -opslag
- **Core** – kerneoperationer
- **Journal** – journalnoter og dokumentation
- **Virksomheder** – virksomhedsdata

### Nexus

Objekter til det sociale velfærdssystem Nexus:

- **Borgere og forløb** – borgere og sagsforløb
- **Brugere og organisationer** – brugere og organisationsstruktur
- **Core** – kerneoperationer
- **Indsatser og tilstande** – sociale indsatser og tilstandsstyring
- **Kalender** – kalenderopslag og -opdateringer
- **Medcom** – Medcom-beskeder via Nexus
- **Opgaver og lister** – opgavestyring og lister
- **Relationer** – relationer mellem borgere og aktører
- **Skemaer** – formularudfyldning og -håndtering

### KP

- **KP** – integration med KP-systemet

### Skat

- **Skat** – integration med Skatteforvaltningens systemer

## Brug

Importer BPA-objekterne (.xml) i Blue Prism via **File → Import** eller via Blue Prism Management Utility.

Objekterne kan herefter bruges som afhængigheder i egne processer.

## GDPR og sikkerhed

Objekterne interagerer med systemer, der indeholder personhenførbare oplysninger, herunder CPR-numre, sagsinformation, sociale ydelsesdata, kalenderoplysninger og organisationsdata for danske kommuner. Adgang til de underliggende systemer bør begrænses til autoriserede brugere og tjenester i overensstemmelse med gældende databeskyttelsesregler.

## Licens

MIT
