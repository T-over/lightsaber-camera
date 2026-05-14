# ⚔️ Lightsaber AR Camera

Caméra web progressive avec sabre laser en réalité augmentée. Une seule page HTML, aucune dépendance.

## Fonctionnalités

- **Sabre dynamique** — le sabre pivote pour pointer dans la direction du mouvement (souris ou doigt)
- **7 couleurs** — bleu, rouge, vert, violet, jaune, orange, blanc — chacune avec son propre glow
- **Longueur réglable** — slider pour ajuster la lame de 80 à 320 px
- **Son Web Audio** — bourdonnement, son d'allumage, whoosh lors des swings, claquement à la capture
- **Retournement caméra** — bascule caméra arrière / avant (selfie miroir)
- **Capture avec glow multi-passes** — le sabre est rendu avec 4 couches de glow dans la photo finale
- **Prévisualisation** — popup après capture avec téléchargement et partage natif (mobile)
- **Flash à la capture** — effet d'éclair blanc
- **HUD Star Wars** — coins de visée, réticule central, scanlines, vignette

## Raccourcis clavier

| Touche | Action |
|--------|--------|
| `Espace` | Capturer une photo |
| `F` | Retourner la caméra |
| `M` | Activer / couper le son |
| `1`–`7` | Changer la couleur du sabre |

## Utilisation

Ouvrir `index.html` dans un navigateur (Chrome, Safari, Firefox récent).  
Autoriser l'accès à la caméra → positionner le sabre avec la souris ou le doigt → capturer.

Fonctionne directement depuis le système de fichiers ou via n'importe quel serveur HTTP statique :

```bash
python3 -m http.server 8080
```

## Compatibilité

Tout navigateur moderne supportant `getUserMedia`, `Web Audio API` et `Canvas 2D`.
