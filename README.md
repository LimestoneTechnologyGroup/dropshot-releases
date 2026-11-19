# Dropshot downloads

Windows screenshots that go straight where you want them: a Teams channel, Claude, an email or a folder.

- **Download page:** https://limestonetechnologygroup.github.io/dropshot-releases/
- **Latest exe:** https://github.com/LimestoneTechnologyGroup/dropshot-releases/releases/latest/download/Dropshot.exe

This repo holds released builds and the download page. Dropshot 1.10.x and earlier update themselves
from its latest release. From 1.11.0, Dropshot is signed by Limestone Technology Group, LLC, is
released from the `dropshot` repository's GitHub Actions to `downloads.limestonetg.com`, and updates
from there. Releases here are copies of those production files, made by **Actions > Mirror a
release**, so that older copies can reach the signed version. The mirror verifies each file's
hashes and signature before publishing it, and stops once older copies have moved over.

Silent per-user install for IT: `Dropshot.exe --install --quiet` (add `--no-start` to skip launching it).
Silent uninstall: `"%LOCALAPPDATA%\Programs\Dropshot\Dropshot.exe" --uninstall --quiet`.
