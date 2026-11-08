# Min Träning 0.9.5

Nyheter:
- Träningshistorik: varje set visas på en egen tydlig rad med vikt och reps. Konditionspass visar tid, distans och tempo på separata rader.
- En ny styrkeövning börjar med **ett set**. Tidigare övnings första set används som förslag. Lägg till fler set vid behov.
- Fungerande redigeringsvy i historik även när du lägger till/tar bort set i ett avslutat pass.
- Installationsförslag för telefon återställt (saknades av misstag i en tidigare version).
- Ny version 0.9.5 och uppdaterad offlinecache.

## Publicering på GitHub Pages
1. Exportera gärna säkerhetskopia under Profil före uppdatering.
2. Packa upp ZIP-filen. Ladda upp **innehållet** direkt till roten av repot `goombahswe/min-traning` (inte ZIP-filen och inte en extra mapp).
3. Ersätt gamla filer, inklusive `index.html`, `app.js`, `sw.js`, `version.json`, och klicka Commit changes.
4. Kolla att `index.html` på GitHub har rubriken **V0.9.5**.
5. Öppna i Chrome eller ett inkognitofönster för att kontrollera publiceringen. Rensa **inte** webbplatsdata; dina pass, vikt och måltider sparas lokalt.

## Besöksstatistik
GitHub Pages ger ingen detaljerad appstatistik i sig. Statistik kräver en separat tjänst, till exempel GoatCounter (https://www.goatcounter.com/) eller Cloudflare Web Analytics (https://developers.cloudflare.com/web-analytics/get-started/). Skapa först ett konto och följ leverantörens guide för att infoga deras spårningskod i `index.html`. Ingen spårning är aktiverad i detta paket och inga tränings- eller hälsouppgifter ska skickas i statistik.

## Teststatus
JavaScript-syntax, ZIP-paket och grundläggande funktioner valideras vid byggnation. Androidinstallation och tredjepartsstatistik kräver separat test/inställning.
