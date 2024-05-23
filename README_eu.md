<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Iceshrimp YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/iceshrimp.svg)](https://dash.yunohost.org/appci/app/iceshrimp) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/iceshrimp.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/iceshrimp.maintain.svg)

[![Instalatu Iceshrimp YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=iceshrimp)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Iceshrimp YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Iceshrimp is a decentralized and federated social networking service, implementing the ActivityPub standard.

It was forked from Calckey Firefish (itself a fork of Misskey) in mid-2023, to focus on stability, performance and usability instead of new features.

**Paketatutako bertsioa:** 2023.12.6~ynh1

## Pantaila-argazkiak

![Iceshrimp(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://iceshrimp.dev>
- Jatorrizko aplikazioaren kode-gordailua: <https://iceshrimp.dev/iceshrimp/iceshrimp>
- YunoHost Denda: <https://apps.yunohost.org/app/iceshrimp>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/iceshrimp_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing --debug
edo
sudo yunohost app upgrade iceshrimp -u https://github.com/YunoHost-Apps/iceshrimp_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
