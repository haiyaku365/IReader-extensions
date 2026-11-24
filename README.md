# Custom extension repo

This folder is a ready-to-publish IReader extension repo containing only the fixed
Novel Fire v2.12 extension. No compilation is needed.

## Files

```
index.min.json
apk/ireader-en-novelfire-v2.12.apk
icon/ireader-en-novelfire-v2.12.png
```

## Publishing

Create a `repov2` branch in your extension-repo fork that contains these three files
at the repository root, then add the corresponding raw `index.min.json` URL in
IReader under Sources → Extensions → Add repository.

The repo will be shown as UNTRUSTED because it is a third-party repository. That is
expected.
