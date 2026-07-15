# 🍓 GS1 Digital Link & AI-Ready Product Page Demo

Questa repository contiene una landing page dimostrativa per un prodotto GS1 (Marmellata di Fragole Extra, GTIN: **08032089000147**). 

Il progetto funge da "Proof of Concept" (PoC) per dimostrare come unire un'interfaccia utente (UI) moderna e focalizzata sulla conversione con un'infrastruttura di **Dati Strutturati (JSON-LD)** avanzata, leggibile perfettamente sia dai motori di ricerca tradizionali (Google) sia dai nuovi Agenti AI (ChatGPT, Gemini).

---

## 🚀 Caratteristiche Principali

### 1. Architettura GS1 Digital Link
Il progetto è strutturato per simulare un resolver GS1 Digital Link direttamente su GitHub Pages. L'URL di produzione rispetta lo standard URI di GS1 (senza estensioni `.html` o slash finali indesiderati):
👉 `.../01/08032089000147`

### 2. Dati Strutturati Ibridi (GS1 + Schema.org)
Il "motore nascosto" della pagina è un JSON-LD unificato che accontenta sia le logiche E-commerce che quelle B2B:
* **Schema.org (`Product`, `Offer`)**: Per sbloccare i Rich Snippet su Google Search e Google Merchant Center (prezzo, disponibilità, immagini).
* **GS1 Web Vocabulary (`gs1:FoodBeverageTobaccoProduct`)**: Per fornire dati di filiera ultra-precisi alle macchine e alle AI (Dimensioni logistiche, GTIN14, GLN del Brand Owner, Tabella Nutrizionale, Ingredienti strutturati).

### 3. AI & LLM Ready
La pagina è progettata per essere ispezionata da modelli linguistici dotati di Web Browsing (come ChatGPT o Gemini Advanced). Un'AI che visita la pagina è in grado di bypassare la UI estraendo istantaneamente il peso netto, la percentuale esatta degli ingredienti (es. *Fragole al 70%*) e i dati logistici aziendali.

---

## 🔗 Live Demo

Puoi navigare la pagina utente e ispezionare il codice sorgente (o inviare l'URL a un'Intelligenza Artificiale per l'estrazione dati) a questo indirizzo:

🌐 **[https://marcoruberto-gs1it.github.io/demo1/01/08032089000147]**
