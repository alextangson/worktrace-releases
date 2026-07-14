# WorkTrace Releases

![WorkTrace](brand/hero-1600x1000.png)

This is the public binary distribution repository for **WorkTrace**. It contains signed installers, checksums, release notes, and reusable product images. The application source code remains in a private repository.

Official public pages:

- Product: <https://alextangson.github.io/worktrace-releases/>
- Privacy policy: <https://alextangson.github.io/worktrace-releases/privacy/>
- Support: <https://alextangson.github.io/worktrace-releases/support/>

WorkTrace turns computer activity and offline work into an evidence-backed timeline, work memory, and delivery brief—organized around the user's actual role and responsibilities.

## Downloads

Open [Releases](../../releases) to download the latest installer when the first public build is available:

- macOS: `WorkTrace-X.Y.Z.dmg`
- Windows: `WorkTrace-X.Y.Z.msix` once the Windows release reaches public beta
- Integrity: matching `.sha256` files

The macOS app will be Developer ID signed and notarized before public distribution. Windows releases will use signed MSIX packages.

## Privacy

Work data is local-first. Capture can be paused, sensitive applications can be excluded, and local screenshot retention can be disabled. See the public [privacy policy](https://alextangson.github.io/worktrace-releases/privacy/) for the current data-handling details.

## Official assets

Files under `brand/` are the approved public WorkTrace logo and project introduction images. Please do not recolor, distort, or recreate the logo.

The current public brand version is recorded in `brand/VERSION`. Verify reusable assets with `shasum -a 256 -c brand/SHA256SUMS`.

**WorkTrace — Your work, made legible.**
