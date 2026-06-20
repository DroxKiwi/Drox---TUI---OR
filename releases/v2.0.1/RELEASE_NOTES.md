# Drox TUI v2.0.1

**Produit** : Drox TUI 2.0.1  
**Moteur** : dÃ©rivÃ© du moteur agent Drox IDE 1.5.0  
**Certification** : local-first â€” pas de tÃ©lÃ©mÃ©trie Drox, pas de cloud obligatoire.

## Artefacts Windows x64

| Fichier | Description |
|---|---|
| `drox-tui-2.0.1-windows-x64-setup.exe` | Installateur Windows (assistant graphique) |
| `SHA256SUMS-windows.txt` | Empreinte SHA256 |

## Installation Windows

1. Telechargez `drox-tui-2.0.1-windows-x64-setup.exe`
2. Lancez l'installateur (double-clic)
3. Cochez Â« Ajouter au PATH Â» si propose
4. Ouvrez un **nouveau** terminal :

```powershell
drox-tui --workspace C:\chemin\projet
```

## Linux x64

| Fichier | Description |
|---|---|
| `drox-tui-2.0.1-linux-x64.tar.gz` | Binaire + `install.sh` |
| `SHA256SUMS-linux.txt` | Empreinte SHA256 (si publie) |

```bash
tar xzf drox-tui-2.0.1-linux-x64.tar.gz
cd drox-tui-2.0.1-linux-x64
./install.sh
drox-tui --workspace ~/projets/mon-repo
```

Date de publication : 2026-06-20