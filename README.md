# htmlcss-media-query

Esercizio da fare da soli dopo la lezione di giovedì 5/11 sulle media query. È la pagina del secondo live coding: ora la rifai tu.

## Cosa devi fare

Parti dalla pagina di questa repo: un header, sei card e un banner. Oggi l'icona e il menu si vedono insieme, le card vanno a capo da sole e il banner sta sempre in fondo. Con le media query decidi tu cosa succede a ogni larghezza, come negli screenshot.

**L'HTML non si tocca**: scrivi solo in `css/style.css`. Si lavora mobile first.

## Cosa trovi qui

```
├── index.html               ← la pagina, da non modificare
├── css/style.css            ← qui scrivi le media query
├── img/                     ← le immagini delle card
├── screenshot-mobile.jpg    ← la pagina finita a 400px
├── screenshot-tablet.jpg    ← la pagina finita a 800px
└── screenshot-desktop.jpg   ← la pagina finita a 1300px
```

## Come procedere

1. Fai il **fork** di questa repo: bottone **Fork** in alto a destra, lascia il nome `htmlcss-media-query`. Il fork è la tua consegna: così il docente la vede.
2. Clona il **tuo** fork sul computer (`git clone` con l'indirizzo del tuo fork, non di questa repo).
3. Apri la cartella e lavora con l'inspector aperto. La barra dei dispositivi (`Ctrl+Shift+M` su Windows, `Cmd+Shift+M` su Mac) ti fa scrivere la larghezza esatta.
4. Fai commit e push sul tuo fork.

## Cosa deve fare la pagina

1. **Il menu**: sotto i 576px si vede solo l'icona, da 576px solo le voci del menu.
2. **Una colonna**: togli la regola che fa andare a capo le card da sole. Si riparte da una card per riga, a ogni larghezza.
3. **Le colonne**: una sotto i 676px, due da 676px, tre da 876px, quattro da 1200px. Il gap resta di 24px.
4. **Il banner**: sopra tutte le card fino a 875px, sotto tutte le card da 876px in su.

Come verificare ogni passo e i suggerimenti sono nella pagina **Media query** che trovi nel canale del corso, sezione *Esercizio*. Per ripassare: [dispensa Media query](https://kb-aiwd.andreadev237.workers.dev/lezioni/css-media-query) e [dispensa Layout](https://kb-aiwd.andreadev237.workers.dev/lezioni/css-layout).

Se usi l'AI, il file `AGENTS.md` la fa lavorare da tutor: ti fa domande e ti indica dove guardare, senza darti la soluzione.

## Bonus (facoltativo)

Togli `flex-grow: 1` dalle card e prova i valori di `justify-content` sulla `.row`. Sai spiegare perché a 1300px si muove solo l'ultima riga di card, e a 1100px nessuna?

## Consegna

Nessuna scadenza. Fai push sul tuo fork, poi incolla il link nel canale del corso.
