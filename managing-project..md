                                                    Test Pratico 1


1)Hanna ha appena creato il suo primo progetto gestito dal team con modello Kanban. Hanna ora si chiede dove può creare un ruolo personalizzato per il suo progetto appena creato

    Access
    nei progetti gestiti dal team, qualsiasi autorizzazione o accesso che desideri concedere alle persone nel tuo progetto è controllato nella pagina Accesso . Qui puoi aggiungere persone al tuo progetto e assegnare loro un ruolo in modo che possano iniziare a collaborare al lavoro del tuo team.
    Questa pagina mostra:
    L'elenco delle persone che hanno accesso al tuo progetto
    Il ruolo che hanno nel tuo progetto
    La pagina Accesso ti consente anche di ottimizzare l'accesso che dai alle persone al lavoro del tuo team. Puoi creare ruoli utilizzando il pulsante "Gestisci ruoli" per personalizzare le autorizzazioni che concedi a determinate persone o gruppi.


2)Quale tra le seguenti affermazioni è vera?
-Gli amministratori di progetto possono assegnare ruoli di progetto alle autorizzazioni del progetto
-Gli amministratori di progetto possono creare autorizzazioni globali e assegnare loro ruoli di progetto
-Gli amministratori di progetto possono assegnare agli utenti autorizzazioni globali
-Gli amministratori di progetto possono creare nuovi ruoli di progetto e assegnarli alle autorizzazioni di progetto
-Gli amministratori di progetto possono assegnare gli utenti ai ruoli di progetto

    Gli amministratori di progetto possono assegnare gli utenti ai ruoli di progetto
    Infatti un amministratore di progetto è una persona che dispone dell'autorizzazione specifica per il progetto , ma non necessariamente dell'autorizzazione globale "Amministratore Jira". I ruoli di progetto vengo definiti dagli amministratori Jira

3)Vuoi migliorare il lead time dei ticket che passano attraverso la tua Kanban Board.
Pertanto, hai concordato con il tuo team di fissare le date di scadenza per ogni nuovo problema creato nel tuo progetto Kanban gestito dall'azienda.
Quali sono le autorizzazioni necessarie per poter impostare le date di scadenza? (Scegline due)

    "Edit Issue" project permission
    "Schedule Issues" project permission
    La prima autorizzazione è necessaria in quanto senza di essa non è possibile modificare una issue e i suoi attributi
    La seconda permette ad un utente di impostare o modificare il valore del campo data di scadenza


4)Il progetto Scrum gestito dall'azienda "PEGASUS" ha i seguenti ruoli e permessi di progetto:
Permission                Users/Groups/Project roles

Browse Projects           Project Role (Global Team) 

Edit issue                Project Role (Developers)

Create Attachments        Project Role (Compliance)

Delete All Attachments    Project Role (Analysts)

Delete Own Attachments    Project Role (Scrum team)

Delete issues             Project Role (Administrators)

Ashley deve essere in grado di aggiungere e rimuovere documenti PDF ai numeri del progetto “PEGASUS”.
Quanti ruoli di progetto, come minimo, dovrebbero essere assegnati ad Ashley?

    Ha bisogni di 3 ruoli : Craete Attachments, Browse Projects, Delete All attachments
    Potresti pensare che l'opzione "Delete Own Attachments" sia necessaria, MA non lo è poiché l'autorizzazione "Elimina tutti gli allegati" è potente. Permetterà ad Ashley di eliminare non solo i suoi allegati ma anche gli allegati di altri utenti.


5)17)Lo schema di autorizzazione del progetto Kanban gestito dall'azienda "SOL" è mostrato di seguito:
Permission          Users/Groups/Project roles

Administer Projects  Project Role (Administrators)

Browse Projects     Project Role (Administrators)
                    Project Role (Users)
                    Project Role (Managers)
                    Project Role (Auditors)

Assignable User     Project Role (Auditors)
                    Project Role (Administrators)

Edit issues         Project Role (Administrators)
                    Project Role (Managers)

