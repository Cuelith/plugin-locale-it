# plugin-locale-it

Modulo lingua italiana di Cuelith. Fonte di verità: il documento di progetto nel repo `cuelith-docs`.

- Solo dati: nessun codice, `runtime: none`. Non aggiungere script o processi.
- Ogni nuova chiave `core.*` o `protocol.*` introdotta in `cuelith-core` o `cuelith-sdk` va aggiunta qui nello stesso giro di lavoro; il test delle lingue del nucleo lo verifica.
- Testi per l'operatore: frasi semplici, attive, che dicono cosa succede o cosa fare. Niente gergo tecnico se esiste una parola comune.
- Lavoro su `dev`; `main` riceve solo release taggate (SemVer).
