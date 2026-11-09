# Kur gyventi Kaune

Kelionės laikas automobiliu ir viešuoju transportu pagal paros metą, laiko zonos, darželiai ir mokyklos (valstybiniai ir privatūs), dviračių takai, miškai, KVT linijos ir tavo įkelti skelbimai Kaune ir Kauno rajone.

Failai:
- `index.html` programa
- `kaunas.json` žemėlapio ir maršrutų duomenys
- `config.js` tarpinio serverio adresas skelbimų nuorodoms (žr. žemiau)
- `sw.js`, `manifest.webmanifest`, ikonos: kad veiktų kaip programėlė ir be interneto

Skelbimai pagal įklijuotą nuorodą veikia tik tada, kai `config.js` faile įrašytas Cloudflare Worker adresas (kodas aplanke `cloudflare-proxy`).

Duomenys: © OpenStreetMap bendraautoriai (ODbL), KVT GTFS, Švietimo, mokslo ir sporto institucijų registras (AIKOS). Žemėlapis: MapLibre GL.
