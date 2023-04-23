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

    


















