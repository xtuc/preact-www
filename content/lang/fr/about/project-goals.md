---
name: Project Goals
permalink: '/about/project-goals'
---

# Les objectifs de Preact

## Objectifs

Preact vise à accomplir quelques objectifs clés :

- **Performance:** Rendu rapide et efficace
- **Taille:** Taille réduite, légère _(approximativement 3.5kb)_
- **Efficacité:** Utilisation efficiente de la mémoire  _(renouvellement, éviter le GC thrash)_
- **Compréhensibilité:** Comprendre le codebase ne devrait prendre que quelques heures
- **Compatibilité:** Preact vise à être _largement compatible_ avec l'API de React. [preact-compat] tente de parvenir à autant de compatibilité avec React que possible.

## Non-Objectifs

Quelques fonctionnalités de React sont délibéremment omis de Preact, soit parce qu'elles ne sont pas réalisables tout en maintenant les objectifs primaires du projet ou qu'elles ne peuvent tenir dans le cadre de l'assemblage principal des fonctionnalités de Preact.

- Les éléments concernés de la rubrique [Qu'est ce qui manque?] :
    - PropTypes, qui sont facilement utilisables dans une librairie séparée
    - Children, puisque Preact emboîte toujours les children comme un Array
    - Synthetic Events, puisque Preact ne tente pas de réparer les erreurs dans les plus anciens navigateurs comme IE8

[preact-compat]: https://github.com/developit/preact-compat/
[Qu'est ce qui manque?]: /guide/differences-to-react#whats-missing
