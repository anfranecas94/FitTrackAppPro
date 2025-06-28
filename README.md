
# FitTrackPro (Standalone Version)

## Descrizione
FitTrackPro è un'app Java standalone che genera piani di allenamento e dieta personalizzati, utilizzando concetti OOP, design pattern (Factory, Composite, Strategy, Iterator), multithreading e principi di sicurezza.

## Come eseguire

1. Apri il terminale nella cartella `fittrackpro`
2. Compila il progetto:
```
javac fittrackpro/*.java fittrackpro/model/*.java fittrackpro/plan/*.java fittrackpro/report/*.java fittrackpro/security/*.java fittrackpro/service/*.java
```
3. Esegui l'app:
```
java fittrackpro.FitTrackPro
```

## Funzionalità
- Input sicuro e validato
- Generazione parallela di piano dieta e workout
- Report giornaliero e mensile
- Logging sicuro e gestione eccezioni

## Requisiti
- JDK 11 o superiore
- Nessuna dipendenza esterna (no Maven)