Resolve issues      Project Role (Auditors)
                    Project Role (Managers)
                    Project Role (Users)

Close issues        Project Role (Administrators)
                    Project Role (Auditors)
                    Project Role (Managers)

Manage sprints      Project Role (Administrators)
                    Project Role (Auditors)

Schedule issues     Project Role (Auditors)
                    Project Role (Administrators)

Set Issue Security  Project Role (Administrators)
                    Project Role (Managers)

Diane deve essere in grado di:
Impostare il campo dei problemi "Correggi versione".
Cambia il livello di sicurezza.
Non le dovrebbero essere concesse più autorizzazioni del necessario.
Di quale ruolo o ruoli ha bisogno Diane per soddisfare i requisiti di cui sopra garantendo al contempo il principio del privilegio minimo?

    Manager, ha bisogno dei ruoli Set Issue Security e Resolve Issue


6)Dopo una recente modifica, alcuni utenti nel tuo sito Jira Cloud si lamentano perché non possono più creare progetti gestiti dal team. Tuttavia, sono in grado di visualizzare e lavorare sui problemi utilizzando Agile Boards.
Individua il motivo.

    Global permission
    Ricordiamo che esistono sei autorizzazioni globali: amministrare Jira, browse user  e group , condividere dashboard e filtri, gestire le sottoscrizioni ai filtri di gruppo, apportare modifiche in blocco e creare progetti gestiti dal team. I progetti gestiti dal team non influiscono sui progetti esistenti o sulle configurazioni condivise come flussi di lavoro, campi o autorizzazioni. Per impostazione predefinita, Jira Software offre agli utenti finali l' autorizzazione globale Crea progetti gestiti dal team . Tuttavia, poiché gli utenti non sono più in grado di creare progetti gestiti dal team, ciò significa che l'amministratore di Jira ha modificato questa impostazione.

7)Quale affermazione sui Componenti è falsa ?
    -I componenti fanno distinzione tra maiuscole e miniuscole
    -L'assegnatario predefinito di un componente può essere uno dei segeunti: Project Defaul, Component Lead, Project and lead Unassigned
    -I componenti possono essere usati nei report e nei gadget
    -Solo gli amministrtori di progetto possono creare componenti
    -I nomi dei componenti devono essere univoci in un progetto

    I componenti fanno distinzione tra maiuscole e miniuscole

8)Amanda non può visualizzare i report agili di uno Scrum Board gestito dall'azienda del progetto "DEV". 
Identificare due motivi.

    Ad Amnda manca l'autorizzazione del progetto browse project
    Il filtro salvato nella bacheca non è condiviso con Amanda

9)Il progetto Kanban gestito dall'azienda "AQUARIUS" ha i seguenti ruoli e autorizzazioni del progetto:ù

Permission           Users/Groups/Project roles
--
Browse Projects      Project Role (Analysts)
                     Project Role (Scrum team)
                     Application access (Jira Software)
-- 
Edit issue           Project Role (Compliance)
                     Project Role (Analysts)
--
Create issues        Project Role (Compliance)
                     Project Role (Analysts)
                     Project Role (Scrum team)
--
Create attachments  Project Role (Analysts)
                    Project Role (Scrum team)

Ashley deve essere in grado di creare solo issue.
Di quale ruolo o ruoli ha bisogno Ashley per soddisfare i requisiti di cui sopra?

    Compilance

10)Stai lavorando per un'agenzia spaziale utilizzando Jira per tenere traccia delle informazioni sul sistema solare.
Come sapete, il sistema solare è composto da 12 pianeti. Quando si crea un problema in Jira, gli utenti devono selezionare il singolo pianeta a cui desiderano aggiungere informazioni. Le informazioni sul pianeta devono essere utilizzate per rapporti accurati in un gadget Statistiche problema.
Quale campo soddisfa questi requisiti?

     " Campo personalizzato - Seleziona elenco (scelta singola) " è CORRETTA. L'informazione importante è che deve consentire la scelta di un solo pianeta e che deve essere utilizzata a scopo di segnalazione in un gadget di statistiche. Tutte le altre opzioni accettano più valori o non sono sufficientemente precise per la segnalazione in un gadget Statistiche problemi.

    
