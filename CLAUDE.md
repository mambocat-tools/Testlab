# Arbeitskontext für Testlab

<!-- server-mambocat-hinweis -->
## Server und übergreifendes Wissen

Diese Anwendung läuft auf dem MamboTools-Server. Alles, was **nicht nur
dieses Werkzeug** betrifft, steht in
[`mambocat-tools/server_mambocat`](https://github.com/mambocat-tools/server_mambocat)
— dort nachsehen, bevor du etwas am Server, an Authentik oder an der
Plenty-API änderst:

| Thema | wo |
|---|---|
| Serverzugang, Deployment, freie Ports | `README.md` |
| Authentik: neue App, **Policy-Binding**, Token-Laufzeit | `README.md`, „Prüfliste bei JEDER neuen App" |
| Backup, Datenbankabzüge, Wiederherstellung | `README.md`, „Backup" |
| Plenty-API: geprüftes Wissen und Eigenheiten | `plenty-api/VERIFIZIERT.md` |
| Sicherheitsrichtlinie, Zugriffsrechte der API-Konten | `SICHERHEIT.md` |

**Neue Erkenntnisse, die mehr als dieses Repo betreffen, gehören dorthin**
— nicht hierher. Sonst stehen sie bald an dreißig Stellen unterschiedlich.

<sub>Dieser Abschnitt wird von `tools/repo_hinweis.py` in
`server_mambocat` gepflegt. Änderungen hier werden beim nächsten Lauf
überschrieben.</sub>
<!-- /server-mambocat-hinweis -->
