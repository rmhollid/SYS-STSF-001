# SYS-STSF-001

Official repository for the STSF source system.

## Repository state

**PRE-IMPORT**

The canonical STSF source package has not yet been imported into this repository. This repository is prepared to receive a verified source archive without rewriting its authoritative contents.

No STSF compliance claim is made by this repository scaffold.

## Access and licensing

STSF is intended to remain publicly accessible and useful for personal, educational, research, evaluation, and other noncommercial purposes.

**Commercial use is not granted by the public license. Commercial use requires a separate paid written license from the applicable STSF rights holder.**

See [LICENSE.md](LICENSE.md) and [COMMERCIAL-LICENSING.md](COMMERCIAL-LICENSING.md).

This repository is therefore source-available under a noncommercial-use model; the presence of public source does not imply unrestricted commercial-use rights.

## Authority boundary

Repository-maintenance files under `.github/`, along with `.gitignore`, `.gitattributes`, and repository policy documents are stewardship surfaces only. They do not define, replace, extend, or override STSF authority.

After import, authoritative source-system content is determined by the verified package itself, including its STD, PRG, SPL, source-system binding, manifests, and operator entry surfaces.

## Import gate

Before a source archive is accepted:

1. Verify the archive against its supplied SHA-256 sidecar.
2. Inspect archive paths before extraction.
3. Reject unsafe path traversal or special-file entries.
4. Preserve source bytes and filenames during intake.
5. Validate source-system bindings and required authority containers.
6. Record the imported package version and digest.
7. Run repository checks before treating the import as accepted.

The public-facing repository description will be updated after the verified source package is imported.
