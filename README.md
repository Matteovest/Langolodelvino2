# Sito Web Enoteca Locale

## 🌐 Come Rendere il Sito Accessibile

Il sito è attualmente **locale** (solo sul tuo computer). Per renderlo accessibile ad altri, hai diverse opzioni:

---

## Opzione 1: Server Locale (Accessibile nella tua rete locale)

### Con Python (più semplice)
1. Apri il terminale nella cartella del sito
2. Esegui uno di questi comandi:

**Python 3:**
```bash
python -m http.server 8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

3. Il sito sarà disponibile su:
   - **Sul tuo computer:** `http://localhost:8000`
   - **Per altri nella tua rete:** `http://[TUO-IP]:8000`

Per trovare il tuo IP su Windows:
```bash
ipconfig
```
Cerca "Indirizzo IPv4" (es. 192.168.1.100)

**Limiti:** Solo accessibile se altri sono nella tua stessa rete WiFi/Ethernet.

---

## Opzione 2: Hosting Online Gratuito (Accessibile da tutto il mondo)

### A) GitHub Pages (Gratuito e facile)
1. Crea un account su GitHub.com
2. Crea un nuovo repository
3. Carica i file del sito (index.html, styles.css, script.js)
4. Vai su Settings → Pages
5. Il sito sarà disponibile su: `https://tuousername.github.io/nome-repository`

### B) Netlify Drop (Gratuito, molto facile)
1. Vai su https://app.netlify.com/drop
2. Trascina la cartella con i file del sito
3. Il sito sarà immediatamente online con un link tipo: `https://random-name.netlify.app`

### C) Vercel (Gratuito, facile)
1. Vai su https://vercel.com
2. Registrati
3. Clicca "New Project" → carica la cartella
4. Il sito sarà online immediatamente

### D) Surge.sh (Gratuito, da terminale)
1. Installa: `npm install -g surge`
2. Nella cartella del sito esegui: `surge`
3. Il sito sarà online in pochi secondi

---

## Opzione 3: Server Web Tradizionale

Se hai già un hosting (es. Aruba, SiteGround, Hostinger):
1. Carica i file (index.html, styles.css, script.js) via FTP
2. Il sito sarà accessibile dal tuo dominio

---

## 📁 File del Sito

Il sito è composto da questi file:
- `index.html` - Struttura e contenuti
- `styles.css` - Stili e design
- `script.js` - Funzionalità interattive

---

## 🚀 Quick Start - Server Locale

Ho creato degli script per avviare facilmente un server locale:

**Windows (PowerShell):**
```powershell
.\start-server.ps1
```

**Windows (CMD) o Linux/Mac:**
```bash
start-server.bat
```

Oppure manualmente con Python:
```bash
python -m http.server 8000
```

Poi apri il browser su: `http://localhost:8000`

---

## 🔒 Sicurezza

- **Server locale:** Solo accessibile nella tua rete domestica
- **Hosting online gratuito:** Accessibile da tutto il mondo (controlla le impostazioni di privacy se necessario)

---

## 💡 Raccomandazione

Per un'enoteca locale, ti consiglio:
- **Netlify Drop** o **Vercel** per una pubblicazione rapida online
- **GitHub Pages** se vuoi avere il controllo completo e aggiornamenti facili
- **Server locale** se vuoi solo mostrarlo temporaneamente in negozio o a clienti in visita

---

## 📞 Serve Aiuto?

Se hai bisogno di assistenza per una delle opzioni, posso aiutarti passo passo!

