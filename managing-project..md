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

1)Di seguito sono riportate le impostazioni di configurazione nel progetto gestito dall'azienda "RISE":

    Project Lead : James
    
    --
    Default Assignee: Project Lead
    -- 
    
    Component          Component Lead          Default Assignee
    ------------------------------------------------------------
    Alpha              Rihana                  Component Lead
    Beta               Amelia                  Component Lead
    Gamma              Sophia                  Project Default
    Delta              Jeniffer                Unassigned   

Hai creato una nuova issue, selezionato tutti e 4 i componenti e selezionato Elijah come assegnatario.

A chi verrà assegnato l'issue appena creata?

    Spiegazione : Nel caso di problemi con più componenti, la struttura dell'assegnatario funziona dall'alto verso il basso, cioè dal meno specifico al più specifico. Il più specifico (Component Lead) ha la precedenza sugli altri. Si supponga, ad esempio, che un problema abbia più componenti e che per alcuni di questi componenti sia selezionata l'opzione Non assegnato. In tal caso, per alcuni è specificato un responsabile del progetto e per altri un responsabile del componente, quindi il responsabile del componente avrà sempre la precedenza come assegnatario. In sintesi, ecco la regola da ricordare (controlla anche lo schema qui sotto):
    L'emissione sarà assegnata a:

    Assegnatario selezionato

    Se non viene selezionato alcun assegnatario allora --> Component Lead (Component Id Ascending Order)

    Se non è selezionato alcun componente, allora --> Predefinito progetto

    Se non è definita alcuna impostazione predefinita del progetto, allora --> Project Lead

    Quindi la questione appena creata sarà assegnata a " Elia " poiché è lui l'assegnatario che è stato selezionato. 

    Nota che nella documentazione troverai questo:

    L'assegnatario predefinito di un componente sostituirà l'assegnatario predefinito generale del progetto. Se qualcuno crea un problema con più di un componente e gli assegnatari predefiniti per tali componenti sono persone diverse, Jira assegna il problema all'assegnatario predefinito del componente che è il primo in ordine alfabetico.

    Questo non è corretto . L'assegnazione non è fatta secondo “il componente che è primo in ordine alfabetico”. Puoi provare il seguente esempio:

    Test1: creare tre componenti nel seguente ordine: prima "Component1", quindi "Component2" e quindi "Component3". Quindi assegnare a ciascun componente un lead componente diverso e impostare l'assegnatario predefinito di ciascun componente sul relativo lead componente. Crea un problema, lascia l'assegnatario come automatico e scegli tutti e tre i componenti. Il problema verrà automaticamente assegnato al lead componente del componente "Componente1" poiché il suo ID componente sarà il più basso.

    Test2: eliminare tutti e tre i componenti del test "Test1". Ora crea gli stessi componenti ma in un ordine diverso: "Component2" prima, poi "Component1" secondo, e poi, infine, il "Component3". Come per il “Test1” assegnare ad ogni componente un capogruppo diverso e impostare l'assegnatario di default di ogni componente al suo capogruppo. Crea un problema, lascia l'assegnatario come automatico e scegli tutti e tre i componenti. Il problema verrà assegnato automaticamente al lead componente del componente "Componente2" poiché il suo ID componente sarà il più basso.

    Queste informazioni sono state inviate al team di Atlassian.


2)Richard ha creato una nuova bacheca gestita dall'azienda utilizzando il menu "Crea bacheca".
Ha utilizzato l'opzione "Board da un progetto esistente" e ha scelto il progetto Kanban gestito dall'azienda "UPSILON", a cui il suo team ha già accesso.
Tuttavia, quando ha inviato l'URL della scheda al suo team, non è stato possibile accedervi.
Identificare perché?

    L'opzione che dice " A Richard manca l'autorizzazione globale "Crea oggetti condivisi" " è CORRETTA. Se crei una bacheca tramite la pagina Bacheche in Jira (URL: /jira/boards, accessibile anche quando fai clic su "Visualizza tutto", controlla lo screenshot qui sotto), non sarai in grado di condividerla, a meno che tu non abbia l'opzione "Crea Autorizzazione globale degli oggetti condivisi.
    Se crei la bacheca tramite i metodi seguenti, non hai bisogno dell'autorizzazione globale "Crea oggetti condivisi" per condividere la bacheca:
    Creazione di un progetto (in cui viene creata una bacheca per il progetto per impostazione predefinita)
    Configurare Jira Software per la prima volta (dove ti viene chiesto di creare un progetto, che crea anche una bacheca per il progetto)
    Copiare una bacheca (la bacheca copiata sarà condivisa con gli stessi utenti della bacheca originale)

