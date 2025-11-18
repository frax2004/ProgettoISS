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
  - [**P = 1**] [**USR 1**] **As a** player **I want to** access the main menu **so that** I can start a new campaign [**EPC 4**]
  - [**P = 3**] [**USR 2**] **As a** player **I want to** access the main menu **so that** I can access the options [**EPC 4**]
  - [**USR 3**] **As a** player **I want to** choose a character class **so that** I can create a character [**EPC 1**]
  - [**USR 4**] **As a** player **I want to** insert a name **so that** I can create a character [**EPC 1**]
  - [**P = 1**] [**USR 5**] **As a** player **I want to** view the events in the current scenario **so that** I can choose one of them or skip it (next scenario or boss)
  - [**P = 3**] [**USR 6**] **As a** player **I want to** access the main menu **so that** I can view credits [**EPC 4**]
  - [**P = 3**] [**USR 7**] **As a** player **I want to** see the events' description **so that** I can learn about lore
  - [**P = 3**] [**USR 8**] **As a** player **I want to** see the campaign's map **so that** I can view the campaign's info
  - [**P = 2**] [**USR 9**] **As a** player **I want to** access the inventory **so that** I can see the party's stats and equipments
  - [**P = 3**] [**USR 10**] **As a** player **I want to** be able to save the campaign's history on a local file **so that** I can review it later
  - [**USR 11**] **As a** player **I want to** view the contents of the non-fight event **so that** I can interact with it [**EPC 2**] 
  - [**USR 12**] **As a** player **I want to** view the outcome of the event **so that** I can go to the next scenario [**EPC 2**]
  - [**USR 13**] **As a** player **I want to** view the contents of the fight event **so that** I can choose my next action [**EPC 3**]
  - [**USR 14**] **As a** player **I want to** choose an action on my turn **so that** I can use it [**EPC 3**]
  - [**USR 15**] **As a** player **I want to** choose a target on my turn **so that** I can interact with it [**EPC 3**]
  - [**P = 2**] [**USR 16**] **As a** player **I want to** have the choice of discarding an owned item **so that** I can change it with a new one (dropped by boss or bought from shop/market)
  - [**USR 17**] **As a** player **I want to** choose the number of team members **so that** I can continue creating the new campaign
  - [**P = 1**] [**USR 18**] **As a** player **I want to** skip the current scenario **so that** I can go to the next one or I can fight the boss directly
  - [**P = 1**] [**USR 19**] **As a** player **I want to** finish the current level (by defeating the final boss) **so that** I can go to the next level

- Epics
  - [**P = 1**] [**EPC 1**] **As a** player **I want to** create a new campaign **so that** I can play
  - [**P = 1**] [**EPC 2**] **As a** player **I want to** interact with non-fight events **so that** I can access the next scenario
  - [**P = 1**] [**EPC 3**] **As a** player **I want to** interact with fight events **so that** I can access the next scenario 
  - [**EPC 4**] **As a** player **I want to** access main menu **so that** I can see the main options of the game

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
  - View the events options (with details) (disable the events that cannot be played)
  - View the skip options
  - View the inventory option
  - Select an event option (if the event's required hours are less or equal then the user's current hours)
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
- [**USR 11**] Ensure that the player is able to:
  - View the contents (possibile description) of the non-fight event
  - View the non-fight event options (0+)
  - Select one of the options if there is at least one
- [**USR 12**] Ensure that the player is able to:
  - View the event outcome (possibile reward)
  - Close the event tab
- [**USR 13**] Ensure that the player is able to:
  - View the event's description 
  - View the event's enemies
- [**USR 14**] Ensure that the player is able to:
  - View the compact stats (hp and mana) on their turn
  - View the action options on their turn
  - Select one of the action options on their turn
- [**USR 15**] Ensure that if the player selects an ability, then he is able to:
  - View the possible targets
  - Select one of the possibile targets
- [**USR 16**] Ensure that the player is able to:
  - View the stats of new equipment
  - View the discard options (Y/N)
  - Select only one of the options
  - View the 'outcome' label
- [**USR 17**] Ensure that the player is able to:
  - View the 'Insert number of teammates
  - Insert the number of teammates (2-5)
  - View input errors if they happen
- [**USR 18**] (Once skip option is selected [**USR 5**]) Ensure that the player is able to:
  - View the next scenario
  - (Or) View the boss event
- [**USR 19**] Ensure that the player is able to:
  - (If not last level) View the 'Level Completed' label
  - (If not last level) Change to next level tab
  - (If not last level) View the next level first scenario (see [**USR 5**])
  - (If last level) View Campaign's History
  - (If last level) View the save history options (Y/N) (see [**USR 10**])
  - (If last level) Return Main Menu (see [**EPC 4**])