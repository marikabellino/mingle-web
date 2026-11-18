# mingle-web

Pagine web pubbliche di **mingle.**, pubblicate con GitHub Pages
(Settings → Pages → branch `main`, cartella `/ (root)`).

- `index.html` — pagina iniziale ("mingle. sta arrivando")
- `auth/confirm.html` — pagina di atterraggio dei link nelle email
  (conferma registrazione `?flow=signup`, reset password `?flow=reset`).
  Mostra "Email confermata" / "Link scaduto" e passa all'app i parametri
  del link con il pulsante "Apri mingle.".

L'app punta qui da `AppConstants.authLandingUrl` nel repository dell'app.
Questo repository deve restare **pubblico**: con il piano gratuito GitHub
Pages funziona solo sui repository pubblici. Non contiene chiavi né dati.
