<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# PeerTube Remote Runner untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/peertube_remote_runner.svg)](https://ci-apps.yunohost.org/ci/apps/peertube_remote_runner/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/peertube_remote_runner.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/peertube_remote_runner.maintain.svg)

[![Pasang PeerTube Remote Runner dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=peertube_remote_runner)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang PeerTube Remote Runner secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Remote runner to offload heavy workloads jobs (such as transcoding) from one or several (distant) Peertube server.


**Versi terkirim:** 0.0.18~ynh1
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://docs.joinpeertube.org/admin/remote-runners>
- Dokumentasi admin resmi: <https://docs.joinpeertube.org/maintain/tools#peertube-runner>
- Repositori kode aplikasi hulu: <https://github.com/Chocobozzz/PeerTube/tree/develop/packages/peertube-runner>
- Gudang YunoHost: <https://apps.yunohost.org/app/peertube_remote_runner>
- Laporkan bug: <https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing --debug
atau
sudo yunohost app upgrade peertube_remote_runner -u https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
