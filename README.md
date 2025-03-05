# GitHub CLI Cheatsheet

## Navigation & Consultation

```bash
# Lister les repos
gh repo list

# Cloner un repo
gh repo clone owner/repo

# Voir les issues
gh issue list
gh issue view <number>

# Voir les pull requests
gh pr list
gh pr view <number>
```

## Issues

```bash
# Créer une issue
gh issue create --title "titre" --body "description"

# Fermer une issue
gh issue close <number>

# Réouvrir une issue
gh issue reopen <number>
```

## Pull Requests

```bash
# Créer une PR
gh pr create --title "titre" --body "description"

# Vérifier une PR
gh pr checkout <number>

# Merger une PR
gh pr merge <number>

# Fermer une PR
gh pr close <number>
```

## Gist

```bash
# Créer un gist
gh gist create file.txt

# Lister ses gists
gh gist list
```

## Releases

```bash
# Lister les releases
gh release list

# Créer une release
gh release create v1.0.0 --title "Version 1.0.0"

# Télécharger une release
gh release download v1.0.0
```

## Workflows

```bash
# Lister les workflows
gh workflow list

# Voir les runs d'un workflow
gh run list

# Voir les logs d'un run
gh run view <number>
```

> Pour plus de détails sur chaque commande, utilisez `gh <command> --help`
