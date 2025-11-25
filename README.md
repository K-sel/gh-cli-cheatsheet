# gh-cli Cheatsheet

## Login / Logout
```bash
gh auth login
gh auth logout
```

## Workflow 1 : Création du repo distant + remote + push initial

```bash
git init
gh repo create nom-du-repo --public --source=. --remote=origin   # ou --private
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```
