# 🧩 Sudoku Game - Vue3 Edition

> *"Because sometimes you need to fill 81 squares to feel complete"* 🎯

[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-4FC08D?style=flat-square&logo=vue.js&logoColor=white)](https://vuejs.org/)
[![Offline First](https://img.shields.io/badge/Offline-First-green?style=flat-square)](https://web.dev/offline-first/)
[![No Server Required](https://img.shields.io/badge/Server-Not%20Required-red?style=flat-square)](https://github.com)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square)](https://github.com)

## 🚀 What's This?

Un'implementazione **completamente offline** del classico gioco Sudoku, costruita come Single Page Application con **Vue 3**. Niente server, niente dipendenze complesse, solo puro divertimento matematico! 🤯

## ✨ Features

- 🎮 **Tre livelli di difficoltà**: Facile, Medio, Difficile
- 🎨 **UI moderna e responsive** con gradients che fanno invidia a Instagram
- ⚡ **Completamente offline** - funziona anche senza internet!
- 🧠 **Solver automatico** per quando ti arrendi (nessun giudizio qui)
- ⏱️ **Timer integrato** per sfidare te stesso
- 📱 **Mobile friendly** - gioca ovunque, anche in bagno
- 🎯 **Validazione in tempo reale** - niente più errori nascosti
- 🎉 **Animazioni celebrate** quando completi il puzzle

## 🛠️ Tech Stack

```
Vue 3 (CDN) + Vanilla CSS + Pure JavaScript = ❤️
```

- **Frontend**: Vue 3 (via CDN - perché a volte semplice è meglio)
- **Styling**: CSS3 con gradients e animazioni smooth
- **Logic**: JavaScript ES6+ per la generazione e risoluzione dei puzzle
- **Dependencies**: Zero! (ok, Vue dal CDN, ma conta?)

## 🚀 Quick Start

1. **Clone this bad boy**:
   ```bash
   git clone https://github.com/tuousername/sudoku-vue3.git
   cd sudoku-vue3
   ```

2. **Open and play**:
   ```bash
   # Opzione 1: Doppio click su index.html
   open index.html
   
   # Opzione 2: Se sei un purista del terminale
   python -m http.server 8000
   # Poi vai su http://localhost:8000
   ```

3. **That's it!** 🎉 No npm install, no build process, no webpack config hell!

## 🎮 How to Play

1. 🎲 Clicca "Nuovo Gioco" per generare un puzzle
2. 🎯 Seleziona una cella vuota
3. 🔢 Usa il number pad per inserire i numeri (1-9)
4. ❌ Clicca "❌" per cancellare un numero
5. ✅ Usa "Verifica" per controllare se hai fatto errori
6. 💡 Se ti blocchi, "Risolvi" è tuo amico (ma dove sta il divertimento?)

## 🧠 Algorithm Nerdy Stuff

### Generazione del Puzzle
- **Backtracking algorithm** per generare soluzioni valide
- **Random cell removal** basato sulla difficoltà selezionata
- **Unicità garantita** - ogni puzzle ha una sola soluzione

### Solver
- **Constraint propagation** + **Backtracking**
- **Naked singles** e **Hidden singles** detection
- Risolve anche i puzzle più diabolici in millisecondi ⚡

## 📁 Project Structure

```
sudoku-vue3/
├── index.html          # 🏠 The one and only file you need
├── README.md          # 📖 You are here
└── .gitignore         # 🙈 Git stuff to ignore
```

*Sì, è tutto in un file. Deal with it.* 😎

## 🎨 Customization

Vuoi personalizzare i colori? Cerca questi CSS custom properties:

```css
/* Cambia il gradient principale */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Modifica i colori dei bottoni */
background: linear-gradient(45deg, #667eea, #764ba2);
```

## 🐛 Known Issues

- ⚠️ Il solver è troppo veloce (non è un bug, è una feature)
- 🎯 Potresti diventare dipendente dal gioco
- 🧠 Potrebbe aumentare il tuo QI involontariamente

## 🤝 Contributing

Found a bug? Want to add features? PRs are welcome! 

1. Fork it 🍴
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 🚀

## 📜 License

MIT License - perché condividere è bello! 

## 🙏 Credits

- **Vue.js Team** per aver reso JavaScript divertente di nuovo
- **Il matematico Leonhard Euler** per i quadrati latini (antenato del Sudoku)
- **Maki Kaji** per aver inventato il Sudoku moderno
- **Caffè** per aver reso possibile questo progetto ☕

---

<div align="center">

**Se questo progetto ti ha fatto sorridere, lascia una ⭐!**

*Made with 💻 and lots of ☕ by [Il Tuo Nome]*

</div>