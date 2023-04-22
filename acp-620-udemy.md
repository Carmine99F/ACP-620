1)Quali informazioni sul progetto possono essere modificate dall'amministratore del progetto di un progetto gestito      dal team dalla pagina dei dettagli del progetto? (Scegli quattro)

    Nome Progetto
    Chiave
    Categoria
    Responsabile del progetto

2)Funzionalità esclusive dei progetti gestiti dal team

    Creazione di più issue contemporaneamente
    L'amministratore di progetto può creare nuovi issue type (Possibile creare fino a 30 tipi di issue)

3)Sarah è l'amministratore del progetto gestito dal team "BLOCK" in cui l'accesso al progetto è impostato su"Limitato".
    Sarah ha aggiunto Maria al progetto e le ha assegnato il ruolo di "Membro". Sarah ha quindi confermato di poter creare problemi, aggiungere un commento, aggiungere allegati, impostare date di scadenza, modificare i reporter e assegnare e modificare problemi. Ma non può classificare i problemi.
    Cosa dovrebbe fare Sarah per risolvere questo problema?

    Bisogna disporre di una licenza del prodotto software jira

4)Quale tipologia di progetto soddisfa i seguenti requisiti?
        Consenti un arretrato
        Supporta la configurazione del filtro secondario
        Consenti agli amministratori di progetto di assegnare ruoli.

        Risposta : progetto gestito dall'azienda con modello Kanban
        i filitri secondari non sono consentiti nei progetti gestiti dal team, solo le bacheche kanban gestite dall'azienda lo consentono, nemmeno sulle bacheche di progetti scrum gestiti dall'azienda sono consentiti
        Per quanto riguarda l'assegnazione di ruoli da parte degli amminitratori di progetto cioè è permesso sia nei progetti gestiti dal team che dall'azienda


5)Amelia ha appena creato un progetto scrum gestito dall'azienda denominato "MIG".
    Amelia si chiede quali schemi siano stati creati automaticamente da Jira per il suo progetto "MIG".
    Identificare quali schemi sono unici (cioè non condivisi) per il progetto appena creato "MIG"? (Scegli tre)

    Schema del Workflow
    Screen Scheme
    Issue type Schema


6)Steve vuole creare un progetto Jira e ha i seguenti requisiti:
    Capacità di stabilire le priorità del lavoro su base giornaliera utilizzando una scheda Agile
    Capacità di lavorare su problemi in iterazioni ma con durata variabile
    Consenti agli amministratori di progetto di cancellare la colonna all'estrema destra della scheda Agile quando necessario.
    Il progetto dovrebbe soddisfare tutti questi requisiti subito dopo la creazione senza abilitare funzionalità aggiuntive.
    Quale tipo di progetto e modello dovrebbe creare Steve?

    Progetto gestito dal team con modello Kanban
    Il primo requisito può essere soddisfatto sia da progetti gestiti dall'azienda che da un team con una scheda Kanban
    Il secondo requisito ci indica che il modello scrum non è adatto ed è necessario usare un modello kanban
    Per il terzo requisito è consentito eliminare la colonna a alla destra della scheda agli amministratori di progetto solo nel caso in cui si tratti un progetto gestito dal team

7)Quali dei seguenti non sono ruoli predefiniti nei progetti gestiti dal team?

    Developer
    Project Lead
    Amministratori
    Team member

8)Quali informazioni sul progetto possono essere modificate dall'amministratore del progetto in un progetto gestito dall'azienda?

    Decrizione
    Nome Progetto
    Responsabile del progetto
    Invece per poter modificare la chiave e la categoria del progetto devi essere amministratore jira

9)Identifica le funzionalità esclusive dei progetti gestiti dall'azienda . (scegline due)
    
    Possibilità di configurare filtri secondari
    È possibile creare swimlane personalizzate e si basano su query JQL

