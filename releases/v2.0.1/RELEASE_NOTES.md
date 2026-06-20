# Drox TUI v2.0.1

**Produit** : Drox TUI 2.0.1  
**Moteur** : dÃ©rivÃ© du moteur agent Drox IDE 1.5.0  
**Certification** : local-first â€” pas de tÃ©lÃ©mÃ©trie Drox, pas de cloud obligatoire.

## Artefacts Windows x64

| Fichier | Description |
|---|---|
| `drox-tui-2.0.1-windows-x64.zip` | Binaire + `install.ps1` |
| `SHA256SUMS-windows.txt` | Empreinte SHA256 |

## Installation Windows

```powershell
Expand-Archive drox-tui-2.0.1-windows-x64.zip -DestinationPath .\drox-tui
cd .\drox-tui
.\install.ps1
drox-tui --workspace C:\chemin\projet
```

## Linux x64

Construire sur Linux ou WSL :

```bash
./packaging/build-and-pack-linux.sh
./packaging/publish-or-linux.sh   # ou copier manuellement releases/v2.0.1/
```

Puis :

```bash
tar xzf drox-tui-2.0.1-linux-x64.tar.gz
cd drox-tui-2.0.1-linux-x64
./install.sh
```

Date de publication : 2026-06-20