11)Hai appena creato un nuovo progetto gestito dall'azienda "CMW" con modello Kanban e assegnato a Ryan il ruolo di "Amministratore". Ryan deve rimanere l'unico amministratore di progetto del progetto "CMW" per garantire la coerenza della configurazione.
Ryan ha raccolto i seguenti requisiti dal suo team:
Requisito 1: creare componenti "Front", "Back", "Security"
Requisito 2: creare una nuova bacheca Kanban situata nel progetto appena creato ma con solo storie
Requisito 3: visualizzare la data di scadenza su tutte le schermate e i layout dei problemi utilizzati dal progetto
Requisito 4: aggiornare il layout del problema per nascondere i campi quando sono vuoti
Requisito 5: concedere l'autorizzazione del progetto "Elimina problemi" al responsabile del progetto "CMW"
Tutte le altre impostazioni di Jira sono nella loro configurazione predefinita e non sono mai state aggiornate.
Identifica quale configurazione non può essere eseguita da Ryan. (Scegline due)

    L'opzione che dice " Requisito 3 " è CORRETTA.   Per impostazione predefinita, il campo di sistema della data di scadenza non viene aggiunto alle schermate e solo l'amministratore Jira può modificare le schermate in Jira Cloud. Inoltre, poiché il layout della rivista si basa sulla schermata di modifica del tipo di rivista corrispondente, Ryan non sarà in grado di trovare il campo "data di scadenza" nel layout della rivista.
    L'opzione che dice " Requisito 5 " è CORRETTA.   La concessione dell'autorizzazione del progetto "Elimina problemi" al responsabile del progetto può essere eseguita in due modi. Assegnando al responsabile del progetto il ruolo di progetto "Amministratori" o modificando lo schema di autorizzazione e aggiungendo il "Responsabile del progetto". Poiché Ryan deve rimanere l'unico amministratore di progetto del progetto "CMW", il responsabile del progetto non deve essere aggiunto al ruolo di progetto "Amministratori". Inoltre, la modifica dello schema di autorizzazione richiede che Ryan sia un amministratore di Jira e non solo un amministratore di progetto. Pertanto, tale requisito non può essere soddisfatto.


12)Quali informazioni non vengono visualizzate nel pannello "Development"?

    Number of pipelines
    se il tuo amministratore ha connesso Jira Software a uno strumento di sviluppo compatibile, vedrai le informazioni sullo sviluppo insieme ai tuoi problemi in Jira. A seconda degli strumenti che hai connesso, Jira mostra i rami collegati, i commit, le richieste pull, le build, le distribuzioni e i flag delle funzionalità. Inoltre, devi fare riferimento alle chiavi dei problemi di Jira in commit, rami e richieste pull per visualizzare l'attività di sviluppo in Jira. Scopri di più sui problemi di riferimento nel tuo lavoro di sviluppo . Una volta che le informazioni sullo sviluppo sono state collegate a un problema, non possono essere rimosse.

13)Di seguito sono riportate le impostazioni di configurazione nel progetto gestito dall'azienda "FLO":
Project Lead : Zara
--
Default Assignee: Project Lead
-- 
Component          Component Lead          Default Assignee
------------------------------------------------------------
Front              Mia                     Project Lead
Authentication     James                   Component Lead
MicroService-XUT   Sophia                  Project Default
MicroService-MLK   Martinez                Unassigned   
MicroService-BSO   Ryan                    Component Lead

Hai creato una nuova issue, selezionato i seguenti componenti: “Front”, “Authentication”, “MicroService-XUT” e hai lasciato l'assegnatario come “Automatic”.
A chi verrà assegnato il numero appena creato?

    James
    Nel caso di problemi con più componenti, la struttura dell'assegnatario funziona dall'alto verso il basso, cioè dal meno specifico al più specifico. Il più specifico (Component Lead) ha la precedenza sugli altri. Si supponga, ad esempio, che un problema abbia più componenti e che per alcuni di questi componenti sia selezionata l'opzione Non assegnato. In tal caso, per alcuni è specificato un responsabile del progetto e per altri un responsabile del componente, quindi il responsabile del componente avrà sempre la precedenza come assegnatario. In sintesi, ecco la regola da ricordare
    L'assegnatario è selezionato > Component Lead (Component Id Ordine Crescente) > Project Default > Project Lead

