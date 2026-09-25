L’agente definito nel file etl-knowledge.agent.md ora:
- Legge tutte le trascrizioni nella cartella trascrizioni (da creare in locale).
- Integra le informazioni delle diverse call.
- Organizza i contenuti per argomento:
    - panoramica del progetto;
    - processo dati ed ETL;
    - dominio ESG e finanziario;
    - BI, reportistica e frontend;
    - operatività, ambienti e accessi;
    - glossario e punti da verificare.
- Genera o aggiorna questi Markdown nella cartella documentazione (da creare in locale).
- Aggiorna index.md come guida alla lettura.
- Segnala ogni informazione come:
- Esplicita;
- Inferita;
- Da verificare.
Mantiene i riferimenti alle trascrizioni e ai timestamp quando disponibili.
Non inventa informazioni mancanti e segnala ambiguità o conflitti.
Il file etl-knowledge.agent.md è quindi la configurazione dell’agente: contiene il suo ruolo, le regole, la struttura dei documenti e il comportamento da seguire.
 
Non si avvia automaticamente quando aggiungi una trascrizione. Devi selezionarlo in Copilot Chat e chiedergli, ad esempio:
"Analizza tutte le trascrizioni aggiornate e sincronizza la documentazione tematica nella cartella documentazione."
