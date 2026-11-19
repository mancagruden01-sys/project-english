# Project English — Train · Learn · Remember

Samostojna, odzivna spletna aplikacija za dnevno učenje poslovne angleščine: gradbeništvo, elektrotehnika ter projektno vodenje in investicije.

## Objava na GitHub Pages (brezplačno)

1. Na https://github.com/new ustvari repozitorij **project-english**. Izberi **Public** (za standardno brezplačno objavo prek GitHub Pages).
2. Odpri repozitorij in izberi **Add file → Upload files**. Naloži **vseh šest datotek** iz te mape (`index.html`, `app.js`, `bank.js`, `fox.svg`, `manifest.webmanifest`, `sw.js`). Datoteke naj bodo v **korenu** repozitorija, ne v podmapi. `README.md` je neobvezen.
3. Klikni **Commit changes**.
4. Odpri **Settings → Pages → Build and deployment**. Pri **Source** izberi **Deploy from a branch**, izberi vejo **main** in mapo **/(root)**, nato **Save**.
5. Ko se stran objavi, jo odpri na `https://TVOJE-UPORABNISKO-IME.github.io/project-english/` (ime repozitorija in uporabniško ime prilagodi dejanskima).
6. Povezavo pošlji možu. Na telefonu lahko v meniju brskalnika izbere **Add to Home Screen** / **Dodaj na začetni zaslon**, če brskalnik to omogoča.

## Pomembno

- Hosting GitHub Pages je lahko brezplačen; zasebna sinhronizacija podatkov ni vključena.
- Napredek je v `localStorage` vsakega brskalnika. Ni prijave ali sinhronizacije; v zasebnem načinu/po brisanju podatkov se lahko izgubi.
- Dnevni izziv je determinističen glede na lokalni datum naprave; 8 vprašanj besedišča, 2 prevoda, 2 sestavljanji stavkov.
- Prevajanje stavkov se preverja z **eno referenčno rešitvijo**, z normalizacijo velikosti črk, ločil in presledkov. Zato so lahko drugačni slovnično pravilni prevodi označeni kot napačni. V1 nima AI ocenjevalnika.
- `Remember` vsebuje napačno odgovorjene besede iz kviza. Izraz lahko označi kot naučen.
- Govorna funkcija je **poslušanje izgovorjave**, ne ocenjevanje uporabnikovega govora; kakovost in razpoložljivost glasov sta odvisni od naprave.
- Service worker omogoča shranjevanje osnovnih datotek po prvem spletnem obisku (običajni pogoji podpore brskalnika).

## Spreminjanje nalog

V datoteki `bank.js` lahko dodaš / urediš besede, prevode in stavke. Pri posodobitvi objave bo GitHub Pages spletno aplikacijo znova objavil.
