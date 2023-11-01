## Daimon Canon

# Che cos'è questa repository?

Daimon Canon è la repository ufficiale che contiene l'intero canone narrativo del progetto Daimon.
Ciò che si trova all'interno della copia originale di questa repository (masterbaseguild/daimon_canon) è completamente canonico al momento di lettura, sebbene possa essere modificato in futuro.

# Come funziona?

Ogni autore che vuole contribuire alla repository può forkarla e proporre una pull request. Il team di Daimon revisionerà la pull request, si metterà in contatto con gli autori per discutere eventuali modifiche, necessarie a fare sì che le aggiunte rimangano coerenti con il resto del canone corrente, ed eventualmente approverà la pull request.
L'obiettivo è di costruire un universo narrativo semi-open-source, al quale chiunque può aggiungere contenuti, i quali poi sono accuratamente selezionati e revisionati da un team di supervisori e ufficialmente canonizzati qualora soddisfino i requisiti.

# Voglio mantenere segreti alcuni aspetti della mia fork per rivelarli in un secondo momento, come posso fare?

In tal caso, è raccomandato clonare la fork e rendere privata la repository clonata; dopodichè, consigliamo di lavorare direttamente sulla copia, e pullare verso la fork soltanto il materiale che può essere rivelato attualmente. Tuttavia, consigliamo come prima cosa di contattare il team di revisione e fornirgli accesso alla copia, onde evitare spiacevoli sorprese dell'ultimo momento (ad esempio, una rivelazione non è coerente con il resto del canone)

# Come verrà sincronizzata la repository del canone con il materiale live?

Ad ogni push ricevuto dalla repository originale, verrà attivata una GitHub Action che pusherà tutte le modifiche a un bucket di AWS S3, da cui poi i server di Daimon recupereranno gli articoli. I dettagli dell'implementazione non sono ancora stati delineati.

# Questo progetto sarà solo in italiano?

No, la scelta di cominciare dalla lingua italiana è puramente logistica; l'obiettivo indiscusso è quello di avere un vault ufficiale in inglese e vari mirror tradotti, dove le traduzioni saranno svolte in parte dalla comunità, e tutto il materiale restante verrà automaticamente tradotto tramite Google Translate. I dettagli dell'implementazione non sono ancora stati delineati.

# Altre idee in fase di sperimentazione

Un concetto interessante che potrebbe facilitare molto il lavoro è l'idea di narrazione inaffidabile, ovvero inquadrare parte del materiale come proveniente da fonti prevenute e talvolta persino discordanti tra di loro.
Altra idea, più tecnica, è quella di implementare in Daimon dei filtri anti-spoiler, che proteggano un utente ignaro da rivelazioni successive al punto in cui si trova in determinate narrative.
Tuttavia, per il momento si tratta ancora solamente di idee.
