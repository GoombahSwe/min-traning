# Min Träning v8 – testversion

En mobilanpassad PWA med mörk design. Publicera innehållet i den här mappen (inte själva ZIP-filen) i roten av ditt GitHub-repository. Gå till Settings → Pages → Deploy from a branch → main → /(root). Vänta på publicering och uppdatera sidan. På Android: Chrome → Installera app / Lägg till på startskärmen.

## Funktioner
- Träning: sökbar lista med vanliga gymmaskiner, fria vikter, kroppsvikt och konditionsaktiviteter. Favoriter, egna aktiviteter, direktredigering och en enda Lägg till-knapp.
- Styrka: individuella set, repetitioner och kg. Kondition: minuter, km, beräknat tempo/hastighet. Trappmaskin: minuter, steg, steg/minut.
- Dagens pass sparas automatiskt i lokal webbläsarlagring; Avsluta pass sparar i historik. Tidigare resultat visas vid val av övning.
- Sparade träningsprogram och veckoschema med dropdown per dag.
- Hem: översikt och viktlogg. Historik: tidigare pass och vikt. Profil: namn, mål, automatisk proteinuppskattning och JSON-export/import.

## Viktigt
All data sparas lokalt per webbläsare och enhet, utan konto eller server. Exportera en säkerhetskopia under Profil innan du byter telefon eller rensar webbplatsdata. v8 använder samma localStorage-nyckel `mintraning-v2` som v7 för att läsa befintliga profiluppgifter, vikter, pass och program. En ny version av appen kan uppdateras genom att ersätta filerna på GitHub.

Detta är en testversion. JavaScript-syntaxen är kontrollerad men fullständigt webbläsar- och mobiltest har inte kunnat genomföras.
