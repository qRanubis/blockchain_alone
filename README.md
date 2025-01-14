1. Descrierea Proiectului
Proiectul este o aplicație web interactivă care combină jocul tradițional "Piatra-Foarfeca-Hartie" cu tehnologia blockchain. Scopul este să creeze o experiență captivantă, unde scorurile jucătorului sunt înregistrate și actualizate pe blockchain folosind NFT-uri. Proiectul integrează funcționalități avansate, precum conectarea cu wallet-uri, verificarea și generarea de NFT-uri, și un sistem de scor bazat pe interacțiuni în timp real.
Funcționalități principale
•	Conectarea unui wallet folosind fișiere .pem.
•	Verificarea existenței NFT-urilor pentru utilizator.
•	Crearea de NFT-uri în cazul în care lipsesc.
•	Actualizarea scorurilor NFT pe blockchain în funcție de performanța jucătorului.

2. Structura Proiectului
Tehnologii utilizate
•	Frontend: HTML, CSS, JavaScript
•	Backend: Python (Flask)
•	Blockchain/SKD: MultiversX  / : MultiversX SDK

3. Workflow al Aplicației
•	Conectare wallet: Utilizatorul încarcă un fișier .pem pentru a se autentifica.
•	Verificare NFT-uri: Aplicația verifică dacă utilizatorul deține NFT-urile necesare (Piatra, Foarfeca, Hartie).
•	Generare NFT-uri: În cazul în care lipsesc NFT-uri, acestea pot fi generate.
•	Joc interactiv: Utilizatorul se joacă cu robotul; cine ajunge primul la 5 puncte câștigă.
•	Actualizare scoruri: La finalul jocului, scorurile finale sunt scrise pe blockchain pentru NFT-uri.
•	Redirecționare: După finalizarea jocului, utilizatorul este redirecționat pe pagina principală, menținând wallet-ul conectat pentru sesiunea curentă.

4. Documentația utilizată
Biblioteci și Resurse Oficiale
•	MultiversX SDK Documentation
•	Flask Documentation

5. Documentație proprie
•	Configurarea proiectului
o	Instalarea Flask și a SDK-ului MultiversX.
o	Configurarea endpoint-urilor backend.
•	Logica jocului
o	Implementarea regulilor clasice pentru "Piatra-Foarfeca-Hartie".
o	Gestionarea scorurilor și a actualizărilor pe blockchain.
•	Fluxul de date
o	De la frontend la backend: Verificare și generare NFT.
o	De la backend la blockchain: Actualizare scoruri NFT.
•	Testare și depanare
o	Testarea tranzacțiilor pe devnet MultiversX.