3)Quale affermazione è falsa riguardo le label?

    - è possibile utilizzare il campo label in un Issue Statistic gadget
    -Le label sono cliccabili
    -Le label sono case-sensitive
    -Non è possibile rimuovere una label una volta creata

    Spiegazione: le label  consentono alle persone di contrassegnare le issue con frammenti di testo riutilizzabili immessi come testo in formato libero. Jira suggerisce le etichette esistenti per ridurre gli errori di immissione. Le persone possono anche creare nuove etichette digitando nel campo dell'etichetta.
    L'opzione che dice “ Non è possibile rimuovere un'etichetta una volta creata ” è falsa e quindi CORRETTA. Per eliminare completamente una label  dal tuo sito Jira, la label deve essere prima rimossa da tutte le issue in quel sito. Una volta che l'etichetta è stata rimossa da tutte le issue , non sarà più visibile quando si sfogliano le etichette.


4)Identifica quali funzionalità NON sono supportate dai progetti gestiti dal team.

    -Aggiungi un campo "affects version" ai campi esistenti di un issue type
    -Create a custom issue type
    -Aggiungi un campo "Fix version" ai campi esistenti di un issue type
    -Add a screen transition for a workflow
    -Personalizza l'indirizzo email di notifica del progetto utilizzato per inviare email

    L'opzione che dice " Aggiungi una transizione di schermata per un flusso di lavoro " NON È SUPPORTATA; quindi è CORRETTO : non è possibile aggiungere transizioni di schermate ai flussi di lavoro nei progetti gestiti dal team.
    L'opzione che dice " Aggiungi un campo " Versioni interessate " ai campi esistenti di un tipo di problema " NON È SUPPORTATA e quindi è CORRETTA . Di seguito è riportato un elenco di tutti i campi e tipi di campo disponibili nei progetti gestiti dal team. Come puoi notare, non esiste un campo "Versioni interessate". 

5)Un progetto Kanban gestito dall'azienda utilizza il seguente schema di autorizzazione:

    Permission         Users/Groups/Project roles
    ------------------------------------------------
    Administer         Project Role (Administrators)
    Projects
    --
    Browse Projects    Project Role (Administrators)
                       Project Role (Global Team)
    --
    Modify Reporter    Any logged-in user
    --
    Assignable User    Project Role (Developers)
                       Project Role (Administrators)
                       Project Role (Feature Team)
    -- 
    Edit issues         Project Role (Developers)
                        Project Role (Administrators)
                        Project Role (Global Team)
                        Project Role (Feature Team)
    --
    Assign issues      Project Role (Administrators)
                       Project Role (Feature Team)

Olivia deve essere in grado di:
Modifica l'assegnatario
Modify Reporter
Non le dovrebbero essere concesse più autorizzazioni del necessario.
Di quale ruolo o ruoli ha bisogno Olivia per soddisfare i requisiti di cui sopra garantendo al contempo il principio del privilegio minimo?


    Future team and Global team

    "Modifica l'assegnatario" → Olivia necessita dell'autorizzazione "Assign Issue". Questa autorizzazione consente alle persone di modificare il valore del campo Assegnatario su qualsiasi issue del tuo progetto. Non consente di assegnare problemi alle persone (vedere Autorizzazione utente assegnabile ). Nel nostro caso, a due ruoli viene concessa questa autorizzazione: "Amministratori" e "Team di funzionalità".

    "Modifica il reporter" → Olivia necessita dell'autorizzazione al progetto "Modifica reporter". Questa autorizzazione consente alle persone di modificare il valore del campo Reporter predefinito su qualsiasi problema del tuo progetto. Il campo Reporter viene impostato automaticamente sull'autore del problema al momento della creazione del problema. Ciò consente a qualcuno di creare problemi per conto di qualcun altro. Nel nostro caso, questa autorizzazione è concessa a tutti gli utenti che hanno effettuato l'accesso.
    Tieni presente che nei progetti software, le persone devono avere accesso al prodotto a Jira Software per utilizzare questa autorizzazione.
    Oltre a questi due requisiti, Olivia necessita delle autorizzazioni del progetto "Sfoglia progetti" e "Modifica problemi" per poter visualizzare e modificare i problemi. Perché senza queste due autorizzazioni, i requisiti di cui sopra non possono essere soddisfatti. In base allo schema di autorizzazione di cui sopra, i ruoli "Amministratori" e "Team globale" possono visualizzare e modificare i problemi.
    In sintesi, Olivia ha bisogno di: ("Amministratori" O "Team di funzionalità") E ("Amministratori" O "Team globale"). Quindi abbiamo due soluzioni:
    Soluzione 1 → Assegnale solo il ruolo di "Amministratori": questo le consentirà di essere anche l'amministratore del progetto e come tale avrà più autorizzazioni del necessario. Questa opzione non è buona poiché il principio del minimo privilegio non è rispettato.
    Soluzione 2 → Assegnale due ruoli, "Feature team" e "Global Team". Il ruolo "Feature team" è necessario anche se le concederà l'autorizzazione "Utente assegnabile", ma avrà meno privilegi che se le fosse concesso il "ruolo di amministratore".
    Quindi l'opzione che dice " Il ruolo "Feature Team" e il ruolo "Global Team" " è CORRETTA. 


