# Temporary transfer: KoL Worker agent reference bundle

This repository is being used as a temporary transfer point for Socel.

The original uploaded archive is **kol-worker-agent-reference-bundle(1).zip**.

Because the GitHub connector available in this session can only write UTF-8 text files, the ZIP is stored losslessly as base64 text parts. After cloning, reconstruct it with:

```bash
cat kol-worker-agent-reference-bundle.zip.b64.part-* | base64 -d > 'kol-worker-agent-reference-bundle(1).zip'
sha256sum 'kol-worker-agent-reference-bundle(1).zip'
```

Expected SHA-256:

```text
a0f3c576ceb8c933121535cdeb594465cab69b0fef2798ec1c31e48f102d99d1
```

Then unzip normally:

```bash
unzip 'kol-worker-agent-reference-bundle(1).zip'
```

This repo is intentionally temporary and can be deleted after transfer.
