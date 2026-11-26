# Support de Julien · atelier « IA souveraine et IA locale » (Tangente 2026)

Diaporama web (25 slides) de Julien MORICE pour ses passages dans l'atelier coanimé avec Baptiste GAULTIER (IMT Atlantique), jeudi 26/11/2026, 14 h - 16 h, à distance. Créé le 25/11/2026, sur le moteur de la présentation IRFASE (`EXED/FormationIRFASE/presentation/`). Le support commun reste le Keynote de Baptiste (`../Support_Baptiste/`) : ce diaporama ne couvre que les niveaux de Julien, avec des slides bleues « À toi, Baptiste » pour passer le partage d'écran.

Répartition suivie : CR du 24/11/2026 (`../2026-11-24_CR_Preparation_Atelier_IA_Souveraine_Locale.docx`) et demande de Julien du 25/11.

## Ouvrir

Double-cliquer sur `index.html` (ou le servir en local).

**En ligne depuis le 25/11/2026 (accord de Julien) :** https://practice-imtbs.github.io/presentation-tangente-ia-souveraine/ (dépôt public https://github.com/practice-imtbs/presentation-tangente-ia-souveraine, GitHub Pages sur `main`, racine ; le grand QR code de la dernière slide pointe vers cette adresse). Les vidéos ne partent pas sur GitHub (exclues par `.gitignore`) : en ligne, seules celles qui ont un permalien Médiaserveur se lisent ; les cinq vidéos à enregistrer n'y apparaîtront qu'une fois déposées sur le Médiaserveur et leur `permalien` renseigné. Attention : les notes de l'orateur sont dans le code de la page, donc lisibles en ligne.

Mise à jour : `git add -A && git commit -m "…"`, puis `gh auth switch -u practice-imtbs && git push && gh auth switch -u julienmorice`. GitHub Pages republie en une minute environ.

| Touche | Action |
|---|---|
| `→` `espace` / `←` | slide suivante / précédente |
| `S` (ou clic sur le numéro) | sommaire, avec les heures |
| `N` | notes de l'orateur, heure de fin visée, horloge |
| `F` | plein écran |
| `L` | vidéos en copie locale (mémorisé), et retour |

## Déroulé (horaires indicatifs, à recaler avec Baptiste)

| Slides | Séquence | Qui | Horaire |
|---|---|---|---|
| 1-2 | Titre, carte des quatre niveaux (facultative) | Julien | pendant l'ouverture de Baptiste |
| 3-8 | **Niveau 1 · Modèles frontière** : usages, harnais, une vidéo, une en réserve, la limite | Julien | 14 h 25 - 14 h 35 |
| 9 | Relais : PIAG, puis niveau 2 | Baptiste | 14 h 35 - 15 h 00 |
| 10-17 | **Niveau 3 · Logiciel chez moi, calcul à distance** : clés ILaaS et Albert, Kiro et son téléchargement, Open WebUI d'IMT-BS, RAGaRenn, Whisper, tableau comparatif | Julien | 15 h 00 - 15 h 15 |
| 18 | Relais : OpenCode et Mistral Vibe | Baptiste | 15 h 15 - 15 h 20 |
| 19-21 | **Niveau 4 · Tout local** : LM Studio, Kiro branché sur LM Studio | Julien | 15 h 20 - 15 h 25 |
| 22 | Relais : agent vocal local | Baptiste | 15 h 25 - 15 h 30 |
| 23-25 | Pratique (récupérer sa clé), trois idées, contact | ensemble | 15 h 30 - 16 h 00 |

Whisper (Transcripteur) est placé à la fin du niveau 3, comme demandé, mais présenté comme un « avant-goût du niveau 4 » : le calcul reste sur le poste.

## Liens courts

Créés le 26/11/2026 sur is.gd, affichés sur les slides 11 et 23 et à coller dans la discussion : https://is.gd/cleilaas (demande de clé ILaaS individuelle) et https://is.gd/clealbert (console des clés Albert API). Kiro : https://shorturl.at/rNscz (slide 13).

