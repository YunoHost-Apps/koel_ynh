<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Koel YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/koel.svg)](https://dash.yunohost.org/appci/app/koel) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/koel.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/koel.maintain.svg)

[![Instalatu Koel YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=koel)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Koel YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Koel is a simple web-based personal audio streaming service written in Vue on the client side and Laravel on the server side.

Targeting web developers, Koel embraces some of the more modern web technologies to do its job.


**Paketatutako bertsioa:** 6.12.1~ynh1

**Demoa:** <https://demo.koel.dev>

## Pantaila-argazkiak

![Koel(r)en pantaila-argazkia](./doc/screenshots/showcase.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://koel.dev>
- Administratzaileen dokumentazio ofiziala: <https://docs.koel.dev>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/koel/koel>
- YunoHost Denda: <https://apps.yunohost.org/app/koel>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/koel_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/koel_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/koel_ynh/tree/testing --debug
edo
sudo yunohost app upgrade koel -u https://github.com/YunoHost-Apps/koel_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
