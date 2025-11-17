# ProgettoISS


### Requisiti Non Funzionali

- **Requisiti di sviluppo** : 
  - Il linguaggio di programmazione da utilizzare per l'implementazione è `Java 21` (minimo)
  - Lo strumento di sviluppo condiviso è Git
  - Lo strumento di organizzazione dello sviluppo agile/scrum sarà jira (o trello, da vedere)

- **Requisiti di funzionamento** :
  - Il software avrà come **target** qualunque sistema operativo che supporta il `JRE` (Java Runtime Environment).

- **Requisiti di spazio** :
  - Requisiti dell'architettura :
    - Ordine di Mib RAM
    - Ordine di Mib DISCO

- **Requisiti di usabilità** : 
  - E' prevista la separazione per le interfacce di I/O
  - I menù devono essere semplici
    - Un menù è semplice se soddisfa i seguenti requisiti:
      - Massimo 10 opzioni
      - Il numero di caratteri di un opzione è limitato a 256
  - La creazione dei personaggi dovrà essere fatta in 3-8 passaggi
  - I nomi dei personaggi devono avere 1-20 caratteri

### Requisiti Funzionali

- User stories
  - [**USR 1**] **As a** player **i want to** access the main menu **so that** i can start a new campaign
  - [**USR 2**] **As a** player **i want to** access the main menu **so that** i can access the options
  - [**USR 3**] **As a** player **i want to** choose a character class **so that** i can create a character [**EPC 1**]
  - [**USR 4**] **As a** player **i want to** insert a name **so that** i can create a character [**EPC 1**]
  - [**USR 5**] **As a** player **i want to** view the events in the current scenario **so that** i can choose one of them or skip it (next scenario or boss)
  - [**USR 6**] **As a** player **i want to** access the main menu **so that** i can view credits
  - [**USR 7**] **As a** player **i want to** see the events' description **so that** i can learn about lore
  - [**USR 8**] **As a** player **i want to** see the campaign's map **so that** i can view the campaign's info
  - [**USR 9**] **As a** player **i want to** access the inventory **so that** i can see the party's stats and equipments
  - [**USR 10**] **As a** player **i want to** be able to save the campaign's history on a local file **so that** i can review it later
  - [**USR 11**] **As a** player **i want to** view the contents of the non-fight event **so that** i can interact with it [**EPC 2**] 
  - [**USR 12**] **As a** player **i want to** view the outcome of the non-fight event **so that** i can go to the next scenario [**EPC 2**]
  - [**USR 13**] **As a** player **i want to** view the contents of the fight event **so that** i can choose a target to fight [**EPC 3**]
  - [**USR 14**] **As a** player **i want to** choose an action on my turn **so that** i can use it [**EPC 3**]
  - [**USR 15**] **As a** player **i want to** choose a target on my turn **so that** i can interact with it [**EPC 3**]
  - [**USR 16**] **As a** player **i want to** view the outcome of the fight event **so that** i can go to the next scenario [**EPC 3**]

- Epics
  - [**EPC 1**] **As a** player **i want to** create a player **so that** i can play
  - [**EPC 2**] **As a** player **i want to** interact with non-fight events **so that** i can access the next scenario
  - [**EPC 3**] **As a** player **i want to** interact with fight events **so that** i can access the next scenario 

### Acceptance Criteria
- [**USR 1**] Ensure that the player is able to:
  - View the main menu
  - View the "start" option
  - Select the "start" option 
- [**USR 2**] Ensure that the player is able to:
  - View the main menu
  - View the "options" option
  - Select the "options" option
- [**USR 3**] Ensure that the player is able to:
  - View all the possibile playable character classes
  - Select exactly one of the playable character classes
- [**USR 4**] Ensure that the player is able to:
  - View the text entry
  - Insert the character's name
- [**USR 5**] Ensure that the player is able to:
  - View "Menu scenario"
  - View the events options (with details)
  - View the skip options
  - View the inventory option
  - Select an event option
  - Select a skip option
  - Select the inventory option
- [**USR 6**] Ensure that the player is able to:
  - View the main menu
  - View the "credits" option
  - Select the "credits" option 
- [**USR 7**] Ensure that the player is able to:
  - Read the event's description
- [**USR 8**] Ensure that the player is able to:
  - View the campaign's info
- [**USR 9**] Ensure that the player is able to:
  - View the party's inventory
  - View the party's stats
  - View the party's buffs
- [**USR 10**] Ensure that the player is able to:
  - View the "save history" option
  - Select the "save history" option
