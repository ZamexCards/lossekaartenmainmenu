ZAMEXCARDS POKEMON SERIES EN SETS
=================================

UPLOADEN NAAR GITHUB
1. Maak een nieuwe lege repository aan op GitHub.
2. Pak het ZIP-bestand uit.
3. Upload alle bestanden uit de map, dus niet de ZIP zelf.
4. Open bij de repository: Settings > Pages.
5. Kies bij Source: Deploy from a branch.
6. Kies main en /(root), en klik Save.
7. GitHub toont daarna het adres van de pagina.

IN JOUWWEB PLAATSEN
1. Open jouw JouwWeb-pagina voor losse Pokemon-kaarten.
2. Voeg een onderdeel Insluitcode/Embed code toe.
3. Open het bestand jouwweb-embed.html.
4. Vervang de voorbeeldlink bij src door jouw echte GitHub Pages-link.
5. Kopieer daarna de volledige iframe-code naar JouwWeb.

LINKS
De actieve verkooplinks naar ZamexCards zijn al ingevuld. Een set zonder
verkooplink toont automatisch 'Pagina volgt' en stuurt bezoekers nergens heen.

GOOGLE SHEETS (OPTIONEEL)
De pagina werkt direct zonder Google Sheet. Wanneer je later een Sheet wilt
gebruiken, publiceer je het juiste tabblad als CSV en plak je die CSV-link in
config.js achter sheetCsvUrl. De pagina gebruikt bij een fout automatisch de
ingebouwde gegevens, zodat het overzicht nooit leeg wordt.

SEO / GOOGLE
De GitHub-pagina bevat bewust een canonical-verwijzing naar de hoofdpagina op
ZamexCards.nl en staat op noindex. Hierdoor voorkom je dat bezoekers vanuit
Google op de losse GitHub-pagina uitkomen. Zet de SEO-titel, omschrijving, H1 en
introductietekst altijd op de JouwWeb-pagina zelf; iframe-tekst telt niet als
gewone inhoud van de JouwWeb-pagina.
