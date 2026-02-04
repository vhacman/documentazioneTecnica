# documentazioneTecnica

Repository con la documentazione e gli appunti del corso: Java, Database, Soft Skills e progetto di gruppo Scrum.

---

## Struttura

```
├── 01_Database/                      Appunti e materiale teorico sui database
├── 02_Soft_Skills/                   Materiale soft skills e certificazioni Scrum
├── JAVA-DOCUMENTAZIONE TEORICA/      Appunti completi sul corso Java e Spring Boot
├── SOFTSKILL/                        Appunti lezioni, materiale teorico e progetto di gruppo
│   ├── 01_Appunti_Lezioni/
│   ├── 02_Materiale_Teorico/
│   └── 03_Progetto_Gruppo/           Progetto "Sviluppatori Anonimi" con mockup e artefatti Scrum
└── brainstack-programming-notions/   Submodule: appunti di programmazione C/C++
```

---

## Contenuto

### 01_Database
Fondamenti di database relazionali: introduzione alle tabelle, DDL, DML e configurazione POM.

### 02_Soft_Skills
Materiale teorico su competenze trasversali, adattabilità, lavoro di squadra e guide Scrum Fundamentals.

### JAVA-DOCUMENTAZIONE TEORICA
Documentazione del corso Java, organizzata per tema:

- **Fondamenti** — classi, variabili, tipi primitivi, costruttori, scope e flusso di esecuzione
- **OOP avanzata** — astrazione, interfacce, lambda, generics, type safety
- **Strutture dati** — array, ArrayList, Set, Map, filter, reduce
- **Controllo di flusso** — if, switch, cicli, operatore ternario, short-circuit
- **Eccezioni** — try-catch-finally, gestione degli errori
- **Architettura** — Client-Server, MVC, Spring Boot, Controller vs RestController
- **Database** — DDL/DML, Spring Data JPA, SQL GROUP BY, SQLite
- **Frontend** — HTML, CSS, JavaScript
- **Altro** — caching, JUnit, factory method, HashMap

### SOFTSKILL
Appunti delle lezioni e materiale teorico sul corso Soft Skills, inclusi modulo Scrum e guide SBOK.

Il progetto di gruppo **"Gli Sviluppatori Anonimi"** (in `03_Progetto_Gruppo/`) contiene:
- analisi e documentazione del progetto
- mockup desktop e mobile (homepage, profilo, pannello amministrativo)
- artefatti Scrum: user story, sprint backlog, sprint planning, roadmap e scrum board

### brainstack-programming-notions
Submodule git con appunti di programmazione C e C++: OOP, puntatori, referenze, allocazione dinamica, floating point e IEEE 754.

---

## Setup del submodule

Al primo clone della repo, il contenuto di `brainstack-programming-notions/` non viene scaricato automaticamente. Per inizializzarlo:

```bash
git submodule update --init
```
