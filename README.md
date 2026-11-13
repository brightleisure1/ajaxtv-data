# Ajax TV-gegevens

Leverancier van `data.json` voor de Ajax TV-app op een Samsung-tv uit 2012.
Die tv kan geen moderne HTTPS-verbinding maken, dus de gegevens worden via
GitHub Pages op `http://tv.stuby.nl/data.json` aangeboden (HTTPS niet afgedwongen).

Een GitHub Action haalt elk kwartier de gegevens op bij `https://ajaxtv-data.vercel.app/api/data`.
