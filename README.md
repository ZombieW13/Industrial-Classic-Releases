# IndustrialClassic Releases

Official public distribution channel for IndustrialClassic.

This repository contains release downloads, manifests, checksums, release notes
and the license files required by each package. It does **not** contain or mirror
the private development source repository.

## Current status

The first public Alpha, `A.12.0`, is being prepared. A version is available only
after it appears on the [Releases page](https://github.com/ZombieW13/Industrial-Classic-Releases/releases).

Do not download placeholder files or builds obtained from third-party sources.

## Supported environment

- Minecraft: Java Edition `26.2`;
- Java `25`;
- Fabric Loader `0.19.3`;
- Fabric API `0.155.2+26.2`;
- Windows 11 x64 for the official IndustrialClassic Launcher.

## Release downloads

Each approved release may contain:

- `IndustrialClassic-A.<sprint>.<revision>.jar` — Fabric mod;
- `IndustrialClassic-Launcher-Setup-<revision>.exe` — recommended Windows installer;
- `IndustrialClassic-Launcher-<revision>-win-x64.zip` — portable Launcher package;
- `IndustrialClassic-Launcher-<revision>.exe` — executable used by Launcher updates;
- `IndustrialClassic-Launcher-Updater.exe` — transactional update helper;
- `IndustrialClassic-Server-A.<sprint>.<revision>.zip` — dedicated-server package;
- `manifest-A.<sprint>.<revision>.json` and `manifest-stable.json` — verified distribution manifests;
- `checksums.sha256` — SHA-256 hashes for every published asset.

The first public executables are not digitally signed. Verify downloads against
`checksums.sha256` from the same GitHub Release before running them.

## Installation

For normal Windows installation, download the `IndustrialClassic-Launcher-Setup`
file from the latest approved release. The Launcher creates an isolated game
directory and uses the official Minecraft Launcher for Microsoft authentication
and the final Play action.

Minecraft, Java, Fabric Loader and Fabric API remain subject to their own terms.
The dedicated-server package does not redistribute them.

## Support and security

Report distribution or Launcher problems through this repository's
[Issues](https://github.com/ZombieW13/Industrial-Classic-Releases/issues).
When reporting a problem, attach only the sanitized diagnostic package exported
by the Launcher. Never publish passwords, tokens, worlds, `server.properties`,
RCON keys or other personal/server secrets.

## Português (Brasil)

Este é o canal público oficial de distribuição do IndustrialClassic. O
repositório contém somente releases, manifestos, checksums, notas e licenças;
ele não contém nem espelha o repositório privado de desenvolvimento.

O primeiro Alpha público, `A.12.0`, está em preparação. Considere uma versão
disponível somente quando ela aparecer na página
[Releases](https://github.com/ZombieW13/Industrial-Classic-Releases/releases).
Use preferencialmente o instalador `IndustrialClassic-Launcher-Setup` e confira
todo download com o arquivo `checksums.sha256` da mesma release.

O Launcher usa uma instância isolada e deixa a autenticação Microsoft e a ação
final de jogar no Minecraft Launcher oficial. Ao solicitar suporte, compartilhe
somente o diagnóstico sanitizado; nunca publique senhas, tokens, mundos,
`server.properties`, chaves RCON ou outros dados pessoais/do servidor.

## License

See [`LICENSE`](LICENSE). Each release package also includes its applicable
license scope and third-party notices. IndustrialClassic artwork, audio, visual
identity and trademarks are not granted by the Apache License 2.0 unless an
asset explicitly states otherwise.
