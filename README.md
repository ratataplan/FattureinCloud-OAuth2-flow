# FattureinCloud-OAuth2-flow

Questa classe permette di eseguire Oauth2 da un'applicazione Desktop Windows con le nuove API 2.0 di FattureinCloud in modo molto lineare
Apre una Tab di Chrome ed attende il redirect in caso di token nullo. Cattura il token dai parametri dell'url di redirect. Se è trascorso meno di un anno
dall'ultima autenticazione esegue il refresh del token in modo automatico e salva il nuovo token nel DB. Nel caso sia trascorso meno di un anno dall'ultima autenticazione il processo è completamente trasparente per l'utente.
