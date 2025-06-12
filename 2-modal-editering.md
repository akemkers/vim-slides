# Modal editering

- "Vanlige" editorer har ikke moduser. Alt du gjør er å skrive.
- Hva når du bare vil navigere, eller flytte, eller endre?
- Kombinasjon av mus, og diverse ctl/alt/shift+piltaster


Vim løser dette ved å dele opp i en en rekke forskjellige *moduser*.
Hver modus er optimalisert for et mål. 


## Normal mode (esc)
- Når man er i *normal mode*, så er målet å navigere og redigere eksisterende tekst
- Tastaturet vil ikke virke som du tror, alle bokstaver er nå forvandlet til kommandoer
- Feks H   J   K   L 
- Dette er standard modusen, kommer tilbake hit ved bruk av esc


## Insert mode (i, a, o)
- Den "vanlige" modusen man kjenner igjen som standard fra andre editorer
- Kan skrive tekst, bruke backspace, som normalt


## Visual mode (v)
- For når man vil markere tekst


## Command mode (:)
- Kommandoer
- skrive til fil, åpne ny fil, search/replace
