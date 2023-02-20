# [1.7.0](https://github.com/SmartMedSA/github-workflows/compare/v1.6.0...v1.7.0) (2023-02-20)


### Features

* **github/skaffold:** support vals ([c96985c](https://github.com/SmartMedSA/github-workflows/commit/c96985c5861857d9b4569cb85c67f41b775bd490))

# [1.6.0](https://github.com/SmartMedSA/github-workflows/compare/v1.5.1...v1.6.0) (2023-01-12)


### Features

* bump node version to 18 ([9dd0b0a](https://github.com/SmartMedSA/github-workflows/commit/9dd0b0a52c5f57378244fcf1e9a14bbccc5b4f27))

## [1.5.1](https://github.com/SmartMedSA/github-workflows/compare/v1.5.0...v1.5.1) (2022-12-21)


### Bug Fixes

* **skaffold:** mdgreenwald/mozilla-sops-action version ([b9a46a8](https://github.com/SmartMedSA/github-workflows/commit/b9a46a8a3c824ff347212352b10213d2bed5bfc5))

# [1.5.0](https://github.com/SmartMedSA/github-workflows/compare/v1.4.0...v1.5.0) (2022-12-21)


### Features

* **skaffold:** bump default version to 1.39.4 ([a77d23b](https://github.com/SmartMedSA/github-workflows/commit/a77d23bfd9a9a68ed01a29c80f8f28ca851e411b))
* **skaffold:** bump mdgreenwald/mozilla-sops-action@v1.4 ([9012b97](https://github.com/SmartMedSA/github-workflows/commit/9012b972d14aeedc5737bb2849fddd994a130ab7))

# [1.4.0](https://github.com/SmartMedSA/github-workflows/compare/v1.3.0...v1.4.0) (2022-12-21)


### Features

* **docker_build:** bump actions/checkout version ([c35581f](https://github.com/SmartMedSA/github-workflows/commit/c35581f8471d4a70fd309ac730794882a45b1828))

# [1.3.0](https://github.com/SmartMedSA/github-workflows/compare/v1.2.0...v1.3.0) (2022-12-15)


### Features

* upgrade deps actions - fix output warning ([4297a16](https://github.com/SmartMedSA/github-workflows/commit/4297a1631db6f0a30ef33f313c13f8efa97cbbc8))

# [1.2.0](https://github.com/SmartMedSA/github-workflows/compare/v1.1.0...v1.2.0) (2022-12-15)


### Features

* **skaffold:** set action-setup-kube-tools v0.9.2 ([55cfe94](https://github.com/SmartMedSA/github-workflows/commit/55cfe94734d91719f56de738191e6c40d00230ed))

# [1.1.0](https://github.com/SmartMedSA/github-workflows/compare/v1.0.0...v1.1.0) (2022-10-22)


### Bug Fixes

* **docker_build:** better group concurrency setting ([aa6763d](https://github.com/SmartMedSA/github-workflows/commit/aa6763d7eca3e95bfcb83b5af97d11752e726279))
* **docker_delete:** Input required and not supplied: name ([bf7cb17](https://github.com/SmartMedSA/github-workflows/commit/bf7cb1748184dc3fcda5d7bbe21a697f05541215))
* **skaffold:** correct version for yokawasa/action-setup-kube-tools ([39edd10](https://github.com/SmartMedSA/github-workflows/commit/39edd10fa4631c0d1c165f7dd777dbdacc12a7b7))


### Features

* **docker_build:** bump ASzc/change-string-case-action to v3 ([5c97b8f](https://github.com/SmartMedSA/github-workflows/commit/5c97b8ffb5a3dfb57135c7783c4ab261ea1f9e7e))
* **skaffold:** add sops install action ([511287c](https://github.com/SmartMedSA/github-workflows/commit/511287c129ae8d4bb8f1f049ac7968129a217263))
* **skaffold:** yokawasa/action-setup-kube-tools bump to v0.8 ([2b9b6b1](https://github.com/SmartMedSA/github-workflows/commit/2b9b6b1e21a63cd5457a769a6c2597a9588fe6d1))

# 1.0.0 (2022-10-15)


### Bug Fixes

* better output for docker build, wip skaffold workflow ([#4](https://github.com/SmartMedSA/github-workflows/issues/4)) ([7dd2d7a](https://github.com/SmartMedSA/github-workflows/commit/7dd2d7a2c2aad8a8fa56f97ed0590093cd0bd2c6))
* deploy url output empty ([2d9d4eb](https://github.com/SmartMedSA/github-workflows/commit/2d9d4ebbe2af612154ebdfaf7b0e03a4bfafea7f))
* deploy url output empty ([ed3152a](https://github.com/SmartMedSA/github-workflows/commit/ed3152a412199ac526052c7a1ba7fa185ed76c92))
* deploy url output empty ([3d4bd07](https://github.com/SmartMedSA/github-workflows/commit/3d4bd07632ba2477575e6f516e3c10324c693b3a))
* **docker_build/docker_delete:** caching + missing workflow inputs ([b81ec52](https://github.com/SmartMedSA/github-workflows/commit/b81ec527b99bafbe15834cbd7fc672f33c556fcc))
* **docker_build:** add workflow top level outputs ([1003470](https://github.com/SmartMedSA/github-workflows/commit/100347064decc6d7aaf4d023767719493105a7e7))
* **docker_build:** concurrency group too generic ([ed0d681](https://github.com/SmartMedSA/github-workflows/commit/ed0d6810195b83a262229c2cff5b75dabbed5858))
* **docker_build:** drop lint and test workflows ([d1da220](https://github.com/SmartMedSA/github-workflows/commit/d1da220c97b98b46dc61d302b3cdca52b3f9265d))
* **github/release:** workflow definition ([d3fe232](https://github.com/SmartMedSA/github-workflows/commit/d3fe23261601a5bb82e4f1c1a5438fd2b517ae9f))
* references to workflows must be rooted in '.github/workflows' ([4e13fd6](https://github.com/SmartMedSA/github-workflows/commit/4e13fd65bf5a38538bac6b18c5cfc02ee7e200e4))
* tempo set github checkout action to 3.0.2 ([cba87d0](https://github.com/SmartMedSA/github-workflows/commit/cba87d0a02efd85efb1b03b8863aa6e461eea721))


### Features

* deploy url output ([18ab387](https://github.com/SmartMedSA/github-workflows/commit/18ab3876255902282429b38a59f3d7642ddeec32))
* **docker_build:** add concurrency setting ([3b74880](https://github.com/SmartMedSA/github-workflows/commit/3b7488073de721d620210e35f0a728cad166f949))
* **github/release:** add semantic_release workflow ([26ac9a9](https://github.com/SmartMedSA/github-workflows/commit/26ac9a9ebd9cc0f35d20c8620bf4ed4fdf2dbc5a))
* **github/skaffold:** add deployment workflow ([f3ca583](https://github.com/SmartMedSA/github-workflows/commit/f3ca5839979a7075d8d80529b73d2bff6e5da715))
* initial commit, pull workflows from various projects ([fafa24c](https://github.com/SmartMedSA/github-workflows/commit/fafa24c2045c4790b0c730358b1e2abf62f0b48e))
* **waypoint:** split wpoutputs to it's own step ([d0c2979](https://github.com/SmartMedSA/github-workflows/commit/d0c29791d74d1512a6773b6f1b9f3ad9442728a4))
