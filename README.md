# Attache downloads

Built installers for [Attache](https://attache-cloud-production.up.railway.app).
This repository holds releases only -- no source.

## Latest

**Attache 0.2.1 for Windows 10/11 (64-bit) -- 1.8 GB**

[Download](https://github.com/lennycruzsantiago-afk/attache-downloads/releases/download/v0.2.1/Attache-Setup-0.2.1.exe)

The assistant model is inside the download, so Attache answers questions as
soon as it finishes installing: no account, no API key, and no separate
Ollama install. It needs about 2.2 GB on disk and roughly 3 GB of free RAM
while answering.

SHA-256

```
6c4dfa9127ab52fe8efd5ef491d6a4113b1fec7e0d718a93eb17f7c335ee7417
```

Windows will warn before running it -- the build is not code-signed yet.
Choose **More info**, then **Run anyway**.

### Bundled third-party software

| Component | Licence |
|---|---|
| [Ollama](https://github.com/ollama/ollama) | MIT |
| [Qwen2.5 3B Instruct](https://huggingface.co/Qwen/Qwen2.5-3B-Instruct) | Apache 2.0 |