6)Vuoi aggiungere un task secondario all'ambito di uno sprint attivo.
Sapendo che la "Stima rimanente e il tempo impiegato" è abilitato su questa Scrum Board, come verrà trattata la sottoattività?

    L'attività secondaria verrà trattata come una modifica dell'ambito e si rifletterà nel  burndown chart
    l Burndown Chart si applica solo ai board Scrum. Sono inclusi solo gli Story Point sulle attività principali. Le attività secondarie non lo sono.
    Se aggiungi una sottoattività a un problema in uno sprint attivo, viene trattata come una modifica dell'ambito. Tuttavia, questa modifica dell'ambito si rifletterà nel grafico di burndown solo se utilizzi i campi Stima rimanente o Tempo trascorso sulla scheda. Quindi l'opzione che dice " Il task secondario verrà trattato come una modifica dell'ambito e si rifletterà nel grafico di burndown " è CORRETTA.



7) l tuo team utilizza un progetto gestito dall'azienda per gestire il proprio lavoro. Stanno lavorando alla versione "1.0" che ha lo stato " UNRELEASED ".
Il tuo team si è rivolto a te con i seguenti requisiti:
Sposta tutti i problemi irrisolti dalla versione "1.0" alla nuova versione "2.0"
Mantenere la versione "1.0" come opzione disponibile nel campo di sistema "Versioni interessate".
Quale singola azione dovresti eseguire per soddisfare entrambi i requisiti di cui sopra?

    Rilasciare la versione 1.0
    L'opzione che dice " Release version 1.0 " è CORRETTA . Quando si rilascia una versione, Jira suggerisce automaticamente di spostare i problemi irrisolti in una versione che dovrebbe essere selezionata o di ignorare i problemi irrisolti (vedi screenshot sotto). Quindi l'operazione da eseguire è “Rilasciare la versione 1.0”. Quindi la risposta corretta è 1.

8)Alan è nuovo in Jira e ha appena creato il suo primo progetto gestito dal team da un modello Scrum.
Alan vuole usare "Tempo" invece di "Punti storia" come stima.
Identifica la sezione delle impostazioni del progetto in cui Alan può farlo.

    Features
    Spiegazione : l'impostazione della "Stima" in un progetto gestito dal team Scrum può essere eseguita utilizzando la pagina "Features" . Quindi l'opzione che dice " Features " è CORRETTA .

9)Un utente Jira ha rilasciato le seguenti dichiarazioni:
Affermazione 1: Jira non dispone di una funzione per consentire a un utente di modificare il monitoraggio del tempo di altri utenti
Dichiarazione 2: Jira non dispone di una funzione per consentire a un utente di eliminare i commenti di altri utenti
Cosa ne pensi di queste due affermazioni?

    Entrambe le affermazioni 1 e 2 non sono corrette


10)Più team stanno lavorando sulla stessa applicazione e devono eseguire sprint paralleli.
Quale tipo di progetto supporta questa funzione?

    Sia progetti gestiti dal team che dall'azienda
    Spiegazione: la funzione Sprint paralleli consente di abilitare più sprint attivi che vengono eseguiti in parallelo tra loro. Ad esempio, se hai due team che lavorano sullo stesso backlog, ogni team può ora lavorare simultaneamente sul proprio sprint attivo.
    Questa funzione è stata recentemente rilasciata per i progetti gestiti dal team (controlla JSWCLOUD-17195 ).


11)In qualità di proprietario del prodotto, utilizzi regolarmente le funzionalità di votazione e visualizzazione. Ora devi aggiornare l'elenco degli osservatori in modo che i membri del tuo team possano ricevere aggiornamenti su storie importanti. Sfortunatamente, hai notato che non puoi aggiornare l'elenco degli osservatori.
Quale configurazione deve essere aggiornata?

    Concedi l'autorizzazione "Manager watchers"
    L'opzione che dice " Concedi l'autorizzazione al progetto "Gestisci osservatori" " è CORRETTA.   Infatti, non avere l'autorizzazione del progetto "Gestisci osservatori" non ti consentirà di aggiungere/rimuovere osservatori a un problema.


