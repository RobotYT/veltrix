<div align="center">

# ⚡ VELTRIX

**A fast, native Minecraft: Java Edition launcher.**

No Electron. No bloat. Starts in about a second.

[Download](../../releases/latest) · [Features](#features) · [FAQ](#faq)

</div>

---

## What is Veltrix?

Veltrix is a free, lightweight launcher for Minecraft: Java Edition built with native .NET — not a web app in a window. It manages your versions, mods, skins and accounts in one sleek dark-crimson interface, and launches the game through the official Mojang and Microsoft services.

Veltrix **requires a Microsoft account that owns Minecraft: Java Edition**. It does not and will not bypass game ownership.

## Features

- **Every Minecraft version** — releases, snapshots, betas and alphas straight from Mojang's official version manifest, installed on demand with verified downloads
- **Microsoft sign-in** — the official device-code login flow; multiple accounts with instant switching; tokens encrypted at rest
- **Skin studio** — a skin library with a live rotating 3D preview, PNG upload, and one-click apply through the official Minecraft profile API
- **Mod manager** — browse and install Fabric mods from Modrinth, drag-and-drop your own .jar files, switch between mod profiles
- **One-click FPS boost** — installs the proven optimization pack (Sodium, Lithium, FerriteCore and friends) matched to your game version
- **Cosmetics** — free launcher-side capes and hats with live 3D preview
- **Smart Java handling** — detects installed Java and auto-downloads the right Temurin runtime per Minecraft version
- **Quality of life** — RAM slider, JVM arguments, resolution control, Discord Rich Presence, automatic launcher updates

## Download

Grab the latest `Veltrix.exe` from the [Releases page](../../releases/latest). Self-contained — no .NET installation required.

| Platform | Status |
|---|---|
| Windows 10/11 (x64) | ✅ Available |
| Linux | 🔜 Planned |
| macOS | 🔜 Planned |

## FAQ

**Is Veltrix free?**
Yes, completely.

**Do I need to own Minecraft?**
Yes. Veltrix signs you in with your Microsoft account and verifies ownership through the official Minecraft services — exactly like the vanilla launcher.

**Is my account safe?**
Sign-in happens directly between you and Microsoft (you enter a code on microsoft.com). Veltrix never sees your password, and session tokens are stored encrypted on your own machine. Nothing is sent to third-party servers.

**Where does Veltrix store its files?**
`%AppData%\Veltrix` — game files, mods, skins and logs all live there.

**Can I add my own mods?**
Yes — drop any Fabric .jar onto the Mods page, or install straight from Modrinth inside the launcher.

## Contact

Questions, bug reports or feedback: open an [issue](../../issues) on this repository.

---

<div align="center">
<sub>Veltrix is not affiliated with Mojang Studios or Microsoft.</sub>
</div>
