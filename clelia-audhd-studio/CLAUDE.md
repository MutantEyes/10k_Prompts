# CLAUDE.md — CLELIA-AUDHD-STUDIO

> Contexte lu automatiquement par Claude Code à chaque session ouverte dans ce dossier.

## Le projet

**CLELIA-AUDHD-STUDIO** est un studio de création de vidéos par et pour les personnes AuDHD
(autistes + TDAH). La créatrice est infopreneure débutante et privilégie les outils open source
(Linux Mint).

- **Public :** adultes AuDHD, autistes ou TDAH, et leur entourage.
- **Ton :** bienveillant, clair, concret, sans infantiliser. Pas de jargon non expliqué.
- **Accessibilité des vidéos :** sous-titres systématiques, rythme posé, une idée par séquence,
  pas de flashs ni de sons agressifs, récapitulatif à la fin.
- **Langue :** français.

## Comment travailler avec moi

- Avancer **par petites étapes numérotées**. Une étape = une action.
- **Une seule question à la fois**, avec des choix proposés quand c'est possible.
- Toujours **rappeler où on en est** (étape actuelle / étapes restantes).
- Structurer les réponses : titres courts, listes, tableaux. Éviter les longs paragraphes.
- Proposer une **recommandation** plutôt qu'une liste exhaustive d'options.
- Ne jamais supprimer ou écraser un fichier sans demander.
- Être direct et honnête : dire clairement si quelque chose ne marche pas ou n'existe pas.

## Organisation des fichiers

Une vidéo = un dossier numéroté `videos/V001/`, `videos/V002/`, etc.

```
videos/V001/
├── 01-idee.md          # Sujet, public, objectif, message clé
├── 02-plan.md          # Structure : hook, chapitres, conclusion
├── 03-script.md        # Texte complet + indications (plans, lumière, B-roll)
├── 04-storyboard.md    # Description des images / prompts image et vidéo
├── 05-publication.md   # Titre, description, miniature, tags, sous-titres
└── STATUT.md           # Checklist d'avancement de la vidéo
```

## Protocole de création d'une vidéo

Suivre ces étapes dans l'ordre. Ne pas passer à la suivante sans validation.

1. **Explorer** : lire les fichiers existants du dossier de la vidéo. Ne rien écrire encore.
2. **Planifier** : proposer le plan (`02-plan.md`) et attendre mon accord.
3. **Écrire** : rédiger `03-script.md` section par section.
4. **Relire** : vérifier ton, durée, accessibilité, cohérence avec `01-idee.md`.
5. **Enregistrer** : mettre à jour `STATUT.md` puis faire un commit git clair
   (ex. `V001 : script v1 terminé`).

## Ressources

- Prompts sélectionnés pour l'écriture de scripts : `prompts-script-video.md`
  (à copier dans ce dossier). Prompts clés : *Cinematic Video Essay Director* (structure),
  *AI Video Creation Assistant* (script), *Storyboard Grid* (visuels).
