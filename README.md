# documentazioneTecnica

Repository con la documentazione e gli appunti del corso: Java, Database, Soft Skills e progetto di gruppo Scrum.

---

## Struttura

```
├── JAVA-DOCUMENTAZIONE TEORICA/      Appunti completi sul corso Java e Spring Boot
│   ├── 01_Fondamenti_Java/           Classi, variabili, tipi primitivi, costruttori, OOP
│   ├── 02_Collezioni_e_Strutture_Dati/  Array, ArrayList, Set, Map, filter, reduce
│   ├── 03_Eccezioni_e_Testing/      Try-catch, JUnit, gestione errori
│   ├── 04_Design_Patterns_e_Architettura/  MVC, Spring Boot, architettura applicazione
│   ├── 05_Spring_Boot/               Controller, RestController, JPA, Spring Data
│   ├── 06_Web_e_Frontend/            HTML, CSS, JavaScript, Client-Server
│   ├── 07_Database_e_SQL/            DDL, DML, SQLite, JOIN, relazioni
│   └── 08_Materiale_Riferimento/    Libri, manuali, guide
├── SOFTSKILL/                        Appunti lezioni, materiale teorico e progetto di gruppo
│   └── 03_Progetto_Gruppo/           Progetto "Sviluppatori Anonimi" con mockup e artefatti Scrum
├── brainstack-programming-notions/   Submodule: appunti di programmazione C/C++
└── LibroAngularFerdinando/          (ignorato da git)
```

---

## Contenuto

### JAVA-DOCUMENTAZIONE TEORICA
Documentazione del corso Java organizzata per tema:

- **01_Fondamenti_Java** — classi, variabili, tipi primitivi, costruttori, scope, flusso esecuzione, astrazione, interfacce, lambda, generics
- **02_Collezioni_e_Strutture_Dati** — array, ArrayList, Set, Map, filter, reduce
- **03_Eccezioni_e_Testing** — try-catch-finally, JUnit, test automatizzati
- **04_Design_Patterns_e_Architettura** — MVC, Spring Boot, caching, factory method
- **05_Spring_Boot** — Controller vs RestController, Spring Data JPA, annotazioni
- **06_Web_e_Frontend** — HTML, CSS, JavaScript, architettura Client-Server, progetti
- **07_Database_e_SQL** — DDL, DML, SQLite, GROUP BY, JOIN, relazioni, ereditarietà
- **08_Materiale_Riferimento** — libri Java, manuali, guide Eclipse

### SOFTSKILL
Appunti delle lezioni e materiale teorico su competenze trasversali, adattabilità, lavoro di gruppo e certificazioni Scrum.

Il progetto di gruppo **"Gli Sviluppatori Anonimi"** contiene:
- analisi e documentazione del progetto
- mockup desktop e mobile
- artefatti Scrum: user story, sprint backlog, sprint planning, roadmap

### brainstack-programming-notions
Submodule git con appunti di programmazione C e C++.

---

## Setup del submodule

Al primo clone della repo, il contenuto di `brainstack-programming-notions/` non viene scaricato automaticamente. Per inizializzarlo:

```bash
git submodule update --init
```
