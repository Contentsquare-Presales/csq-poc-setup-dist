# Mobile POC/POT Setup Tool

A one-command tool for Solutions Consultants that builds all the Contentsquare
Console projects a **mobile POC/POT** needs — and switches on every feature flag
required to showcase the SDK (Session Replay, Heatmaps, Crash Reporting, error
tracking, and more). Setup goes from an afternoon to a couple of minutes.

## 📖 Full guide

👉 **[Read the how-to guide](https://contentsquare-presales.github.io/csq-xp-setup-dist/)**
— what it does, how to get your login token, and how to run it.

## ⬇️ Download

**[Download the latest version](https://github.com/Contentsquare-Presales/csq-xp-setup-dist/releases/latest/download/csq-xp-setup)**
— a single file for macOS (Apple Silicon). Then:

```bash
xattr -c csq-xp-setup
chmod +x csq-xp-setup
sudo mv csq-xp-setup /usr/local/bin/
```

If macOS says **"Apple could not verify…"**, the `xattr -c` line clears the
download quarantine so it runs (already installed? `sudo xattr -c /usr/local/bin/csq-xp-setup`).
GUI alternative: **System Settings → Privacy & Security → Open Anyway**.

See [all releases](https://github.com/Contentsquare-Presales/csq-xp-setup-dist/releases).

---

*This repository hosts the documentation and downloads only. Questions or
feedback: **[add your Slack channel / contact here]**.*
