# TROVAT1O · preview Cloudflare Workers

Pacchetto statico mobile first per una prima prova pubblica. Il claim è **Non perderti più una partita**.

## Stato

- Il sito serve `public/` come asset statici su un URL `workers.dev`.
- Mantiene `onlineReady: false`: account reali, eventi condivisi, OTP, notifiche push, Supabase e pagamenti non sono attivi.
- Usa i dati dimostrativi nel browser. Non inserire dati reali o di altre persone.
- Pagine informative: privacy, cookie/archiviazione, termini e politiche.
- Mantiene `noindex` per ridurre l'indicizzazione della preview.

## Deploy

Il progetto Cloudflare `trovato` usa il comando `npx wrangler deploy` dalla radice. Questo file configura l'asset directory e abilita l'URL `workers.dev` del Worker.

La versione è stata preparata per il piano gratuito; controlla nel pannello Cloudflare che il Worker rimanga sul piano Free e verifica i limiti prima di invitare utenti reali.
