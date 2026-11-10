# Canvas Didattici - Laboratorio Digitale Interattivo

Portale web interattivo progettato per raccogliere e consultare simulazioni didattiche (2D e 3D) per l'insegnamento e l'esplorazione visiva di concetti scientifici e matematici.

## 🚀 Sito Web Online (GitHub Pages)

Il portale è pubblicato ed accessibile al pubblico:
👉 **[https://galassopartecipanteai-svg.github.io/canvas-didattici/](https://galassopartecipanteai-svg.github.io/canvas-didattici/)**

---

## 📂 Struttura del Progetto

- **`index.html`**: Homepage del portale con la vetrina/galleria di tutte le simulazioni didattiche, filtri per materia e guida per l'aggiunta di nuovi contenuti.
- **`geometria_neon_enti_fondamentali.html`**: Simulazione 3D interattiva creata con Three.js dedicata agli enti geometrici fondamentali (punto, retta, piano).
- **Prossime simulazioni**: nuovi file HTML generati possono essere salvati direttamente nella root e collegati nella griglia di `index.html`.

---

## 📐 Simulazioni Presenti

### 1. Geometria Neon: Enti Fondamentali
- **Link diretto**: [geometria_neon_enti_fondamentali.html](geometria_neon_enti_fondamentali.html)
- **Caratteristiche**:
  - Manipolazione 3D con Three.js e OrbitControls.
  - Creazione dinamica di punti nello spazio e sul piano euclideo &alpha;.
  - Tracciamento di rette luminose tra due punti.
  - Ispezione delle proprietà geometriche con interfaccia Cyber/Neon.

---

## ➕ Come aggiungere una nuova simulazione

1. Salva il file HTML generato (es. con Gemini) nella cartella del progetto:
   ```text
   nuova_simulazione.html
   ```
2. In `index.html`, aggiungi una nuova `<article class="sim-card ...">` con titolo, descrizione e il link al nuovo file.
3. Esegui il commit e push su GitHub:
   ```bash
   git add .
   git commit -m "Aggiunta nuova simulazione"
   git push origin main
   git checkout gh-pages
   git merge main
   git push origin gh-pages
   ```
   Entro 1 minuto la nuova simulazione sarà online su GitHub Pages!
