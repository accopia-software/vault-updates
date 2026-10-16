# VAULT Updates

Offizieller Updatekanal von Accopia Software für freigegebene VAULT-Versionen unter Windows.

## Downloads

Freigegebene Installer werden unter [Releases](https://github.com/accopia-software/vault-updates/releases) bereitgestellt. **Derzeit ist noch keine Version veröffentlicht.**

VAULT befindet sich in der Entwicklungs- und Abnahmephase. Die Einrichtung dieses Kanals ist keine Release-Freigabe.

## Automatische Updates

Eine dafür eingerichtete VAULT-Version prüft vor der Anmeldung auf neuere Versionen und verifiziert die Update-Signatur vor der Installation. Der Einstieg aus älteren Versionen erfordert einmalig die manuelle Installation einer Version mit Update-Unterstützung.

Der Update-Endpunkt wird mit der ersten freigegebenen Version verfügbar:
`https://github.com/accopia-software/vault-updates/releases/latest/download/latest.json`

Ein Updatepaket enthält den Windows-Installer, seine `.sig`-Datei und das zugehörige `latest.json`. Update-Signaturen sind unabhängig von Windows-Authenticode-Signaturen.
