# CLAUDE.md

Guide à l'usage des assistants IA (Claude Code) travaillant sur ce dépôt.
Ce n'est **pas un projet logiciel** : il n'y a ni code, ni build, ni
dépendances, ni tests. C'est un **projet d'écriture** en français. Le livrable
est un texte.

## Le projet en une phrase

Conceptualiser et rédiger un **livret de 80–100 pages** présentant les
parallèles entre le **Wu Xing** (les 5 éléments chinois) et les **5
Fondamentaux** de Duy Dang : **Vérité, Amour, Paix, Beauté, Vie**.

- Public : grand public en quête d'évolution personnelle, de déclics concrets.
- Périmètre : **100 % vie/relations, ZÉRO sexualité** dans ce livret.
- Correspondances : Vérité = Eau · Amour = Feu · Paix = Terre · Beauté = Métal ·
  Vie = Bois.

## Document de référence principal

➡️ **`INSTRUCTIONS_CLAUDE_PROJECT.md` est la source de vérité.** Le lire en
entier avant toute tâche de rédaction. Il définit la voix, la structure du
livre, la terminologie, les concepts clés par Fondamental, et le « processus »
d'amélioration. Ce `CLAUDE.md` ne fait que résumer et pointer vers lui — en cas
de doute, c'est `INSTRUCTIONS_CLAUDE_PROJECT.md` qui fait foi.

## Fichiers du dépôt

| Fichier | Rôle |
| --- | --- |
| `INSTRUCTIONS_CLAUDE_PROJECT.md` | **À lire en premier.** Voix, structure, terminologie, concepts, processus. |
| `Section_Verite_Eau_Validee.md` | **Section modèle validée.** Référence de structure/ton pour rédiger les autres Fondamentaux. |
| `12_Posts_Style_Duy.md` | 12 posts représentatifs du style réel de l'auteur (exemples de voix). |
| `RAPPORT D ANALYSE STYLISTIQUE.md` | Analyse détaillée des caractéristiques stylistiques de Duy. |
| `Discussion wuxing.txt` | Notes de travail : cycles et analogies Wu Xing ↔ 5 Fondamentaux. |
| `LIVRET_5_FORCES_VIVANTES_V2.pdf` | Version antérieure du livret (référence). |
| `Principes Sexualité Sensible.docx.md` | Corpus volumineux — voir la règle ci-dessous. |
| `README.md` | Description en une ligne du projet. |

## Règles importantes (extraites des instructions)

1. **Ne JAMAIS lire en entier `Principes Sexualité Sensible.docx.md`** (~800 Ko)
   : les concepts utiles sont déjà condensés dans
   `INSTRUCTIONS_CLAUDE_PROJECT.md`. Pour un concept précis absent, **demander à
   l'auteur** plutôt que d'ouvrir tout le fichier.
2. **Terminologie stricte** : « 5 Fondamentaux » (jamais « Forces » / « Forces
   Vivantes ») ; « canalise » (jamais « contrôle »). Respecter les
   correspondances élément ↔ Fondamental ci-dessus.
3. La **section Vérité (Eau) est validée** et sert de **modèle** : aligner les
   autres sections sur sa structure et son ton.
4. Les histoires peuvent être **inventées** mais doivent être annoncées
   honnêtement (« Imaginons une personne… »).
5. **Itérer un point à la fois** : une amélioration ciblée à la fois est plus
   efficace que plusieurs d'affilée.

## Voix d'écriture (résumé)

Tonalité : ~40 % vulnérabilité intime, 30 % sagesse calme, 20 % humour léger,
10 % provocation douce. Chaque section : accroche chaleureuse → histoire ou
métaphore du quotidien → retournement → enseignement incarné → fin ouverte.

À faire : commencer par une histoire/anecdote (jamais par un concept) ; parler
en « je » ; images du quotidien ; parallèles inattendus.
À éviter : listes à puces dans le contenu, ton moralisateur, jargon académique,
expliquer juste après une phrase qui frappe.

## Le « processus » (sur demande explicite de l'auteur)

Quand l'auteur dit **« processus »**, appliquer dans l'ordre, sur le texte
visé : (1) analyse **Joe Vitale** (copywriting), (2) analyse **Simon Sinek**
(le WHY), (3) analyse **Duy Dang** (son style) — chacune en points
forts / points faibles / conseils — puis (4) **correction** du texte en
conservant les points forts et en appliquant les conseils. Détails complets
dans `INSTRUCTIONS_CLAUDE_PROJECT.md`.

## Flux de travail

- Le travail consiste à **éditer des fichiers Markdown** (et à en créer de
  nouveaux pour les sections en cours de rédaction). Aucune commande à exécuter.
- Committer avec des messages clairs en **français**.
- Branche de travail dédiée : **`claude/claude-md-docs-f1g2s5`**. Ne pas pousser
  sur `main` sans autorisation explicite.
