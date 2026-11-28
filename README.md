# Ball's Rain — Pioggia di sfere

Terzo gioco della serie di [Word Rain](https://github.com/enzocaravano-gk/word-rain) e [Mary's Number](https://github.com/enzocaravano-gk/marys-number): qui non si scrive, si tocca.

- Sfere colorate cadono sulla città: toccale per farle esplodere. Grandi 5 punti, medie 10, piccole 15
- Ogni sfera ha un tempo (senza timer visibile): quando arriva a terra entra nella fila. La fila ha 10 posti: se si riempie, hai perso
- Le sfere speciali con la stella si dividono in sferette piccole e veloci (15 punti l'una) che durano poco
- Ogni livello ha il suo sfondo illustrato in pixel art (cartella `sfondi/`): Salerno, Mare, Roma, Montagna, Luna, Giappone, New York, Parigi; poi si ricomincia
- Ogni livello ha 4 sottolivelli: giorno, tramonto, sera, notte (lo sfondo si scurisce e compaiono le stelle)
- Dopo ogni livello c'è un bonus: 20 bolle con animali e oggetti rimbalzano sullo schermo, il riquadro in alto dice quale trovare, entro un tempo massimo. Il tempo è di 30 secondi da Principiante, 25 da Intermedio, 20 da Master. Sfera sbagliata = 2 secondi e 10 punti in meno
- Classifica arcade con 3 iniziali, salvata nel browser
- Ogni livello porta una novità: cannoncini dal basso (2), più sfere piccole (3), cannoncini ai lati (4), formazioni (5), più arcobaleno (6), tutto insieme (7), gran finale (8)
- Difficoltà "a dente di sega": i sottolivelli salgono, il livello dopo riparte un po' più calmo; dentro ogni sottolivello si alternano onde e brevi respiri
- Combo: sfere di fila senza farne cadere moltiplicano i punti (x2 da 10, x3 da 25, x4 da 45); ogni 20 di combo si libera un posto nella fila a terra
- Potenziamenti (dal 2° livello, quando la situazione si complica): SPADA (10 secondi per tagliare le sfere strisciando il dito), BOMBA (fa esplodere tutte le sfere in campo), SCOPA (libera 2 posti nella fila a terra), CLESSIDRA (dal 3° livello: 6 secondi di rallentatore)
- Teschio: quando le sfere sono tante può scendere una sfera nera col teschio. Non toccarla: farebbe piombare a terra tutte le sfere sullo schermo (se la lasci cadere sparisce)
- Pioggia di sfere: ogni 30-40 secondi, per 8 secondi, arrivano molte più sfere ma più lente
- Presa "al volo" vicino a terra: +5 punti. Se la fila è quasi piena le sfere rallentano un po'
- Dopo il game over puoi ripartire dal livello che avevi raggiunto (pulsante nella classifica)
- Pausa: tocca la barra in alto (telefono) oppure spazio / ESC (computer)

Per giocare in locale basta aprire `index.html` nel browser.

Nessuna risorsa esterna: niente font, script o librerie caricati da altri server.
