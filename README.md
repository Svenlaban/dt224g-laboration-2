# Laboration 2 – Versionshantering och publicering
## Beskrivning
En webbplats vars syfte är att lära sig Git funktioner.
## Tekniker
HTML
## Publicerade versioner
- [GitHub Pages](https://svenlaban.github.io/dt224g-laboration-2/index.html)
- [Personlig VPS](https://lab2.larverktyg-snh.se)
## Frågor om Git
1. Vad är skillnaden mellan git add och git commit?
- add väljer vad som ska sparas och commit sparar det man valt.
2. Varför använder man branches istället för att jobba direkt i main?
- För att kunna göra ändringar och förbättringar samtidigt som man har en fungerade huvudversionr. Annars skulle projektet vara trasigt om man sprar saker löpandes medans man jobbar på något.
3. Vad händer rent praktiskt när man gör en merge?
- Den tar de ändringar som gjorts en grenen och för över dem till huvudprojektet(alterantivt att man mergar till en annan branch).
4. Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
- När man pushar till GitHub så får man med commmits och versionshistorik till repot. När man Laddar upp manuellt till en server som i mitt fall så följer ingen info med om hur sidan sett ut tidigare eller vilka ändringar som gjorts.
5. Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
- Man skapar filen .gitignore i rotmappen och lägger in vilka filer som Git ska ignorera. Ett exempel kan vara *.log för att den inte ska skicka med eventuella logfiler. Ett annat exempel kan vara filer som innehåller inloggningsinformation.