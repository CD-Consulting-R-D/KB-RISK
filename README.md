# KB-RISK

Chapitre **KB-RISK** — Risk knowledge base — de la Knowledge Base **CD Consulting R&D**
(organisation GitHub [CD-Consulting-R-D](https://github.com/CD-Consulting-R-D)).

**Statut : créé le 08/09/2026 ; deux entrées migrées depuis le dossier `KB-RISK/` du dépôt racine le même jour (BKL-CDC-003, BKL-CDC-004) : `4f2a.html` (analyse WEF 2020-2026) + `9c1e.html` (synthèse), `7b3d.html` (note de lecture Mitchell, Ghosh, Passi) ; troisième entrée publiée le 08/09/2026 : `e6a4.html` (revue « Keeping secrets and code on GitHub », gabarit mixte clair/sombre) ; entrée 4 : `a9d2.html` (Twenty-one risks of working with AI agents: a field register, and the case of the pre-filled prompt) ; entrée 4 : `f3c7.html` (Vingt et un risques de la collaboration avec des agents IA : un registre de terrain, et le cas du prompt pré-rempli).** Chapitre : risque (technologie, information, IA).

## Rôle

- Un dépôt par chapitre de la base de connaissance ; la page d'accueil du domaine
  [www.cd-consulting-rd.be](https://www.cd-consulting-rd.be) vit dans le dépôt racine
  `cd-consulting-r-d.github.io` et pointe vers les chapitres.
- Une fois GitHub Pages activé sur ce dépôt (branche `master`, racine), son contenu sera
  servi sous `https://www.cd-consulting-rd.be/KB-RISK/` (site de projet sous le domaine de
  l'organisation).
- Contenu attendu : `index.html` (liste des entrées) et une page par entrée, nommée par
  quatre caractères hexadécimaux (`4f2a.html`), autoportante (CSS embarqué, aucune
  ressource externe), sources publiques citées.

## Notes de tenue

- Branche servie : **`master`**, seule branche. Publier, c'est pousser sur `master` —
  tout commit poussé est une mise en ligne, donc un gate explicite du propriétaire.
- Encodage UTF-8 **sans BOM**, fins de ligne **LF** (`.gitattributes`).
- Aucun secret, aucune fonction serveur, aucune collecte de données (`.gitignore`).
- Publication par soustraction : rien de la préparation interne ne passe en ligne.
