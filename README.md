# docker-php-mysql

Custom images for internal CI


**Nota:**\
Le immagini non vengono ri-buildate periodicamente, questo vuol dire che se si aggiorna una PATCH version di PHP in sviluppo (ossia ogni volta che viene eseguito il make-run nel progetto), e viene aggiornata anche la versione sul server di produzione con il classico apt-update & apt-upgrade, e magari viene trovato un nuovo bug, per aggiornare la versione dell'immagine bisogna triggerare la build dall'interfaccia delle builds di Docker Hub.
