# Sveitarstjórnarkosningar 2026 — interaktivt kort

Niðurstöður íslensku sveitarstjórnarkosninganna 16. maí 2026, sýndar á gagnvirku korti eftir sveitarfélögum.

## Live

Þegar repo-ið er birt á GitHub Pages: `https://<username>.github.io/kosningar-2026/`

## Hvað er á korti?

- **62 sveitarfélög** lituð eftir niðurstöðum.
- **Sigurvegari**-hamur: hvert sveitarfélag fær lit stærsta listans.
- **Tilteknum flokki**-hamur: hvert sveitarfélag litað eftir kjörfylgi þess flokks.
- Hover yfir sveitarfélag → sjá nafn og sigurvegara.
- Smelltu á sveitarfélag → fá sundurliðun atkvæða með stikuriti.
- Hover yfir línu í stikuriti → fullt nafn flokksins/listans.

## Gögn

- **Atkvæðatölur:** [RÚV GraphQL API](https://gql.kosningar.ruv.is/graphql) (electionID = 394). Birt á [ruv.is/kosningar](https://www.ruv.is/kosningar).
- **Landfræðimörk:** [OpenStreetMap](https://www.openstreetmap.org/) – admin_level=6 í gegnum [Overpass API](https://overpass-api.de/), einfaldað með Douglas–Peucker (þolmörk ~300 m).
- **Síðast uppfært:** 17. maí 2026, ca. 03:53. Þetta er kyrrstöðumynd — gagnasettið er innfellt í HTML.

## Tæki

Hreint HTML + Leaflet 1.9.4 (sótt frá unpkg). Engin byggingarþrep.

## License

Niðurstöður og landfræðimörk eru opin gögn frá RÚV / OSM. Kortið sjálft er birt undir MIT.
