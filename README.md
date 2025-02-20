# Missione 1: Fare la spesa seguendo una lista
> Nel frigo si inizia a sentire l'eco, perciò è ora di fare rifornimenti!
Visto che dimentico sempre qualcosa, decido di appuntarmi tutto ciò che manca in una lista, così una volta al supermercato, girando tra gli scaffali, posso verificare di aver preso tutto e Ricky non rimane senza crocchette come l'ultima volta, povero! Devo ricordarmi di usare il coupon che scade a fine mese, per il resto dovrebbero bastarmi i contanti che ho in portafogli, sempre se non mi faccio prendere la mano con gli snack extra!

### Funzione:
```
- CERCO IL FRIGO
- SE lo trovo
  - APRO il frigo e dentro.
    - CONTROLLO se ci sono X alimenti
      - SE NO
        - PRENDO il telefono dalla tasca
        - SBLOCCO il telefono
        - APRO l'app delle note
        - SCRIVO gli ingredienti mancanti
        - SE ho scritto tutto
          - SALVO
          - BLOCCO il telefono
      - CHIUDO il frigo

- SE il frigo è chiuso 
  - CERCO la dispensa
  - SE la trovo
    - Ci vado davanti
  - APRO la dispensa
    - CONTROLLO se ci sono X alimenti
      - SE NO
        - PRENDO il telefono dalla tasca
        - SBLOCCO il telefono
        - APRO l'app delle note
        - SCRIVO gli ingredienti mancanti
        - SE ho scritto tutto
          - SALVO
          - BLOCCO il telefono
      - CHIUDO la dispensa

- SE la dispensa è chiusa
  - CERCO lo scaffale del cibo di Ricky
  - SE lo trovo
    - CONTROLLO se c’è cibo sufficiente per Ricky
      - SE NO
        - PRENDO il telefono dalla tasca
        - SBLOCCO il telefono
        - APRO l'app delle note
        - SCRIVO gli ingredienti mancanti
        - SE ho scritto tutto
          - SALVO
          - BLOCCO il telefono
      - SMETTO di guardare lo scaffale

- SE ho finito di controllare il cibo  
  - CERCO il portafogli  
  - SE lo trovo  
    - LO APRO  
    - CONTROLLO quanti contanti ci sono  
      - LI CONTO e li memorizzo  
        - CHIUDO il portafogli  
      - SE NO  
        - CONTROLLO se ho la carta di debito  
        - SE ho la carta  
          - SBLOCCO il telefono
          - CERCO l'app della banca
          - SE la trovo
            - APRO l'app della banca
            - MEMORIZZO quanti soldi ci sono nel conto
            - BLOCCO il telefono
        - SE NO  
          - CHIUDO il portafogli
          - CERTO tutta la casa per la carta di debito
           - SE la trovo
            - SBLOCCO il telefono
            - CERCO l'app della banca
            - SE la trovo
              - APRO l'app della banca
              - MEMORIZZO quanti soldi ci sono nel conto
              - BLOCCO il telefono
      - SE non ho CHIUSO il portafogli, CHIUDO il portafogli
      - SENNO continuo  

    - CERCO il coupon sconto  
    - SE lo trovo  
      - CONTROLLO la data di scadenza  
        - SE il coupon è valido  
          - LO METTO nel portafogli  
        - SE il coupon è scaduto 
          - CERCO un cestino E SE lo trovo 
            - LO BUTTO via
          - SENNO lo rimetto nel portafoglio

- SE ho tutto pronto  
  - CERCO le chiavi di casa  
  - SE le trovo  
    - PRENDO le chiavi  
    - MI ASSICURO di avere telefono, portafogli e chiavi  
    - INDOSSO vestiti necessari  
    - ESCO di casa  
    - CHIUDO la porta  

- SE sono fuori casa  
  - MI DIRIGO verso il supermercato  
  - SE arrivo al supermercato  
    - PRENDO un carrello se la spesa è grande  
    - SE la spesa è piccola  
      - PRENDO un cestino  

- APRO la lista della spesa sul telefono  
- SE la lista è aperta  
  - PER OGNI prodotto nella lista  
    - CERCO lo scaffale corrispondente  
    - SE trovo il prodotto  
      - CONTROLLO prezzo e quantità  
      - SE il prezzo va bene  
        - PRENDO il prodotto  
        - LO METTO nel carrello/cestino  
        - SPUNTO il prodotto dalla lista  
    - SE NON trovo il prodotto  
      - PASSO al prossimo  

- CONTROLLO se voglio prendere uno snack extra  
- SE vedo qualcosa che mi piace  
  - CONTROLLO il prezzo  
    - SE il prezzo rientra nel budget  
      - PRENDO lo snack  
      - LO METTO nel carrello  
    - SE il prezzo è troppo alto  
      - LO LASCIO sullo scaffale  

- SE ho preso tutto  
  - VADO verso la cassa  
  - SE c'è una cassa automatica e ho pochi articoli  
    - USO la cassa automatica  
  - SE ho molti articoli  
    - SCELGO una cassa con cassiere  

- SE è il mio turno alla cassa  
  - METTO i prodotti sul nastro  
  - SE ho un coupon valido  
    - LO CONSEGNO alla cassiere  
  - SE il totale è inferiore ai contanti disponibili  
    - PAGO in contanti  
  - SE il totale è superiore ai contanti disponibili  
    - USO la carta
  - SE ne i CONTANTI ne IL CREDITO sulla carta è abbasta
    - LASCIO n alimenti per far si che posso pagare  

- PRENDO lo scontrino  
- RACCOLGO la spesa nelle borse  
- RIPONGO il carrello se usato  
- TORNO a casa  

- SE arrivo a casa  
  - APRO la porta  
  - PORTO dentro le borse  
  - SE ci sono prodotti da frigo  
    - CERCO il frigo  
    - APRO il frigo  
    - METTO i prodotti dentro il frigo  
  - SE ci sono altri alimenti  
    - CERCO la dispensa  
    - APRO la dispensa  
    - METTO gli altri alimenti dentro la dispensa  
  - SE ci sono crocchette per Ricky  
    - CERCO la ciotola di Ricky  
    - PRENDO la ciotola  
    - VERSO le crocchette nella ciotola
    - ACCAREZZO Ricky

- SE tutto è sistemato  
  - MI RILASSO  
  - SE ho preso uno snack  
    - LO MANGIO
```
&nbsp;
&nbsp;
# Missione 2: Scansionare un documento su più fogli fronte-retro

