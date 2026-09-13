# NeuroTendrils — downloads

Builds for every NeuroTendrils application. Each one is published
automatically from its own repository when a version tag is pushed, so what
you download here is built from tagged source, not uploaded by hand.

---

## NeuroTendrils Suite

Local-first EEG research environment. Import, inspect, and process recordings
with a full provenance record of every decision. Your data never leaves the
machine.

**[Download the latest release →](https://github.com/NeuroTendrils/suite/releases/latest)**

| Platform | File |
|---|---|
| Windows 10/11 | `.msi` |
| macOS 12+ | `.dmg` |
| Linux | `.AppImage` or `.deb` |

Requires roughly 4 GB of RAM and 2 GB of disk. Nothing else — no account, no
network connection, no cloud service.

---

## NeuroLearn

Interactive brain–computer interface literacy. Short lessons with simulations
you actually operate rather than watch.

**[Download the latest release →](https://github.com/NeuroTendrils/neurolearn/releases/latest)**

| Platform | File |
|---|---|
| Android 8+ | `app-release.apk` |
| Web | `neurolearn-web.tar.gz` — serve the extracted folder from any static host |

iOS builds are not published yet; they require an Apple Developer account.

To install the APK directly you will need to allow installation from unknown
sources on your device. That is a normal Android prompt for any app not
distributed through the Play Store.

---

## Current status

Everything here is a **pre-release**. That is a deliberate label, not an
oversight:

- The Suite's lineage ribbon and batch runner are built and tested, but not
  yet wired into the main window, so they are not visible in the running app.
- NeuroLearn ships one simulation. Three more are specified and unbuilt.
- Neither has been through an external security review.

Useful for evaluation, early feedback, and non-critical work. Do not treat
either as production software yet.

---

## Reporting problems

Open an issue on the repository the build came from:

- Suite → [github.com/NeuroTendrils/suite/issues](https://github.com/NeuroTendrils/suite/issues)
- NeuroLearn → [github.com/NeuroTendrils/neurolearn/issues](https://github.com/NeuroTendrils/neurolearn/issues)

Include your operating system, the version you downloaded, and what you were
doing when it went wrong. If the Suite is involved, the log path is shown in
Settings → Diagnostics.

---

## Licensing

The Suite is proprietary. NeuroLearn and NeuroFlow are AGPL-3.0-or-later. See
the LICENSE file in each repository.
