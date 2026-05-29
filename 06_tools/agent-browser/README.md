# agent-browser (Vercel Labs) - Intégration DualMind

**Version** : 0.27.0+ (28 mai 2026)

**Pourquoi on l’ajoute** :
- 15x moins de tokens que Playwright MCP
- Lit l’accessibility tree au lieu de screenshots
- Claude / Hermes peut ouvrir son propre navigateur et cliquer directement (@E1, @E2...)
- Parfait pour recherche, upload vidéo, analytics, scraping idées, etc.

## Installation (VPS ou local)

```bash
npm install -g agent-browser
agent-browser install          # télécharge Chrome for Testing
```

## Test rapide (5 commandes)

```bash
agent-browser open https://gmail.com
agent-browser snapshot
agent-browser chat "Combien d'emails non lus ?"
agent-browser click @E1
agent-browser close
```

## Intégration Hermes CEO

Hermes peut maintenant :
- Faire de la recherche web native
- Uploader des vidéos sur YouTube/TikTok
- Checker des stats
- Scraper des idées de dossiers

**Skill associé** : `agent-browser-max` (dans .grok/skills)

**Règle** : Toujours utiliser `--session` pour garder les logins entre les runs.