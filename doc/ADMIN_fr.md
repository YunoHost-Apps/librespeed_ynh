* Toute limitation, contrainte ou élément connu ne fonctionnant pas :
     * Veuillez visiter [Dépannage, problèmes courants, limitations connues](https://github.com/librespeed/speedtest/wiki/Troubleshooting,-common-problems,-known-limitations) pour plus d'informations.
     * Important : l'obfuscation d'ID ne fonctionne actuellement que sur PHP 64 bits ! Vous souhaiterez peut-être définir `$redact_ip_addresses` sur true dans `results/telemetry_settings.php`, de cette façon, toutes les adresses IP seront supprimées de la télémétrie pour une meilleure confidentialité. Ceci est désactivé par défaut.

* Informations à connaître :
     * Une interface de base pour visualiser et rechercher des tests par ID est disponible dans `__DOMAIN____PATH__/results/stats.php`. Un mot de passe vous est demandé lors des étapes d'installation pour accéder à cette page.