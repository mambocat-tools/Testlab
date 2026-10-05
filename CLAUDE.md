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
| **Oberfläche**: Farben, Schrift, Kopfleiste, Knöpfe — nichts selbst erfinden | [`mambotools-design`](https://github.com/mambocat-tools/mambotools-design), `DESIGN.md` |

**Neue Erkenntnisse, die mehr als dieses Repo betreffen, gehören dorthin**
— nicht hierher. Sonst stehen sie bald an dreißig Stellen unterschiedlich.

**Fertig melden.** Ist ein Vorhaben umgesetzt und ausgeliefert, am Ende
ausdrücklich sagen, dass es **fertig** ist – und es in
[`mambotools-projekte`](https://github.com/mambocat-tools/mambotools-projekte)
markieren: im Steckbrief `status: live` setzen (bei Fehlern/Änderungen heißt
das „behoben und ausgeliefert“), in der README die Zeile ins eingeklappte
**Archiv** verschieben. Dann verschwindet es aus der offenen Liste und steht
im Backlog-Tool unter dem Reiter „Archiv“. Gibt es noch keinen Steckbrief,
ist nichts zu markieren.

<sub>Dieser Abschnitt wird von `tools/repo_hinweis.py` in
`server_mambocat` gepflegt. Änderungen hier werden beim nächsten Lauf
überschrieben.</sub>
<!-- /server-mambocat-hinweis -->