12)Lisa è la scrum master del progetto Kanban gestito dall'azienda "ZETA".
Sebbene possa creare, modificare, trasferire e assegnare tutte le issue del suo progetto, ha recentemente notato che non è in grado di impostare le "Fix version".
Quale permesso manca a Lisa?

    "Resolve Issue" project permission
    L'opzione che dice "Resolve Issue " è CORRETTA. In effetti, questa autorizzazione consente alle persone di impostare o cancellare un valore nel campo Risoluzione. Consente inoltre alle persone di impostare il campo Versione correzione per i problemi.

13)Quale dei seguenti requisiti può essere soddisfatto solo utilizzando il campo "Componenti" anziché un campo personalizzato nei progetti gestiti dall'azienda? (Scegline due)


    -Le issue sono facilmente identificabili senza ulteriori configurazioni
    -Il campo deve essere obbligatorio in fase di creazione e determina l'assegnatario

    L'opzione che dice “ Il campo deve essere obbligatorio durante la creazione e determinare l'assegnatario ” è CORRETTA. I componenti e i campi personalizzati possono essere impostati come obbligatori, ma solo i componenti possono determinare l'assegnatario. Un componente può essere utilizzato per sovrascrivere qualsiasi assegnatario predefinito a livello di progetto. Inoltre, l'assegnatario predefinito di un componente può essere uno dei seguenti: Predefinito progetto, Responsabile componente, Responsabile progetto e Non assegnato.

    L'opzione che dice " Le issue associate sono facilmente identificabili senza ulteriori configurazioni " è CORRETTA . Dalla pagina Componenti nella barra laterale del progetto, puoi facilmente verificare quanti problemi fanno riferimento a ciascun componente. Inoltre, puoi fare clic sul link per ottenere l'elenco di questi problemi (controlla lo screenshot qui sotto). I campi personalizzati non hanno questa funzione.

14)Quale tipo di collegamento non è supportato da Jira?

    FTP web link
    Un link a una issue di Jira in un altro sito
    Spiegazione: è possibile collegare i problemi per tenere traccia del lavoro duplicato o correlato. Puoi, ad esempio: 
    Crea un nuovo problema collegato da un problema esistente in un progetto di servizio o progetto aziendale sullo stesso sito Jira su un altro sito
    Crea un'associazione tra un problema e una pagina Confluence
    Collega un problema a qualsiasi altra pagina web
    Quindi l'opzione che dice " An FTP web link " è falsa e quindi è CORRETTA

15)Hai appena assunto un nuovo scrum master che si unisce al tuo team.
Deve essere in grado di creare e riordinare gli sprint nella Scrum Board gestita dall'azienda.
Identificare quale dei seguenti requisiti è necessario per soddisfare questo requisito.

    Permission project
    Product Access

    L'opzione che dice " Permission project " è CORRETTA. In effetti, il nuovo scrum master necessita dell'autorizzazione del progetto "Gestisci sprint". Questa autorizzazione consente alle persone di creare, avviare e completare gli sprint nel progetto. Ciò include la regolazione della durata e dell'obiettivo dello sprint.

    Questa autorizzazione dipende dall'accesso del prodotto a Jira Software. Scopri di più su come consentire alle persone di accedere ai tuoi prodotti Atlassian . A seconda della complessità della query del filtro della tua bacheca, potresti aver bisogno di ulteriori considerazioni durante la configurazione dell'autorizzazione Gestisci sprint per gli utenti. Ad esempio, se una bacheca contiene sprint di più progetti (compresi i progetti di servizio), gli utenti devono disporre dell'autorizzazione Gestisci sprint in ogni progetto per completare correttamente gli sprint. Per ulteriori informazioni sull'impatto dei filtri complessi e sui modi per semplificare la query del filtro, consulta Utilizzo dell'autorizzazione Gestisci sprint per i casi avanzati .

    Esistono alcune azioni sprint (ad esempio, l'aggiunta di problemi agli sprint o la rimozione di problemi dagli sprint) che richiedono le autorizzazioni Pianifica problemi e Modifica problemi per avere esito positivo.

    L'opzione che dice " Accesso al prodotto " è CORRETTA . Come spiegato in precedenza, l'autorizzazione del progetto "Gestisci sprint" da sola non è sufficiente perché dipende dall'accesso del prodotto a Jira Software.


16)Mary è board administrator of a company-managed Kanban Board  “Delta Board”. Di solito lavora in coppia con James, l'amministratore del consiglio di molti altri consigli.
Ha provato ad aggiungere James come nuovo amministratore del consiglio per il consiglio "Delta Board", ma non è in grado di ottenere l'elenco degli utenti suggeriti. Identificare perché?























