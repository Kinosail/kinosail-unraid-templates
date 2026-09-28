# Kinosail templates for Unraid Community Apps

This repository holds the Kinosail Player and Kinosail Subtitles container templates for Unraid. It contains no application code. The templates are MIT licensed. Kinosail application images and source remain under the [PolyForm Perimeter License 1.0.1](https://github.com/Kinosail/kinosail/blob/main/LICENSING.md).

Choose a template in Community Apps when these listings are approved. Until then, download the XML file into `/boot/config/plugins/dockerMan/templates-user/` and select it in **Docker → Add Container**.

The installer asks for an existing media share. Player needs read access. Subtitles needs write access. Both apps run as UID/GID 10001. Give this account the required access to your media and appdata paths.

To install both as one project, use the [Kinosail Compose helper](https://kinosail.com/getting-started/platforms/) with an Unraid Compose manager.

For help, open an issue in the [Kinosail repository](https://github.com/Kinosail/kinosail/issues).
