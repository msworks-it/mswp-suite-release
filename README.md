# MSWorks WordPress Suite: releases

Public releases of the WordPress plugins of the MSWorks WordPress Suite (`mswp-*`), by
[M's Works](https://msworks.it).

Every release on the [Releases](https://github.com/msworks-it/mswp-suite-release/releases) page
contains the plugin zip, its SHA-256 checksum and the changelog of that version. The tag is
`<plugin>@<version>`, e.g. `mswp-geo@0.2.0`.

## Plugins

| Plugin | What it does | Requires |
|---|---|---|
| **MSWP GEO** (`mswp-geo`) | Generative Engine Optimization: AI crawler access rules and llms.txt, working alongside your SEO plugin | WordPress 6.8+, PHP 8.1+ |

Versions `0.x` are published as pre-releases: they are early development versions.

## Install from a zip

1. Download `<plugin>.<version>.zip` from the release.
2. In WordPress, go to **Plugins > Add New Plugin > Upload Plugin**, choose the zip and activate it.

Once a plugin is listed on wordpress.org, install and update it from there: sites do not receive
updates from this repository.

## Verify a download

```sh
sha256sum -c mswp-geo.0.2.0.zip.sha256
```

On Windows (PowerShell): `Get-FileHash mswp-geo.0.2.0.zip -Algorithm SHA256`, then compare it with
the value in the `.sha256` file.

## Security

Please report vulnerabilities privately, as described in [SECURITY.md](SECURITY.md).

## License

GPL-2.0-or-later. See [LICENSE](LICENSE).
