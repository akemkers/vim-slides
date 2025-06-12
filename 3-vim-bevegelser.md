# 3. Vim bevegelser

- Når man er i *Normal mode* så forvandles tastaturet til en kommando sentral

Herfra her man kommandoer for å: 

- Gå inn i andre moduser. 
- slette ord, endre linjer, markere paragrafer, innholdet i paranteser ++++
- bevege seg rundt, markere tekst, kopiere, 


## Bevegelse + operasjoner = aksjon

- en *bevegelse* er en kommando som tar deg et sted
- en *operasjon* er en kommando som gjør noe med bevegelsen

### Noen bevegelser
- w = gå til neste ord
- b = gå til forrige ord
- e = gå til enden av et ord
- $ = gå til slutten av en linje
- _ = gå til starten av en linje

### Noen operasjoner
- d (delete)= slette
- c (change)= endre
- v (visual) = visualisere
- y (yank) = kopiere

### Eksempler på aksjoner
- dw = slett frem til neste ord
- yb = kopier bakover til forrige ord
- c$ = slett alt frem til slutten av linjen, og sett meg inn i insert modus


### Eksempler på mer avanserte aksjoner
- di" = slett alt _inni_ nærmeste fnutter
- ci( = slett alt _inni_ nærmeste paranteser
- va{ = visualiser alt _rundt_ nærmeste krøllparanteser

```js 

function myTestFunction(arg) {
    const argSquared = arg * arg
    console.log("Vim er gøy!")

    return argSquared
}

```


### Eksempler på søke-bevegelser
- / = gå til første treff på søk etter noe. Deretter n for neste treff eller N for forrige
- f + bokstav = gå til første treff på en bokstav på denne linjen (semi for neste, komma for forrige )



- Fungerer litt som lego, hvis man kjenner de ulike brikkene 
  så kan man mikse og matche sammen for å bygge kommandoer
- Trenger ikke så mye. Med 5-10 bevegelser, og 3-4 operatorer så dekker man 90%.
