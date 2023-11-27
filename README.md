# Vue slider

Creiamo uno slider di immagini simile a quello già utilizzato, ma con vue js.
Utilizzando la struttura base nello slider, andiamo a creare con un v-for le copie di quella strutture tante volte quante sono le immagini nel nostro array di oggetti immagini. Dopodiche andiamo ad inserire un src corrispondente al nome dell'immagine, un titolo e una descrizione. Creiamo una variabile currentIndex per l'assegnazione della classe active all'immagine corrispondente all'indice.

Andiamo ad aggiungere un evento click a prev e next, con cui incrementare o decrementre l'index.

Nello stesso modo creiamo le thumbnail, a cui inseriamo un evento click per mostrare l'immagine corrispondente alla thumbnail cliccata.
Nell javascript, nella parte `mounted` che agisce dopo la creazione dell'app, inseriamo una funzione che fa da autoplay ogni 3 secondi dal caricamento della pagina.

Aggiungo una funzione che gestisce l'impostazione del timer ed, all'over con il mouse si rimuove, mentre al mouse out si reimposta.