Ciao ragazzi,
esercizio di oggi: *Social Posts*
nome repo: **js-social-posts
Descrizione**
Ricreiamo un feed social aggiungendo al layout di base fornito, il nostro script JS in cui:
*Milestone 1* - Prendendo come riferimento il layout di esempio presente nell'html, stampiamo i post del nostro feed attraverso javascript.
*Milestone 2* - Se clicchiamo sul tasto "Mi Piace" cambiamo il colore al testo del bottone e incrementiamo il counter dei likes relativo.
Salviamo in un secondo array gli id dei post ai quali abbiamo messo il like.
Numero push minimo: 10/12
P.S. Occhio al nome della repo! Ricordatevi che deve essere js-social-posts!
***BONUS*
1. Formattare le date in formato italiano (gg/mm/aaaa)
2. Gestire l'assenza dell'immagine profilo con un elemento di fallback che contiene le iniziali dell'utente (es. Luca Formicola > LF).
3. Al click su un pulsante "Mi Piace" di un post, se abbiamo già cliccato dobbiamo decrementare il contatore e cambiare il colore del bottone.
*Consigli del giorno:*
Ragioniamo come sempre a step.
Prima scriviamo nei commenti la logica in italiano e poi traduciamo in codice.
console.log() è nostro amico.
Quando un pezzo di codice funziona, chiediamoci se possiamo scomporlo in funzioni più piccole.
Buon lavoro! (modificato) 

(Milestone 1)

1 dal Dom recupero il contenitore dove andrò a immettere la struttura tramite java-script

2 effettuo un ciclo forEach per iterare gli oggetti dell'array

2 vado a immettere dove ho recuperato la struttura creata tramite forEach

(Milestone 2)

1 recuperiamo il tasto dei like dal dom

2 creo l'array vuoto dopo andrò ad aggiungere gli id dei post

3 creo un evento click per il like
-con l'evento deve diventare verde il bottone ed il counter dei like deve aumentare

4 dopo in base al like pusha dentro l'array vuoto l'id del post

