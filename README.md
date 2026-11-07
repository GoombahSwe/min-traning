# Min Träning v9 – version

En statisk, offline-kapabel träningsdagbok för GitHub Pages.

## Publicera på GitHub Pages
1. Packa upp ZIP-filen.
2. Ladda upp **alla filer direkt till roten** av ditt GitHub-repository `min-traning` (inte mappen runt filerna).
3. Ersätt de gamla filerna `index.html`, `app.js`, `sw.js` och `manifest.webmanifest` och behåll ikonerna.
4. Vänta tills GitHub Pages har publicerat. Öppna `https://goombahswe.github.io/min-traning/`.
5. Om gamla versionen visas: prova inkognitofönster, eller stäng och öppna den installerade appen. **Rensa inte webbplatsdata**, då lokala träningsuppgifter kan försvinna.

## Nytt i v9
- Grafitsvart tema med diskret blå accent.
- Välkomstsida med namn, startvikt, målvikt och mål.
- Träning med fri textinmatning, automatiska förslag på egna/tidigare övningar, återanvändning av senaste set/reps/vikt och favoriter.
- Separat Kost-flik med måltider, kalorier, protein, datum och redigering.
- Profil med uppskattat kalorimål enligt Mifflin–St Jeor, valfri manuell justering och proteinmål.
- Viktgraf med datum, historik och JSON-säkerhetskopia.
- Ingen Schema-flik.

## Lagring
Sparar lokalt i webbläsarens localStorage. Befintlig data från tidigare versioner läses från `mintraning-v2`, pågående pass från `mintraning-v8-draft`. Ta en säkerhetskopia via Profil före uppdatering.

Kaloriberäkningen är endast en uppskattning. Den är inte medicinsk rådgivning. Ingen matdatabas eller automatisk näringsvärdesberäkning ingår.
