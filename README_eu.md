<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# PeerTube Remote Runner YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/peertube_remote_runner.svg)](https://ci-apps.yunohost.org/ci/apps/peertube_remote_runner/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/peertube_remote_runner.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/peertube_remote_runner.maintain.svg)

[![Instalatu PeerTube Remote Runner YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=peertube_remote_runner)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek PeerTube Remote Runner YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Remote runner to offload heavy workloads jobs (such as transcoding) from one or several (distant) Peertube server.


**Paketatutako bertsioa:** 0.0.18~ynh1
## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://docs.joinpeertube.org/admin/remote-runners>
- Administratzaileen dokumentazio ofiziala: <https://docs.joinpeertube.org/maintain/tools#peertube-runner>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Chocobozzz/PeerTube/tree/develop/packages/peertube-runner>
- YunoHost Denda: <https://apps.yunohost.org/app/peertube_remote_runner>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing --debug
edo
sudo yunohost app upgrade peertube_remote_runner -u https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
