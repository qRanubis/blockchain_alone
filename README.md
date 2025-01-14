Descrierea Proiectului
Această aplicație web interactivă combină jocul clasic "Piatra-Foarfeca-Hârtie" cu tehnologia blockchain, oferind o experiență captivantă și inovatoare. Scorurile jucătorului sunt înregistrate și actualizate direct pe blockchain, utilizând NFT-uri personalizate.

Funcționalități principale:

Conectarea wallet-ului utilizând fișiere .pem.
Verificarea existenței NFT-urilor pentru utilizator.
Generarea NFT-urilor lipsă, dacă este necesar.
Actualizarea scorurilor NFT în funcție de performanța din joc.
Structura Proiectului
Tehnologii utilizate:

Frontend: HTML, CSS, JavaScript
Backend: Python (Flask)
Blockchain/SDK: MultiversX SDK
Workflow al Aplicației
Conectare wallet: Utilizatorul se autentifică prin încărcarea unui fișier .pem.
Verificare NFT-uri: Se verifică dacă utilizatorul deține NFT-urile necesare (Piatra, Foarfeca, Hârtie).
Generare NFT-uri: Dacă unul sau mai multe NFT-uri lipsesc, acestea sunt create automat.
Joc interactiv: Utilizatorul joacă împotriva unui robot; primul care ajunge la 5 puncte câștigă.
Actualizare scoruri: La finalul jocului, scorurile sunt salvate pe blockchain în NFT-urile utilizatorului.
Redirecționare: După finalizarea jocului, utilizatorul este redirecționat pe pagina principală, menținând sesiunea wallet-ului activă.
Documentația Utilizată
Biblioteci și resurse oficiale:

MultiversX SDK Documentation
Flask Documentation
Documentație Proprie
1. Configurarea Proiectului
Instalarea Flask și SDK-ului MultiversX.
Configurarea endpoint-urilor pentru backend.
2. Logica Jocului
Implementarea regulilor clasice pentru "Piatra-Foarfeca-Hârtie".
Gestionarea scorurilor și actualizarea acestora pe blockchain.
3. Fluxul de Date
Frontend → Backend: Verificarea și generarea NFT-urilor.
Backend → Blockchain: Actualizarea scorurilor NFT.
4. Testare și Depanare
Testarea tranzacțiilor pe devnet MultiversX.
Debugging al interacțiunilor dintre backend și blockchain.
