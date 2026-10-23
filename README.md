# Blackjack – evropský herní salon

Jednostránková hra blackjack proti dealerovi (čisté HTML/CSS/JS, bez závislostí a bez buildu).

**Hrát:** `https://TVOJE-JMENO.github.io/NAZEV-REPOZITARE/`

## Funkce
- animované rozdávání, split, double, surrender, even money
- nastavitelná pravidla (počet balíčků, CSM, H17/S17, peek/ENHC, výplata BJ, DAS, RSA, HSA…) a předvolby (Základní, Vestec Casino)
- basic strategy počítaná z aktivních pravidel, trénovací režim
- shoe s Hi-Lo running countem, statistiky a graf bankrollu
- zvuky kasina, jazzová hudba na pozadí, vibrace na mobilu

## Struktura
```
index.html     celá hra (kód + zvukové efekty vložené inline)
music/         song0.mp3 … song9.mp3 (hudba na pozadí, načítá se za běhu)
.nojekyll      vypíná zpracování Jekyllem na GitHub Pages
```

## Licence a zdroje
- Zvukové efekty: Kenney Casino Audio (CC0).
- Hudba v `music/`: vlastní skladby autora repozitáře.
- Hra je určena pouze k zábavě a tréninku, hraje se o virtuální žetony.
