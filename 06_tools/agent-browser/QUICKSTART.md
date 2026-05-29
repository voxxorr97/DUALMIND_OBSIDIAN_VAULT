# Quickstart agent-browser pour DualMind

## 1. Installation (une seule fois)

```bash
npm install -g agent-browser
agent-browser install
```

## 2. Test immédiat (copie-colle)

```bash
agent-browser open https://example.com
agent-browser snapshot --format png
agent-browser chat "Quel est le titre de cette page ?"
```

## 3. Commandes les plus utiles pour nous

- `agent-browser open [url]`
- `agent-browser click @E1`
- `agent-browser fill @E2 "texte"`
- `agent-browser snapshot`
- `agent-browser chat "instruction"`
- `agent-browser batch ...`

## 4. Sessions persistantes (important !)

```bash
agent-browser --profile dualmind open https://youtube.com
# La prochaine fois :
agent-browser --profile dualmind open https://youtube.com/upload
```

**Pro tip** : Utilise `--profile dualmind` pour garder tes logins YouTube/TikTok entre les sessions.