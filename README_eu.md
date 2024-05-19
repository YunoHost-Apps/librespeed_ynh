<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# LibreSpeed YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/librespeed.svg)](https://dash.yunohost.org/appci/app/librespeed) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/librespeed.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/librespeed.maintain.svg)

[![Instalatu LibreSpeed YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=librespeed)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek LibreSpeed YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Self-hosted Speed Test for HTML5 and more. Easy setup, examples, configurable, mobile friendly. Supports PHP, Node, Multiple servers, and more.

### Features

- Download
- Upload
- Ping
- Jitter
- IP Address, ISP, distance from server (optional)
- Telemetry (optional)
- Results sharing (optional)
- Multiple Points of Test (optional)


**Paketatutako bertsioa:** 5.3.2~ynh1

**Demoa:** <https://librespeed.org>

## Pantaila-argazkiak

![LibreSpeed(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://librespeed.org>
- Erabiltzaileen dokumentazio ofiziala: <https://github.com/librespeed/speedtest/wiki>
- Administratzaileen dokumentazio ofiziala: <https://github.com/librespeed/speedtest/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/librespeed/speedtest>
- YunoHost Denda: <https://apps.yunohost.org/app/librespeed>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/librespeed_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing --debug
edo
sudo yunohost app upgrade librespeed -u https://github.com/YunoHost-Apps/librespeed_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
