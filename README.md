# Vefforritun-1-h1
Hópverkefni 1 í Vefforritun 1

Upplýsingar um alla sem unnu verkefnið:

Brynjar Aron Jónsson (baj15@hi.is)
Ester Jenný Birgisdóttir (ejb7@hi.is)
Veturliði Snær Gylfason (vsg8@hi.is)

Hvernig skal keyra verkefnið:

Þarf að keyra 'npm install' til að setja upp pakkana sem við notuðum. Til að keyra verkefnið er notað command-ið "npm run dev" í terminal til að sjá allar breytingar þegar þær eru gerðar. 
Svo til að keyra Stylelint þarf að nota command-ið "npm run lint" Stylelint grípur allar villur í rauntíma og birtir þær í terminal, ásamt hvar þær eru, sem gaf okkur tækifæri að laga allar villur samtímis.

Skipanir eru því eftir farandi í röð:
1. npm install
2. npm run dev
3. npm run lint

Uppsetning verkefnis:  

Vefsíðan er skrifuð í html og útlitið er stýrt með css. Forsíðan er skrá sem kallast index og er eina blaðsíðan ekki í möppunni 'pages'. Inni í möppunni 'pages' er sér html skrá fyrir hverja síðu í verkefninu. 
Einnig erum við með scss möppu sem inniheldur allar scss skrár. Við erum með scss skrá fyrir hverja síðu, sem hefur sama heitið og tilsvarandi html skrá. 
Svo er líka til scss skrá fyrir takka, sem kallast buttons, og fyrir hausinn og fótinn, sem kallast HeaderFooter.
Við erum með nokkrar breytur í config skrá til að staðla útlitið á vefsíðunni. Svo í lokin erum við með styles.scss skrá sem sækir allar scss skrár og þýðir þær í css.
