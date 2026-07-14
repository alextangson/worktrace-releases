# S-tello Trace Releases

![S-tello Trace](brand/hero-1600x1000.png)

This is the public binary distribution repository for **S-tello Trace**, a work-memory and automation-diagnosis tool from S-tello. It contains signed installers, checksums, release notes, and reusable product images. The application source code remains in a private repository.

Official public pages:

- Product: <https://alextangson.github.io/worktrace-releases/>
- Privacy policy: <https://alextangson.github.io/worktrace-releases/privacy/>
- Support: <https://alextangson.github.io/worktrace-releases/support/>

S-tello Trace turns computer activity and offline work into an evidence-backed timeline, work memory, and delivery brief—organized around the user's actual role and responsibilities. It also surfaces repeated workflows and prepares evidence that a user or FDE can review before deciding whether to automate.

## Downloads

Open [Releases](../../releases) to download the latest available installer:

- macOS: `S-tello-Trace-X.Y.Z.dmg`
- Windows: `S-tello-Trace-X.Y.Z.msix` once the Windows release reaches public beta
- Integrity: matching `.sha256` files

Public macOS builds are Developer ID signed and notarized. Windows releases will use signed MSIX packages when available.

## Privacy

Work data is local-first. Capture can be paused, sensitive applications can be excluded, and local screenshot retention can be disabled. See the public [privacy policy](https://alextangson.github.io/worktrace-releases/privacy/) for current data-handling details.

## Official assets

Files under `brand/` are the approved public S-tello Trace logo and product images. Please do not recolor, distort, or recreate the logo.

The current public brand version is recorded in `brand/VERSION`. Verify reusable assets with `shasum -a 256 -c brand/SHA256SUMS`.

**S-tello Trace — Your work, made legible.**
