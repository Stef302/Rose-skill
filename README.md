# Skill Rose

Skill pour écrire, corriger et faire tourner des programmes dans le langage
**Rose** (langage compilé en français).

## Contenu

```
rose-dev/
  SKILL.md              le skill principal (règles, pièges, architecture)
  references/
    syntaxe.md          toute la syntaxe Rose : types, instructions,
                        opérateurs, bibliothèque standard
    cli.md              la ligne de commande : run / latex / comp / orc /
                        link / info / console, REPL, AOT, installation
  tour.rose             exemple vivant de toute la syntaxe
```

## Installation

Pour **opencode** : dépose `rose-dev/` dans `.opencode/skills/`.

Pour tout autre agent qui lit des skills au format Markdown : `SKILL.md`
porte le frontmatter `name` / `description` attendu.

## Vérifier que ça marche

```bash
cd rose && ./rose exemples/tour.rose
```

Le programme doit afficher les formules LaTeX et les résultats attendus.
