# 🃏 Design Pattern Trainer

Gioco web per imparare a **riconoscere, applicare e disegnare** i 22 design pattern
della Gang of Four (GoF).

👉 **[Prova la demo](https://alemozzoni.github.io/DesignPattern/)**

## Perché l'ho creato
L'ho sviluppato per prepararmi all'esame di **Ingegneria del Software** all'Università
di Camerino. Leggere la teoria non bastava: volevo uno strumento che mi obbligasse a
*usare* i pattern, non solo a ricordarne il nome.

## Funzionalità
- **22 pattern** divisi per categoria: Creazionali (5), Strutturali (7), Comportamentali (10)
- **7 modalità di allenamento**:
  - 🔍 **Riconosci**: dal problema o dall'esempio, indovina il pattern
  - 🎯 **Applica**: scegli il pattern giusto per uno scenario reale
  - 🎯🎯 **Applica ×2**: scenari che richiedono due pattern insieme
  - ✏️ **Disegna**: flashcard sulla struttura UML, da disegnare su carta e poi confrontare
  - 🗣️ **Spiega**: spiega a voce un pattern estratto a caso
  - ⚖️ **Confronta**: due pattern simili a confronto
  - 🎲 **Sfida mista**: tutte le modalità insieme
- Sessioni da **10 domande** con punteggio e serie di risposte corrette
- **Filtro per categoria**, per concentrarsi solo su una parte del programma

## Tecnologie
- **HTML, CSS e JavaScript** puri, senza framework né dipendenze esterne
- **Progressive Web App (PWA)**: si installa su smartphone e desktop come un'app
- **Service worker** con cache: dopo la prima apertura funziona anche **offline**
- Pubblicata con **GitHub Pages**

## Eseguirlo in locale
```bash
git clone https://github.com/alemozzoni/DesignPattern.git
cd DesignPattern
# Il service worker richiede un server: non basta aprire il file direttamente
python3 -m http.server 8000
# poi apri http://localhost:8000

Fonti

Contenuti basati su Design Patterns: Elements of Reusable Object-Oriented Software
(Gamma, Helm, Johnson, Vlissides, 1994).

Autore

Alessandro Mozzoni