> Finalmente sono riuscito a ritrovare quella pratica che sembrava essere svanita nel nulla! Che poi, possibile che nel 2025 ci siano ancora così tanti fogli di carta in giro per l’ufficio?! Ora ci penso io: una bella scansione e l’archiviamo in formato digitale, così la prossima volta so già dove andare a cercarla! L’unica pecca è che lo scanner non ha il fronte-retro automatico e mi tocca farlo a mano. Va beh, poco male, almeno sono pochi fogli!

### Funzione:
```
- CERCO la pratica cartacea smarrita nell’ufficio
- SE la trovo
  - RACCOLGO tutti i fogli
  - CONTROLLO se i fogli sono in ordine e completi
    - SE mancano pagine o risultano disordinati
      - CERCO i fogli mancanti negli archivi o nei cassetti
        - QUANDO ho finito, li conservo

- CERCO lo scanner
- SE lo scanner è spento o in pausa
  - ACCENDO lo scanner e verifico il corretto funzionamento
- PER OGNI foglio della pratica
  - POSIZIONO il lato anteriore sul vassoio dello scanner
  - AVVIO la scansione del lato anteriore
  - SE la scansione va a buon fine
    - ROVESCO il foglio per scansionare il retro
    - AVVIO la scansione del lato posteriore
  - SE la scansione non è soddisfacente
    - RIPETO la scansione del foglio

- RACCOLGO tutte le scansioni in un unico file digitale
- CONTROLLO la qualità del file
  - SE noto errori
    - RIPETO la scansione dei fogli problematici
- SALVO il file in formato PDF
- ARCHIVIO il file digitale nella cartella dell’ufficio dedicata agli archivi
- RIPOSIZIONE i fogli originali nell’archivio cartaceo
- SE tutto è in ordine
  - MI RILASSO
```