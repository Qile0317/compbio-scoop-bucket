# Scoop Bucket of Computational Biology Tools

[![Tests](https://github.com/Qile0317/compbio-scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Qile0317/compbio-scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Qile0317/compbio-scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Qile0317/compbio-scoop-bucket/actions/workflows/excavator.yml)

This is a small bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

Currently, only the `AliView` alignment viewer is available.

## Usage

```pwsh
# add the bucket
scoop bucket add Qile0317_compbio-scoop-bucket https://github.com/Qile0317/compbio-scoop-bucket
# install a package like AliView
scoop install Qile0317_compbio-scoop-bucket/aliview
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