## Vidéos

La slide « Claude prépare, ChatGPT dessine » (vidéo `articuler`) a été retirée le 26/11/2026 à la demande de Julien ; la copie locale reste dans `assets/videos/`.

Toutes déclarées dans le bloc `window.VIDEOS` en tête de `index.html`.

| Clé | Slide | Vidéo | État |
|---|---|---|---|
| `contexte` | 6 | Context engineering avec Claude Code (2 min 48, v126d68cf57ef0dhuepk) | Prête, copie locale |
| `compterendu` | 7 (réserve) | Le compte rendu avec un harnais (3 min 51, v126d5d121f03i66a3ar) | Prête, copie locale. Montre un vrai CR interne avec des noms |
| `kiro` | 12 | Kiro avec une clé ILaaS ou Albert | **À enregistrer** : `assets/videos/Kiro_ILaaS.mp4` |
| `openwebui` | 14 | L'Open WebUI d'IMT-BS | **À enregistrer** : `assets/videos/Open_WebUI_IMTBS.mp4` |
| `transcripteur` | 16 | Transcripteur (Whisper) | **À enregistrer** : `assets/videos/Transcripteur_Whisper.mp4` |
| `lmstudio` | 20 | LM Studio | **À enregistrer** : `assets/videos/LM_Studio.mp4` |
| `kirolocal` | 21 | Kiro branché sur LM Studio | **À enregistrer** : `assets/videos/Kiro_LM_Studio.mp4` |

Pour une vidéo à enregistrer, il suffit de **déposer le fichier sous le nom indiqué** : la slide le lit aussitôt et affiche sa durée, sans toucher au code. Tant qu'il manque, la slide montre un cadre « Vidéo à enregistrer ». Après un dépôt sur le Médiaserveur, renseigner `permalien` dans le bloc pour avoir aussi le lecteur en ligne.

Les copies locales des trois vidéos prêtes viennent de `EXED/FormationIRFASE/presentation/assets/videos/`.

## À vérifier ou compléter avant jeudi

- [ ] Horaires de passage avec Baptiste (slides de relais et notes).
- [ ] Kiro : une vraie conversation avec la clé `kiro_Julien` ; accord de Renaud Dékode pour la v4.
- [x] Téléchargement de Kiro (slide 13, ajoutée le 26/11/2026) : archive sur FileSender (https://filesender.renater.fr/?s=download&token=eca63dca-9a9b-48d1-b18c-6b4cb0e65e8e, expire le 11/12/2026), lien court https://shorturl.at/rNscz, QR code `assets/img/qr_kiro.png` vers FileSender. Au-delà du 11/12, redéposer l'archive et refaire le QR code.
- [ ] Kiro + LM Studio : jamais essayé avec la version ILaaS. Dans LM Studio, démarrer le serveur local et cocher « Enable CORS » ; dans Kiro, Configuration › API et Modèles › LM Studio, `http://localhost:1234`, « Mettre à jour ».
- [ ] LM Studio : modèle montré (Gemma 4 12B est installé ; le CR parle de Gemma 4 4B sur un Mac de 8 Go).
- [ ] Open WebUI : qui l'héberge et l'administre, ce qui est conservé côté serveur.
- [ ] RAGaRenn : qui peut s'y connecter, quels modèles.
- [ ] Transcripteur : le retester.
- [ ] Pratique guidée : retenue ou non (slide 23), circuit des clés à caler avec Lucie JACQUET-MALO.

## Aperçu dans Claude Code

Serveur `presentation-tangente` de `.claude/launch.json` (port 8844). Il sert une copie du dossier placée dans l'espace temporaire de la session, le serveur n'ayant pas accès à `Documents` : recopier le dossier avant de le relancer depuis une autre session.
