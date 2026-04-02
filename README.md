# MeetUp Bitcoin Nantes

Site officiel du MeetUp Bitcoin Nantes.  
Hébergé sur Vercel · Sous-domaine `www.meetupbitcoinnantes.orangepeel.fr`

## Stack

- HTML / CSS / JS pur — aucune dépendance
- Police : Syne (titres) + DM Sans (corps) via Google Fonts
- Déploiement : Vercel

## Structure

```
/
├── index.html
├── style.css
└── README.md
```

## Déploiement Vercel

1. Importer ce repo sur [vercel.com](https://vercel.com)
2. Framework preset : **Other** (aucun build requis)
3. Root directory : `/`
4. Dans les settings Vercel → Domains → ajouter `www.meetupbitcoinnantes.orangepeel.fr`
5. Ajouter le CNAME chez le registrar DNS d'orangepeel.fr :  
   `www.meetupbitcoinnantes` → `cname.vercel-dns.com`

## Développement local

```bash
# Option 1 : ouvrir directement dans le navigateur
open index.html

# Option 2 : serveur local avec VS Code Live Server
# Installer l'extension "Live Server" → clic droit sur index.html → Open with Live Server
```

## Contact

MeetUp Bitcoin Nantes · [Telegram](https://t.me/meetupbitcoinnantes) · [@NantesBitcoin](https://twitter.com/NantesBitcoin)
