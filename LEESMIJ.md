# Maison Ambrose · Amber — website

Deze map is de volledige website, klaar voor GitHub Pages.

```
maison-ambrose-site/
├── index.html      de pagina (3D-fles, ingrediënten, film, nieuwsbrief)
├── img/            7 AI-foto's
├── video/amber.mp4 de film (15 s, verkleind tot 12 MB)
└── .nojekyll       zorgt dat GitHub de map gewoon toont zoals ze is
```

## Online zetten met GitHub Pages (via de website, zonder terminal)

1. Ga naar github.com en log in.
2. Klik rechtsboven op **+** en dan **New repository**.
3. Geef een naam, bijvoorbeeld `maison-ambrose`. Zet hem op **Public**. Klik **Create repository**.
4. Klik op de link **uploading an existing file**.
5. Sleep de **inhoud** van deze map (index.html, de mappen img en video) in het venster.
   Sleep niet de map zelf, anders staat index.html een niveau te diep.
   Het bestand `.nojekyll` is verborgen in Finder; druk op Cmd + Shift + . om het te zien en sleep het mee.
6. Klik **Commit changes**.
7. Ga naar **Settings** → **Pages**. Kies bij *Branch* `main` en map `/ (root)`. Klik **Save**.
8. Na 1 à 2 minuten staat je site op `https://<jouw-gebruikersnaam>.github.io/maison-ambrose/`.

## Na het online zetten testen

- Schrijf je in via het formulier onderaan. Je moet in MailerLite een nieuwe inschrijver zien
  in het formulier "Maison Ambrose – Nieuwsbrief".
- Kijk of de film start als je naar "Van druppel tot fles" scrolt.
- Open de site ook eens op je gsm.

## Lokaal bekijken

```
python3 -m http.server 5173 --directory maison-ambrose-site
```

Open daarna http://localhost:5173 in je browser. Dubbelklikken op index.html werkt niet goed,
omdat de 3D-fles en de film dan door de browser geblokkeerd kunnen worden.
