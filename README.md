### Je conçois des outils, des IA écrivent le code, je les éprouve jusqu'à ce qu'ils tiennent.

Je ne suis pas développeur de métier. Je pars d'un besoin concret, je découpe le problème, je fais écrire le code par
des IA (Claude Code, Codex, modèles locaux avec Ollama), puis je teste et je corrige jusqu'à ce que ça marche pour de vrai.

*I design tools, AI writes the code, and I test them until they hold up.*

#### À la une : un « cerveau » persistant pour agent IA

Depuis le printemps 2026, je fais tourner chaque jour un système qui donne de la mémoire et de la méthode à un agent
IA : un graphe de connaissances rebâti chaque nuit (2 571 nœuds), des tâches automatiques qui proposent sans jamais
imposer, des compétences versionnées, et un contrôle du contenu réellement produit. Trois architectures successives,
des chiffres mesurés, et les échecs racontés franchement :
**[lire l'étude de terrain](https://github.com/nicobatberger-design/synapse/blob/main/docs/etude-cerveau.md)**.

#### Projets publics

| Projet | Ce que c'est |
|---|---|
| **[synapse](https://github.com/nicobatberger-design/synapse)** | Le moteur de mémoire de ce « cerveau » : un graphe de connaissances typé qui relie les règles, les procédures et les mémoires d'un agent IA, pour qu'il commence chaque tâche avec le bon contexte. Python, sans aucune dépendance. |
| **[modular-quantum-trainability](https://github.com/nicobatberger-design/modular-quantum-trainability)** | Recherche indépendante et reproductible sur les circuits quantiques modulaires : une loi de profondeur *g\*(L) ≈ 1,2/√L*, une prédiction annoncée avant le calcul puis confirmée, et les résultats négatifs publiés aussi. |
| **[opr-app](https://github.com/nicobatberger-design/opr-app)** | Application hors ligne pour relever les réserves de chantier sur le plan et éditer le procès-verbal d'OPR. [Essayer](https://nicobatberger-design.github.io/opr-app/). |

#### Contribution : un bug de Claude Code trouvé à la source

Certains matins, les connecteurs de Claude (Gmail, Drive, Notion…) manquaient pendant toute la session. Avec Claude, j'ai
suivi la piste dans les journaux de l'extension VS Code, puis dans le code de Claude Code lui-même : au premier lancement
du jour, la liste des connecteurs reçoit une erreur 401 pendant le renouvellement du jeton, et cette erreur n'est jamais
retentée. Le Wi-Fi et Google étaient hors de cause.
**[Signalement #101117 sur le dépôt d'Anthropic](https://github.com/anthropics/claude-code/issues/101117)**, avec la
méthode pour le reproduire : un autre développeur a confirmé l'analyse, et d'autres signalements y renvoient.

#### Ce que je construis aussi (non publié)

- **Des outils pour le bâtiment** : métré sur plans PDF, pièces écrites tirées d'un devis et d'un plan.

#### Ma façon de travailler

1. **Juger la cible avant d'écrire une ligne** : qui s'en servira, et pour quoi faire.
2. **Tester sur du réel**, pas seulement sur des exemples fabriqués pour l'occasion.
3. **Faire relire par un second modèle**, et corriger ce qu'il trouve.
4. **Dire ce qui est vérifié**, et présenter le reste comme une hypothèse.

#### Outils

Claude Code · Codex · Ollama · Python · JavaScript · PowerShell · Git
