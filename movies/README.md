# Getting Started with Create React App

# 🎬 Movie Filter (React)

Miniaplikace pro filtrování filmů podle kategorie.

## Rychlý start

```bash
npm install
# CRA
npm start
# Vite
npm run dev
```

## Jak to funguje

* `typeOfMovie` (výchozí **"komedie"**) ve state
* `vysledneFilmy = allMovies.filter(m => m.category === typeOfMovie)`
* Tlačítka z `Categories.js` mění `typeOfMovie`

## Soubory

```
src/App.jsx
src/Categories.js   // export default ["komedie", "romantický", "akční", "horor"]
src/data.js         // { id, image, title, age, tags, description, category }
```

> Tip: Hodnota `category` v `data.js` musí přesně odpovídat položkám v `Categories.js`.
