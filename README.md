# Bitburner Dev Kit

Everything you need to start scripting for Bitburner with live reload and TypeScript

## Get Started

You'll need Node.js installed first.

```bash
git clone https://github.com/nsa-scripts/bitburner-dev
cd bitburner-dev
npm install
npm run watch
```

Then in Bitburner game: Options → Remote API → enter port number (usually 12525) → Connect

## What's Included

- Auto-reload when you save scripts
- TypeScript support out of the box  
- Development server that talks to game
- All the config files already set up

## Keeping Updated

```bash
npm update
# or if you want the template changes too:
git pull && npm install
```

Based on Vite - super fast development experience.

MIT License
