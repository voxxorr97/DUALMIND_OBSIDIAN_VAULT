# agent-browser-max v1.0

**Skill complet** créé le 28 mai 2026.

Fichier source : `/home/workdir/.grok/skills/agent-browser-max/SKILL.md`

**Résumé** :
- Donne des yeux + mains web à Hermes à 15x moins de tokens
- Utilise l’accessibility tree (pas de screenshots)
- Sessions persistantes (login YouTube/TikTok une seule fois)
- Parfait pour recherche, upload vidéo, analytics, scraping idées

**Installation sur VPS** :
```bash
npm install -g agent-browser
agent-browser install
```

**Test immédiat** :
```bash
agent-browser open https://gmail.com
agent-browser chat "Combien d'emails non lus ?"
```

**Intégration** : Hermes peut maintenant appeler cet outil directement pour toutes les tâches web.