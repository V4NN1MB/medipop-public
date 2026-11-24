# medipop-public

Il sito pubblico di **Medipop** (https://medipop.app): presentazione,
informativa privacy e assistenza, in cinque lingue: italiano (alla radice,
l'originale), inglese (`en/`), francese (`fr/`), spagnolo (`es/`) e tedesco
(`de/`). Ogni lingua ha tre pagine: `index.html`, `privacy.html` e assistenza
(`supporto.html` in italiano, `support.html` nelle altre). Il selettore delle
lingue è nel piede di ogni pagina; `style.css`, `icon.svg` e `img/` sono comuni.

- Solo HTML e CSS statici: nessuno script, nessun cookie, nessuna risorsa
  esterna (niente font o librerie da altri siti, niente statistiche).
- Pubblicazione: a mano, via SFTP, nella cartella `medipop` dell'hosting OVH
  (il piano Personale non permette Git né altri utenti FTP per un secondo
  sito). Si caricano tutti i file tranne `README.md`.
- `.htaccess`: intestazioni di sicurezza (CSP stretta, niente iframe, HSTS) e un solo indirizzo, https://medipop.app (www e http con un 301).

Il codice dell'app non è qui: questo repository contiene solo il sito.
