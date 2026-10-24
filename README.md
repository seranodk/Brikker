# Brikker

Murbryder i arkade-stil, inspireret af gameplay og fysik fra Arkanoid (1986). Kører i browseren på både mobil og computer — ét `index.html`, ingen afhængigheder.

**Aktuel version: Brikker 0.2.0**

## Spil som app (fuld skærm)
Åbn spillet på GitHub Pages på mobilen og vælg **Føj til hjemmeskærm** (Safari: Del-knappen, Chrome: menuen ⋮). Så starter det i fuld skærm uden browserlinje og kan spilles offline. På Android kan du også trykke på fuldskærmsknappen øverst.

## Spil
- **Mobil:** træk hvor som helst for at styre, tryk for at sende kuglen og skyde.
- **Tastatur:** ← → eller A/D, mellemrum sender/skyder, P pause.
- **Mus:** bevæg for at styre, klik for at sende/skyde.

## Temaer
Neon · Klassisk · Papir — vælges i hovedmenuen eller i pausemenuen.

## Gameplay (som i originalen)
- Bat'et har 8 faste zoner, der bestemmer kuglens vinkel.
- Kuglen bliver hurtigere når den rammer loftet og for hver brik.
- Sølvbrikker kræver flere slag, guldbrikker kan ikke ødelægges.
- Kapsler (kun én ad gangen): **S** langsom, **C** fang, **L** laser, **E** langt bat, **D** tre kugler, **B** warp til næste runde, **P** ekstra liv.
- 8 runder, der derefter gentages med hårdere sølvbrikker og højere fart.

## Versioner
Navngivning: **Brikker 0.x.x** — større ændring hæver første x, mindre ændring hæver andet x.

### Brikker 0.2.0
- Kan installeres som app: fuld skærm, ikon og offline-spil.
- Fuldskærmsknap, og spillet går i fuld skærm ved start på telefoner der understøtter det.
- Hovedmenu-knap under spillet, med bekræftelse.
- Kuglen er 25 % hurtigere.
- Tema og lyd vælges i menuen og pausemenuen.

### Brikker 0.1.0
- Første version: 8 runder, 7 kapsler, 3 temaer, lyd, rekord gemmes lokalt.

## Filer
- `index.html` – spillet til GitHub Pages (med app-installation).
- `game.html` – samme spil i artifakt-udgaven til Claude.
