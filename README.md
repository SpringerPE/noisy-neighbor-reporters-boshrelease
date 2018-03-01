Noisy Neighbor Reporters Release
=====================

This is the [BOSH](bosh) release for the
[Noisy Neighbor Reporters](https://github.com/SpringerPE/noisy-neighbor-reporters.git).

For more information on how the reporters release works and configuration, see the README
for the [Noisy Neighbor Reporters](https://github.com/SpringerPE/noisy-neighbor-reporters.git).

# Dependencies

The Noisy neighbor reporters release depends at the moment on the [cf-light-api](https://github.com/SpringerPE/cf-light-api) a lightweight cached api for Cloudfoundry.

# How to use this release

- Upload first the release to BOSH:

```
bosh upload release https://github.com/SpringerPE/noisy-neighbor-reporters-boshrelease/releases/download/v1/noisy-neighbor-reporters-release-1.tgz

```

- Create a manifest following the model in `manifests/noisy-nozzle.vsphere.yaml` and adapting it to your infrastructure and needs

- Point to the manifest with `bosh deployment noisy-nozzle-manifest.yaml` and `bosh deploy`!
