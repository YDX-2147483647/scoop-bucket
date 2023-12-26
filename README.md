# A Personal [Scoop][scoop] Bucket

[![Tests](https://github.com/YDX-2147483647/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/YDX-2147483647/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/YDX-2147483647/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/YDX-2147483647/scoop-bucket/actions/workflows/excavator.yml)

A personal bucket for [Scoop][scoop], the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add me https://github.com/YDX-2147483647/scoop-bucket
scoop install me/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.

[scoop]: https://scoop.sh
