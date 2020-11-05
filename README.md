# Open-Source-System-Issues-Quality-Analysis

Lo scopo della questa tesi è stato di analizzare i bug report di uno dei sistemi ERP Open Source più diffusi, Odoo , applicando il modello di qualità Zimmermann. Il primo passo effettuato è stato quello relativo al download delle issues OPEN e CLOSED del codice sorgente di Odoo, riportate in un file, mediante l'uso di IssuesDownaload, un codice Java scaricato da GitHub e modificato in base alle nostre esigenze. All'interno del file creato, sono state trovate 17 categorie principali, con le quali raggruppare la maggior parte delle issues. Dopo aver fatto ciò, il secondo passo e stato quello dell'analisi dei dati con diagrammi, analisi statistica e calcolo di classificazione e predizione, tramite i quali siamo giunti a più conclusioni: per prima cosa si può dire che la maggior parte delle issues, sia OPEN che CLOSED, sono incomplete o mancano di parametri fondamentali per la risoluzione di un bug; inoltre si è notato che all'aumentare della reputation di un utente aumentano anche i commenti sul bug report. Per quanto riguarda l'analisi statistica si è osservato come i parametri sono dipendenti tra loro e, tramite gli interval plot, si nota come alcune categorie incidono di più su specifici parametri. Infine, l'ultima analisi effettuata è stata quella sugli algoritmi di apprendimento automatico, con lo scopo di trovare quale tra i tanti algoritmi abbia accuratezza migliore. Ciò è stato effettuato sul software Weka e l'algoritmo con migliore accuratezza trovato (68.8%) è l'albero RandomForest. Per sviluppi futuri, l'applicazione può essere ulteriormente raffinata per includere più parametri e più categorie su cui svolgere l'analisi, inoltre è possibile migliorare il modello di qualita aumentando il numero di issues prese in considerazione e selezionare pari numero issues di tutti i valori della scala Likert, al fine di trovare il miglior algoritmo di apprendimento automatico.
