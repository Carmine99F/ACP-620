                                                    Test Pratico1

1)Quanti campi personalizzati extra possono essere visualizzati su un layout di scheda, al massimo?

    3, è possibile configurare le schede su una bacheca per visualizzare fino a tre campi aggiuntivi. I campi possono essere diversi per gli sprint Backlog e Active se utilizzi una Scrum board. 

2)Harper ha creato un filtro basato sulla seguente query JQL e lo ha condiviso con l'intera organizzazione.
project="OMEGA"
Quindi nota che utenti diversi visualizzano conteggi diversi di problemi quando visualizzano i risultati di questo filtro.
Individua le possibili ragioni. (Scegline quattro)

    Appartentenza al project role
    Appartenenza al gruppo
    Accesso all'applicazione
    Project Permission
    L'opzione che dice " Autorizzazioni progetto " è CORRETTA. Ad esempio, la voce in "Crea problemi" è "Qualsiasi utente che ha effettuato l'accesso" mentre l'unica voce nell'autorizzazione "Sfoglia progetti" è "Reporter". Se crei un problema, puoi vedere il problema perché sei il Reporter. Altrimenti non puoi. Quindi utenti diversi visualizzano conteggi di problemi diversi nel progetto, a seconda di ciò che hanno creato.

    L'opzione che dice " Project role membership " è CORRETTA. Ad esempio, diversi livelli di sicurezza potrebbero richiedere l'appartenenza a diversi ruoli di progetto. Quindi utenti diversi vedrebbero conteggi di problemi diversi a seconda della loro appartenenza a tali ruoli.

    L'opzione che dice " Appartenenza al gruppo " è CORRETTA. Uguale alla risposta "Appartenenza al ruolo del progetto". Ad esempio, diversi livelli di sicurezza potrebbero richiedere l'appartenenza a gruppi diversi. Quindi utenti diversi vedrebbero conteggi di problemi diversi a seconda della loro appartenenza a quei gruppi.

    L'opzione che dice " Accesso all'applicazione " è CORRETTA. Ad esempio, un livello di sicurezza potrebbe richiedere l'accesso all'applicazione Jira Software per visualizzare i problemi a quel livello. Quindi gli utenti che lo hanno vedranno più problemi rispetto agli utenti che non lo fanno.

3)Quando Olivia cerca tutti i problemi con gli stati "Backlog" e "In corso" dal suo progetto, trova 45 problemi.
Ma dalla sua bacheca del progetto, vede solo 28 problemi nelle colonne "arretrati" e "in corso".
Identifica quale configurazione può spiegare questa differenza. (Scegli quattro)

    Column mapping
    Board sub-filter
    Quick filters
    Board Filters
    Devi essere un amministratore di Jira Cloud per configurare la sicurezza a livello di problema.
    Se in questa domanda fosse utilizzata la sicurezza a livello di problema, i problemi non sarebbero accessibili dalla ricerca e dalla bacheca.
    L'opzione che dice " Board filter " è CORRETTA. Questa domanda combina la conoscenza delle configurazioni della scheda e la visibilità dei problemi. Un filtro scheda non mostra necessariamente tutti i problemi del progetto. La query del filtro potrebbe escludere alcuni problemi in base allo stato stesso o ad altri criteri come le etichette o il valore del campo personalizzato. In tal caso, la scheda mostrerà meno problemi. In altre situazioni, il filtro della scheda potrebbe includere più problemi di quelli visualizzati nei risultati di ricerca (ad esempio, se restituisce problemi da più progetti).
    L'opzione che dice " Mappatura colonne " è CORRETTA. Solo perché i nomi delle colonne sono "Backlog" e "In corso" non significa necessariamente che tali stati siano associati a tali colonne. Diversi stati possono essere mappati su una o entrambe le colonne.
    L'opzione che dice " Board sub-filter " è CORRETTA. La domanda non indica se si tratta di una Kanban o di una Scrum Board. Ma se questa è una bacheca Kanban, allora ha un filtro secondario. La query predefinita nel sottofiltro è 'fixVersion in unreleasedVersion() OR fixVersion is EMPTY' ma non deve esserlo. Potrebbe essere modificato per escludere problemi basati su altri criteri. In tal caso, la scheda mostrerà meno problemi.
    L'opzione che dice " Filtri rapidi " è CORRETTA. I filtri rapidi ti consentono di filtrare ulteriormente la raccolta di problemi che compaiono su una bacheca Scrum o Kanban. I filtri rapidi possono essere utilizzati per passare da un tipo di problema all'altro (ad esempio, mostrare solo bug) o per mostrare viste specifiche del team di un backlog comune. Nel nostro caso, se viene cliccato/attivato un filtro rapido, Olivia non sarà in grado di vedere tutti i problemi. Deve quindi disabilitare il filtro rapido e verificare se vengono visualizzati i problemi mancanti.

4)Quali report e gadget sono influenzati dalle impostazioni "Giorni lavorativi" su una bacheca? (Scegli tre)

    Sprint report
    control chart
    Sprint heatl gadget
    