14)Hai assunto Janice, un nuovo scrum master, per unirti al tuo team.
Deve essere in grado di creare e riordinare gli sprint nella bacheca Kanban gestita dall'azienda.
Identifica quale azione le consentirà di soddisfare questi requisiti.

    L'opzione che dice " Aggiungi Janice a un ruolo di progetto elencato nell'autorizzazione "Gestisci Sprint" " è CORRETTA. Janice ha bisogno dell'autorizzazione per il progetto "Gestisci sprint". Questa autorizzazione consente alle persone di creare, avviare e completare gli sprint nel progetto. Ciò include la regolazione della durata e dell'obiettivo dello sprint.
    Questa autorizzazione dipende dall'accesso del prodotto a Jira Software. Scopri di più su come consentire alle persone di accedere ai tuoi prodotti Atlassian . A seconda della complessità della query del filtro della tua bacheca, potresti aver bisogno di ulteriori considerazioni durante la configurazione dell'autorizzazione Gestisci sprint per gli utenti. Ad esempio, se una bacheca contiene sprint di più progetti (compresi i progetti di servizio), gli utenti devono gestire gli sprintautorizzazione in ogni progetto per completare gli sprint con successo. Per ulteriori informazioni sull'impatto dei filtri complessi e sui modi per semplificare la query del filtro, consulta Utilizzo dell'autorizzazione Gestisci sprint per i casi avanzati .
    Alcune azioni sprint (ad esempio, l'aggiunta di problemi agli sprint o la rimozione di problemi dagli sprint) richiedono le autorizzazioni Pianifica problemi e Modifica problemi per avere esito positivo.


15)In qualità di amministratore di progetto di un progetto gestito dall'azienda, quali azioni puoi eseguire sull'issue layout?

    Riordinare i campi
    Nascondere un campo se è vuoto

16)Vuoi allegare un'immagine a un problema. Identificare quale azione non può essere eseguita?

    Send the image using JiraAirDrop to the Jira issue”. Non esiste alcuna funzione JiraAirDrop

17)Nancy è un membro del progetto WEB3 gestito dall'azienda, che utilizza un workflow semplified generato da Jira e da allora non è mai stato aggiornato.
Nancy non può spostare i problemi nella colonna Done nella bacheca del progetto.
Di quale permesso ha bisogno Nancy?

    Transition Issue Permission

18)Michelle è l'amministratore del progetto “VENUS”.
Attualmente sono disponibili due versioni di questo progetto: la versione “1.0” e la versione “2.0”. Entrambe le versioni hanno problemi a farvi riferimento.
La versione “1.0” ha lo stato “ RELEASED ” e la versione “2.0” ha lo stato “ UNRELEASED ”.
Michelle ha erroneamente archiviato entrambe le versioni, "1.0" e "2.0". Dopo aver notato il suo errore, ti ha chiesto se poteva e doveva annullare l'archiviazione di entrambe le versioni per correggere il suo errore.
Individua quale affermazione è corretta.

    Michelle può e deve annullare l'archiviazione di entrambe le versioni
    Per annullare il rilascio di una versione, seleziona Annulla archiviazione dal menu delle azioni. Pertanto, se una versione ha lo stato "RILASCIATO" prima dell'archiviazione, l'annullamento dell'archiviazione riporterà il suo stato a "RILASCIATO". La stessa regola si applica a una versione con lo stato "UNRELEASED". Quindi l'opzione che dice " Michelle può e deve annullare l'archiviazione di entrambe le versioni "1.0" e "2.0" per correggere il suo errore " è CORRETTA .




                                                    Test Pratico 2

















