# Trainlock downloads

Windows installers for Trainlock, an independent training service for Deadlock.
This repository contains release files and installation notes. Application source
code is maintained separately. Trainlock is not affiliated with Valve.

[Download the Windows preview](https://github.com/WhatuWannaDo/trainlock-downloads/releases/download/v0.1.0-preview.1/Trainlock-Setup.exe)

## Windows preview

- Windows 10/11 x64 and Deadlock installed through Steam are required.
- Run `Trainlock-Setup.exe`. No administrator rights are required.
- Setup registers `trainlock://` website links immediately. A manual first app
  launch is not required for registration.
- The app opens in the system tray. Keep it running during training.
- Exit from the tray to stop the session. Close it before updating or uninstalling.
- Installation and removal preserve personal settings, recordings and the
  separately prepared game runtime.

This is an unsigned local preview, tested against Deadlock build 6839. Cloud
website pairing and automatic updates are not included yet. Internal game updates
may require a newer training module. Release assets include SHA-256 checksums;
checksums verify file integrity and are not a publisher signature.

Use the Releases section for version notes and files. Prerelease downloads use
explicit version links; GitHub's `latest` link excludes prereleases.