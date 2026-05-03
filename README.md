# Gestione Centro Sportivo
# Descrizione
Il progetto Gestione Centro Sportivo  ha lo scopo di modellare un sistema software per la gestione delle attività di un centro sportivo, sviluppato nell’ambito del corso di Programmazione Object Oriented e Basi di Dati.

Il sistema consente di gestire:
- utenti (clienti e istruttori)
- corsi sportivi
- prenotazioni
- pagamenti
- strutture del centro sportivo

---

##Obiettivi
L’obiettivo del progetto è progettare il dominio applicativo utilizzando i principi della Programmazione Orientata agli Oggetti (POO), definendo le principali entità e le relazioni tra esse.

---

# Modello del dominio
Le principali entità del sistema sono:
- Utente (classe astratta)
- Cliente
- Istruttore
- Corso
- Prenotazione
- Pagamento
- Struttura

Le relazioni tra queste entità sono rappresentate nel diagramma UML delle classi.

---

##  Tecnologie utilizzate
- Java
- Maven
- PostgreSQL (previsto per le fasi successive del progetto)

---

---

# Struttura del progetto
gestione centro sportivo 
│
├── README.md
├── pom.xml
└── src/
    └── main/
        └── java/
            ├── Utente.java
            ├── Cliente.java
            ├── Istruttore.java
            ├── Corso.java
            ├── Prenotazione.java
            ├── Pagamento.java
            └── Struttura.java

