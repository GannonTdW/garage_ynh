<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Garage for YunoHost

[![Integration level](https://dash.yunohost.org/integration/garage.svg)](https://dash.yunohost.org/appci/app/garage) ![Working status](https://ci-apps.yunohost.org/ci/badges/garage.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/garage.maintain.svg)

[![Install Garage with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=garage)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Garage quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Garage is an S3-compatible distributed object storage service designed for self-hosting at a small-to-medium scale.

Garage is designed for storage clusters composed of nodes running at different physical locations, in order to easily provide a storage service that replicates data at these different locations and stays available even when some servers are unreachable. Garage also focuses on being lightweight, easy to operate, and highly resilient to machine failures.

### Features

- S3 API
- Standalone/self-contained
- Flexible topology
- No RAFT slowing you down
- Several replication modes
- Web server for static websites
- Bucket names as aliases
- Cluster administration API
- Metrics and traces
- Support for changing IP addresses
- K2V API (experimental)


**Shipped version:** 0.9.2~ynh1
## Documentation and resources

- Official app website: <https://garagehq.deuxfleurs.fr/>
- Official user documentation: <https://garagehq.deuxfleurs.fr/documentation/quick-start/>
- Official admin documentation: <https://garagehq.deuxfleurs.fr/documentation/quick-start/>
- Upstream app code repository: <https://git.deuxfleurs.fr/Deuxfleurs/garage>
- YunoHost Store: <https://apps.yunohost.org/app/garage>
- Report a bug: <https://github.com/YunoHost-Apps/garage_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/garage_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/garage_ynh/tree/testing --debug
or
sudo yunohost app upgrade garage -u https://github.com/YunoHost-Apps/garage_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
