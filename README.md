# wawie-local-agent-releases
Public Windows installers and checksums for Wawie Local Agent. Distribution files only.

## Falcon 1
- `falcon1/falcon1-v3.1.1.tar.gz` (actuelle) : niche automobile + fichier maître documentaire (tirage, anti-gabarit, moteur son synthétisé, annexes), alignée sur le rendu Wawie (pas de grain, caméra des hf.custom). SHA-256 dans `falcon1/falcon1-v3.1.1.tar.gz.sha256`.
- `falcon1/falcon1-v3.1.tar.gz` : version précédente.
- `falcon1/falcon1-v3.tar.gz` : version précédente (niche automobile seule), conservée pour les instructions déjà en place.
```
mkdir -p ~/falcon1 && curl -fsSL https://raw.githubusercontent.com/geffred/wawie-local-agent-releases/main/falcon1/falcon1-v3.1.1.tar.gz | tar xz -C ~/falcon1
```
