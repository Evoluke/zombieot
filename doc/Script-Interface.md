# Script Interface Documentation

This repository is meant to include a local copy of the "Script Interface"
article that lives on the Forgotten Server wiki:

<https://github.com/otland/forgottenserver/wiki/Script-Interface>

At the time of this update, the CI environment running this command could not
access GitHub wikis through the corporate proxy (all HTTPS CONNECT requests are
blocked with a `403 Forbidden` response). Because of that restriction the raw
wiki markdown could not be downloaded automatically.

To refresh this document when network access is available, execute:

```bash
git clone https://github.com/otland/forgottenserver.wiki.git
cp forgottenserver.wiki/Script-Interface.md doc/Script-Interface.md
```

Please open an issue if the network restriction is lifted so that the full wiki
content can be mirrored locally.
