# Brief commun — maquettes de pistes visuelles Universitek

Maquettes **jetables** pour choisir une direction artistique. Chaque piste = un seul fichier `index.html` autonome (CSS et JS inline), servi par `http://localhost:8642/<dossier-piste>/`.

## Le projet en bref

Universitek (Montpellier) : collectif de soirées électroniques underground **et** organisme de formation certifié Qualiopi (masterclass musique, stages, ateliers ; branche cinéma CINEMATEK).
DA imposée : **violet obligatoire** — brut / graphique / contemporain / indépendant / nocturne / culturel / un peu punk.
Référence aimée : golimar.fr (fond quasi noir, un seul accent électrique rare, titres énormes très élargis en capitales, infos en mono capitales espacées, sections numérotées « 01 // », listes en lignes plutôt qu'en cartes avec aplat de couleur qui monte au survol, bandeaux défilants, grain + scanlines légers). **S'en inspirer, ne pas la copier** (pas de globe, pas de métaphore .EXE, pas de loader bloquant).
Idée retenue par le client : **des bulles pétillantes qui remontent à la surface, comme dans un verre** — c'est l'objet visuel signature du site.
Matériau existant : l'affiche de la soirée du 16/10 = papier blanc froissé, grotesque condensée noire en capitales, smiley violet tracé à la bombe avec coulures (≈ #6838B8). **Le smiley est le visuel de CETTE soirée uniquement, ce n'est PAS le logo ni un élément de la marque Universitek** : il ne peut apparaître que dans le bloc de l'événement du 16/10 (comme son affiche). Le logo Universitek = « UNIVERSITEK » en blanc avec un « U » ouvert (logo texte en attendant le fichier). Dossier de présentation = violet vif en aplats, bleu nuit, accents cyan ; ton inclusif (point médian), éducation populaire, « transmission & célébrations ».

## Structure de la page (one-page, dans cet ordre)

1. **En-tête** : logo texte UNIVERSITEK ; nav : Agenda · Masterclass · À propos · Artistes · Archives · Cinematek ; bouton « Billetterie ». **Menu mobile obligatoire** (bouton accessible, aria-expanded).
2. **Hero = prochain événement** + effet bulles.
3. **01 Agenda** (à venir) — un seul événement pour l'instant ; prévoir le gabarit en ligne (date / titre / lieu / prix / bouton).
4. **02 Masterclass** (YouTube) — 4 vidéos en façade : vignette stylisée (pas d'image Google chargée), au clic seulement remplacer par `<iframe src="https://www.youtube-nocookie.com/embed/ID?autoplay=1">` + mention « Lire la vidéo charge YouTube (Google) ». Lien « Toutes les masterclass sur YouTube ».
5. **03 À propos** — les deux piliers + chiffres clés.
6. **04 Artistes associé·e·s** — avec lien SoundCloud (href="#" pour l'instant).
7. **05 Archives** — événements passés.
8. **Focus CINEMATEK** — petit encart, clairement secondaire, qui renvoie vers cinematek.fr. Touche de vert néon #39FF14 (couleur de Cinematek) autorisée **uniquement** ici.
9. **Pied de page** — contacts, réseaux, adhésion, bouton **« Informations liées à l'organisme de formation »**, bloc Qualiopi (placeholder), mentions légales.

## Contenu (maquette — reformulé, à remplacer plus tard)

**Prochain événement**
- Titre : ENCORE ET ENCOR · LE CHÂTEAU COSCO · LIMINAAL (« Encor » est voulu)
- Accroche : Live machines modulaire · Techno DIY · Cold techno
- Vendredi 16 octobre 2026, 21h — Le Salon des Indépendants, 4 rue Lunaret, Montpellier
- Tarif unique 10 € (prix bas pour rémunérer correctement les artistes et soutenir la scène indépendante)
- Line-up : **Encore et Encor** — live machines sans timecode, techno 130-145 BPM, hypnotique et rave ; **Le Château Cosco** — trio noise rock / techno DIY, transe répétitive et cérémonielle ; **Liminaal** — cold techno, slow rave, acid, textures cold wave (mixe avec le collectif depuis 2024)
- Billetterie : https://www.helloasso.com/associations/universitek/evenements/encore-et-encor-le-chateau-cosco-liminaal

**Masterclass** (ID YouTube — titre — intervenant·e — date — durée — niveau)
- `-XEUyl_Y-5s` — Dark progressive : patches, tips & tricks — OddWave (Hadra Records) — 08.08.2020 — 1h59 — confirmé·e·s — Ableton, Serum
- `6QuNr6Te8jA` — Liveset & improvisation (EN) — 69DB (Spiral Tribe / SP23) — 19.09.2020 — 1h17 — débutant·e·s — Ableton, NI
- `CTBWyPEV634` — Concert évolutif (BPM) & mix harmonique — Dj Bigmat — 07.02.2021 — 1h58 — tous niveaux — DJing, scratch
- `XOTpP8gJnbM` — Initiation DJing sur CDJ & DJM — Bernadette (Move Ur Gambettes) — 13.12.2023 — 1h24 — débutant·e·s
- Chaîne : https://www.youtube.com/@UNIVERSITEK

**À propos** — Universitek fait de la musique électronique un terrain d'apprentissage, de création et de partage. Deux piliers : **Formation** (masterclass en ligne en direct ou en replay, sessions en présentiel, stages intensifs) et **Production** (soirées club, concerts, formats en espace public, festival) pour faire briller la scène locale et underground. Pédagogie inspirée de l'éducation populaire, exigence professionnelle.
Chiffres : ~20 intervenant·e·s · 70 h+ de formation · ~20 événements · 12 lieux · 1 festival à Victoire 2 · cours en FR & EN.

**Artistes associé·e·s** — Meremix (groovy techno · dark acid disco) · Wildtrack (psytrance · forest) · Zöta (techno · acid house) · Cosmic Bazaar (groovy techno · psytechno) · Liminaal (cold techno · slow rave) · Hurluberlu (VJing · mapping).

**Archives** (date — titre — lieu)
- 31.10.2025 — Panacée Horror Show — Café de la Panacée
- 26.09.2025 — Concert pour la paix — Parc Clemenceau
- 29-30.08.2025 — Ateliers scratch — Hadra Trance Festival
- 22.08.2025 — Boiler Groove #4 — Tropisme
- 13.07.2025 — Universitek × Solaation — MOBA
- 12.07.2025 — Boiler Groove #3 — Panorama, Corum
- 21.06.2025 — Fête de la musique — Bistrot Gilles
- 31.05.2025 — Universitek Festival #1 — Victoire 2 (16h-4h, 2 scènes, 18 artistes)
- 07.05.2025 — Blastfest — Université Paul-Valéry
- 02.05.2025 — Elements of Baraka — Le Salon des Indépendants
- 04.04.2025 — Boiler Groove #2 — MO.CO. Faune
- 21.02.2025 — Boiler Groove #1 — MO.CO. Faune
- 07.12.2024 — Universitek invite Puzzle Puzzle — Mélomane Club

**Focus CINEMATEK** (texte du client, à garder tel quel) — « Créée en 2025, CINEMATEK est la branche d'Universitek dédiée aux métiers du cinéma et de l'audiovisuel. Dans la continuité du projet de transmission développé par Universitek depuis 2017 elle propose des formations professionnalisantes dans le registre du cinéma. » → « + d'infos sur cinematek.fr » (https://www.cinematek.fr/)

**Pied de page** — contact@universitek.com · Instagram https://www.instagram.com/universitek_/ · YouTube · Adhérer (10 €/an) https://www.helloasso.com/associations/universitek/adhesions/j-adhere-a-universitek · bouton « Informations liées à l'organisme de formation » → https://drive.google.com/drive/folders/1zArshubiv1V8xgagEm6ryqpQ_6pF1rAo · bloc placeholder « [logo Qualiopi] La certification qualité a été délivrée au titre de la catégorie d'action suivante : actions de formation » (encadré en pointillés, **ne pas dessiner un faux logo Qualiopi**) · Mentions légales · Confidentialité (href="#").

## Contraintes techniques (toutes les pistes)

- Un seul `index.html`, HTML/CSS/JS vanilla inline ; seule dépendance externe autorisée : Google Fonts (preconnect + `display=swap`). Pas d'image externe : visuels générés (CSS, SVG inline, canvas). Viser < 80 Ko.
- `lang="fr"`, HTML sémantique (header/nav/main/section/footer, h1 unique), lien d'évitement, `:focus-visible` bien visible, contrastes AA (≥ 4.5:1 pour le texte courant), cibles tactiles ≥ 44 px, pas de texte < 12 px.
- **Bulles** : canvas, nombre adapté à la surface, `devicePixelRatio` plafonné à 2, pause hors écran (IntersectionObserver) et onglet caché (`visibilitychange`). Réalisme « verre pétillant » : bulles émises en colonnes depuis des points de nucléation au fond, elles grossissent légèrement et accélèrent en montant, oscillent un peu, et éclatent à la surface. `prefers-reduced-motion: reduce` → une image fixe (une frame) et aucun défilement automatique.
- Aucun loader bloquant. Pas de curseur natif masqué.
- Mobile 375 px impeccable : pas de débordement horizontal, menu mobile, agenda en premier.
- Liens externes : `target="_blank" rel="noopener"`.
- Petit badge discret fixe en bas à gauche : « PISTE X · maquette » (pour comparer les pistes).
