# Progetto Ingegneria Internet e Web 2019/2020
## TCP Over UDP
Implementazione di meccanismi di comunicazione affidabile sopra UDP, in un'applicazione di trasferimento file client/server

### Installazione
- Compilare il programma con il comando `make`. 
- Gli eseguibili generati sono rispettivamente `server` e `client`.

### Utilizzo
- Aprire due terminali.
- Lanciare il comando `./server` sul primo terminale e `./client` sul secondo terminale per stabilire la connessione tra i due processi.
- Per eseguire una operazione digitare sul client un comando tra quelli disponibili e premere invio 
    - 1 = List
    - 2 = Get
    - 3 = Put. 
- Durante l’esecuzione dell’operazione verrà mostrata sul client una barra di avanzamento con la percentuale di download/upload.
- Al termine dell’operazione verrà mostrato il risultato sul terminale del client, e sarà possi-bile digitare un nuovo comando.
- Per terminare l’esecuzione, nel client digitare il comando Close (numero 4 nel menù), nel server uccidere il processo con il comando “Ctrl+C”.
