# CurioFlow — vidéos prêtes à publier

Ce dépôt sert de **salle d'attente** aux vidéos de la chaîne YouTube CurioFlow (@curio-flow).
Chaque **Release** = **une vidéo** à publier (vidéo longue ou Short), avec tous ses fichiers.

## Pour Muse (outil de publication)

1. **Prends les Releases dans l'ordre** indiqué par leur fiche (« n° X sur Y » dans `publication.md`) :
   par numéro de vidéo croissant, la vidéo longue avant ses Shorts. **Une seule publication par jour**, vers 12 h (heure de Montréal) ;
   un Short se publie le lendemain de sa vidéo longue.
2. **Ouvre `publication.md`** dans la Release : il contient tout — les fichiers, le moment, chaque réglage de YouTube Studio
   (titre, description, miniature, playlist, audience, langue, catégorie, tags, sous-titres, écran de fin ou vidéo associée, visibilité)
   et ce qu'il faut faire après. Suis-le à la lettre, sans rien inventer ni modifier.
3. **Télécharge les fichiers** de la Release (vidéo `.mp4`, image `.png`, sous-titres `.srt` s'il y en a) et publie sur YouTube.
4. **Après la publication** : épingle le commentaire indiqué, vérifie que la vidéo est en ligne, puis **supprime la Release**.
   La suppression est le signal « publiée » : la vidéo ne sera plus jamais redéposée.

En cas de doute (fichier manquant, consigne incohérente), **ne publie pas** et signale-le.

## Fichiers d'une Release

| Fichier | Rôle |
|---|---|
| `*.mp4` | la vidéo à importer |
| `miniature.png` | miniature personnalisée d'une vidéo longue (1280×720) — toujours celle-ci, jamais celle de YouTube |
| `couverture-short-NN.png` | couverture d'un Short (déjà la première image de la vidéo) |
| `sous-titres.srt` | sous-titres français d'une vidéo longue |
| `publication.md` | les consignes complètes |
