# Thème Nextcloud — GDL

## Installation (AIO)

1. Copier le dossier `themes/gdl` dans `/var/www/html/themes/` (conteneur `nextcloud-aio-nextcloud`).
2. Dans `/var/www/html/config/config.php`, ajouter **dans** `$CONFIG` : `'theme' => 'gdl',`
3. Vérifier la syntaxe : `php -l /var/www/html/config/config.php`
4. Purger/recharger :
