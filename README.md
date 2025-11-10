# ProgettoISS


### Requisiti Non Funzionali

- **Requisiti di sviluppo** : 
  - Il linguaggio di programmazione da utilizzare per l'implementazione è `Java 21` (minimo)
  - Lo strumento di sviluppo condiviso è Git
  - Lo strumento di organizzazione dello sviluppo agile/scrum sarà jira (o trello, da vedere)

- **Requisiti di funzionamento** :
  - Il software avrà come **target** qualunque sistema operativo che supporta il `JRE` (Java Runtime Environment).

- **Requisiti di spazio** :
  - Requisiti minimi dell'architettura :
    - 2 GB RAM
    - 512 MB Archiviazione

- **Requisiti di usabilità** : 
  - E' prevista la separazione per le interfaccie di I/O
  - I menù devono essere semplici
    - Un menù è semplice se soddisfa i seguenti requisiti:
      - Massimo 10 opzioni
      - Il numero di caratteri di un opzione è limitato a 256
  - La creazione dei personaggi dovrà essere fatta in 3-8 passaggi

### Requisiti Funzionali

- User stories
  - **As a** player **i want to** access the main menu **so that** i can start a new campaign
  - **As a** player **i want to** access the main menu **so that** i can access the options
  - **As a** player **i want to** choose a character class **so that** i can create a character [EPC 1]
  - **As a** player **i want to** insert a name **so that** i can create a character [EPC 1]
  - **As a** player **i want to** view the events in the current scenario **so that** i can choose one of them or skip it (next scenario or boss)
  - **As a** player **i want to** access the main menu **so that** i can view credits
  - **As a** player **i want to** see the events' description **so that** i can learn about its kind and rewards 
  - **As a** player **i want to** see the campaign's map **so that** i can view the campaign's info
  - **As a** player **i want to** access the inventory **so that** i can see the party's stats and equipments
  - **As a** player **i want to** be able to save the campaign's history on a local file **so that** i can review it later

- Epics
  - [EPC 1] **As a** player **i want to** create a player **so that** i can play