10)Un team della tua azienda ti ha chiesto di creare un progetto che soddisfi i seguenti requisiti:
    Capacità di stabilire le priorità del lavoro su base giornaliera utilizzando un backlog e una scheda Agile
    Capacità di lavorare sui problemi in iterazioni settimanali
    Possibilità di aggiornare i nomi degli stati del flusso di lavoro da parte dell'amministratore del progetto
    Il progetto dovrebbe soddisfare tutti questi requisiti subito dopo la creazione senza la necessità di abilitare funzionalità aggiuntive
    Quale tipo di progetto e modello dovresti creare?

    Progetto gestito dal team con modello Scrum
    Esaminiamo i requisiti:
    -Capacità di stabilire le priorità del lavoro su base giornaliera utilizzando un backlog e una scheda Agile
        Queesta funzionalità è supportata sia dai progetti gestiti dall'azienda che dai progetti gestiti dal team
    -Capacità di lavorare sui problemi in iterazioni settimanale
        Questo vuol dire utilizzare gli sprint , che è possibile solo con modello scrum, sia gestito dall'azienda che dal team
    -Possibilità di aggiornare i nomi degli stati del workflow da parte dell'amministratore del progetto
        Solo nei progetti gestti dal team è consentito modificare gli stati del workflow

11)Hannah è una scrum master e dispone di tutte le autorizzazioni necessarie per visualizzare,
     creare, eliminare e modificare i problemnel progetto scrum gestito dall'azienda "MLOPS". È anche in grado di impostare date di scadenza, commentare, registrare il lavoro sui problemi e gestire gli sprint. Hannah è anche l'amministratore della scheda Scrum.
     Ma Hannah non è in grado di classificare le attività secondarie nel backlog. Perché?

     Non è possibile classificare gli issue type dei task secondari

12)Quali elementi possono essere aggiunti da un amministratore di progetto direttamente dalla barra laterale del progetto? (Scegline due)

    Shortcurts
    Code repository

13)James ha appena creato un progetto Kanban gestito dall'azienda "NFT" con una configurazione condivisa.
    Identifica quali elementi di configurazione sono condivisi. (Scegli quattro)

    Issue type
    Workflow scheme
    Issue Security scheme
    Notification Scheme
    I progetti gestiti dall'azienda che condividono la configurazione condividono:
    tipi di problema
    flussi di lavoro
    schermi
    campi
    autorizzazioni (inclusi schemi e livelli di sicurezza dei problemi)
    notifiche
    Se viene apportata una modifica a una delle configurazioni dei progetti, tale modifica influisce su tutti i progetti che condividono tale configurazione.
    Solo gli amministratori Jira possono creare progetti con una configurazione condivisa. La tabella seguente riassume questo aspetto per i progetti gestiti

14)  La tua organizzazione ha appena creato un sito Cloud e attivato due prodotti: Jira Software Cloud e Jira Work Management Cloud. Tutta    la  configurazione è al suo valore predefinito.
Identità quali affermazioni sono vere 

    Tutti gli utenti Jira software possono creare progetti gestiti dal team

15) "SAFE" è un progetto gestito dal team Kanban con i seguenti tipi di problema:
    Task (tipo di problema standard)
    Task secondari (tipo di problema relativo al task secondario)
    Quali affermazioni sono vere (scegline due):

    I task sono visibili nel backlog ma non i task secondari
    I task  possono essere classificati nel backlog ma non nei task secondari

16)Il tuo manager ti ha chiesto di creare un progetto Jira gestito dal team con modello Scrum che soddisfi i seguenti requisiti:
    Solo un elenco selezionato di utenti deve essere in grado di creare problemi
    Tutti gli utenti che accedono al tuo sito devono essere in grado di allegare documenti alle attività che possono visualizzare
    Tutte le storie devono essere visibili solo ai membri e agli amministratori
    Quale livello di accesso al progetto dovresti utilizzare:

    Solo membri e amministratori




























