# medipop-public

Il sito pubblico di **Medipop** (https://medipop.app): presentazione,
informativa privacy e assistenza, in italiano e in inglese.

- Solo HTML e CSS statici: nessuno script, nessun cookie, nessuna risorsa
  esterna (niente font o librerie da altri siti, niente statistiche).
- Pubblicazione: ogni push su `main` viene scaricato dall'hosting OVH nella
  cartella `medipop` (webhook GitHub → OVH), come per gli altri siti.
- `.htaccess`: intestazioni di sicurezza (CSP stretta, niente iframe).
  HSTS e il reindirizzamento a HTTPS si accendono quando il certificato di
  medipop.app è attivo.

Il codice dell'app non è qui: questo repository contiene solo il sito.
