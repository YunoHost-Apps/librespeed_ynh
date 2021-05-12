# LibreSpeed pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/librespeed.svg)](https://dash.yunohost.org/appci/app/librespeed) ![](https://ci-apps.yunohost.org/ci/badges/librespeed.status.svg)  ![](https://ci-apps.yunohost.org/ci/badges/librespeed.maintain.svg)
[![Installer librespeed avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=librespeed)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install librespeed quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Vue d'ensemble

Test de vitesse de connexion très léger implémenté en Javascript, utilisant XMLHttpRequest et Web Workers.

**Version incluse:** 1.0~ynh1

**Démo:** https://librespeed.org/


## Captures d'écran


   ![](./doc/screenshots/librespeed_screenshot.gif)




## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?



## Documentations et ressources

* Site official de l'app : https://librespeed.org/
* Documentation officielle utilisateur: https://yunohost.org/apps
* Documentation officielle de l'admin: https://yunohost.org/packaging_apps
* Dépôt de code officiel de l'app:  https://github.com/librespeed/speedtest
* Documentation YunoHost pour cette app: https://yunohost.org/app_librespeed
* Signaler un bug: https://github.com/YunoHost-Apps/librespeed_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing --debug
or
sudo yunohost app upgrade librespeed -u https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications:** https://yunohost.org/packaging_apps