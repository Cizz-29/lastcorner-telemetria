# Telemetria di Lastcorner.net

File dei singoli giri della sezione [Telemetria](https://lastcorner.net/telemetria),
serviti da GitHub Pages: `https://cizz-29.github.io/lastcorner-telemetria/<anno>/<round>/<sessione>/tel/<numero>.json`.

Li scarica il browser quando si apre un confronto fra giri. Il sito li teneva in
`public/telemetria-data/**/tel/` del repository lastcorner-web: ogni deploy di
Vercel se li portava dietro (191 MB su 197), e lo spazio dei deploy arrivava
al limite del piano gratuito. Dal 4 novembre 2026 vivono qui.

Li pubblica in automatico lo script della telemetria sul PC di Francesco
(`scripts/telemetry/pubblica-giri.bat` nel repository del sito). Non
modificarli a mano.
