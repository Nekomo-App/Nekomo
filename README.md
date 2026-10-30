<div align="center">

<img src="assets/logo.png" alt="Nekomo logo" width="160" height="160" />

# Nekomo

### 猫も &nbsp;·&nbsp; *Cat too.*

**A community-driven anime & manga client for Android and Android TV — you bring the sources.**

[![Platform](https://img.shields.io/badge/Platform-Android%207.0%2B%20%7C%20Android%20TV-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Nekomo-App/Nekomo/releases)
[![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://github.com/Nekomo-App/neko-source)
[![License](https://img.shields.io/badge/License-GPL--3.0-e5395f?style=for-the-badge&logo=gnu&logoColor=white)](https://github.com/Nekomo-App/neko-source/blob/main/COPYING)
[![Stars](https://img.shields.io/github/stars/Nekomo-App/Nekomo?style=for-the-badge&logo=github&color=f5c542)](https://github.com/Nekomo-App/Nekomo/stargazers)

<p>
  <a href="https://nekomoapp.netlify.app"><b>🌍 Website</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/Nekomo-App/Nekomo/releases"><b>📦 Download</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/Nekomo-App/neko-source"><b>💻 Source</b></a> &nbsp;·&nbsp;
  <a href="https://discord.com/invite/E4Ezmgg7Ka"><b>💬 Discord</b></a> &nbsp;·&nbsp;
  <a href="https://t.me/nekomoapp"><b>✈️ Telegram</b></a>
</p>

</div>

> [!IMPORTANT]
> Nekomo **does not host, include or provide any content**, and it ships with **no sources, repositories or extensions**.
> You add and install everything yourself. Please read the [DMCA & Legal Disclaimer](#️-dmca--legal-disclaimer) before using, distributing or contributing.

---

## ✨ About

Nekomo is an Android and Android TV app built with Kotlin. It started from the legacy **Kuro No** and **Shiro** projects and has since been rebuilt around one idea: a polished tracker and player shell where **you choose your own sources**.

It combines anime discovery, list tracking and a manga reader with a plugin system compatible with the most popular community extension formats.

## 🚀 Features

| | Feature | Details |
|---|---|---|
| 🎌 | **Tracking** | AniList, MyAnimeList and Kitsu sign-in and list sync. AniList is also the metadata catalogue |
| 🧩 | **Bring your own sources** | CloudStream (`.cs3`), Zangetsu (JavaScript), Aniyomi (anime APKs) and Mihon (manga APKs) |
| 🔀 | **Source chooser** | Pick, per title, which of your installed sources to search and play from |
| � | **Manga reader** | Browse, read and page through chapters from Mihon sources |
| 📚 | **Library** | Watchlists, bookmarks, subscriptions and recently watched |
| 📥 | **Downloads** | Offline viewing |
| 📱 | **Phone + Android TV** | One codebase, D-pad friendly TV UI. Stable, Beta and Debug channels |
| 🔄 | **Auto updates** | Built-in updater that follows GitHub releases (stable or pre-release channel) |
| 🎛️ | **Content filters** | "Movies & TV shows" and "18+ content" switches, both **off** by default (18+ asks you to confirm your age) |
| 🔒 | **Privacy** | Optional DNS-over-HTTPS, login tokens stored on-device only, no analytics |
| 🪵 | **Error log** | Persistent in-app error log with one-tap GitHub issue reporting |

<sub>Nekomo is not affiliated with or endorsed by AniList, MyAnimeList, Kitsu, TMDb, CloudStream, Aniyomi, Mihon, Zangetsu or any other third-party service.</sub>

## 📥 Download

<div align="center">

[![Download](https://img.shields.io/badge/Download-Latest%20Release-e5395f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nekomo-App/Nekomo/releases)
&nbsp;
[![Website](https://img.shields.io/badge/Website-nekomoapp.netlify.app-ff5c7a?style=for-the-badge&logo=netlify&logoColor=white)](https://nekomoapp.netlify.app)

</div>

| Channel | Package | Who it is for |
|---|---|---|
| **Stable** | `app.nekomo` / `app.nekomo.tv` | Everyone. The reliable build |
| **Beta** | `app.nekomo.beta` / `app.nekomo.tv.beta` | Early access to new features |
| **Debug** | `app.nekomo.debug` / `app.nekomo.tv.debug` | Testers and bug reports (verbose, larger) |

Each channel is a separate app, so you can install more than one side by side. Files are named `Nekomo-<phone|tv>-<release|beta|debug>.apk`, and each build only updates to its own APK.
**Requires Android 7.0 (API 24) or newer.** The TV build also installs on phones for testing.

## 🧭 How sources work

1. Open **Settings → Extensions**. Every list starts empty.
2. Paste the URL of a repository **you** trust (CloudStream `repo.json`, Zangetsu `index.json`, Aniyomi/Mihon `index.min.json` or `index.pb`).
3. Browse what that repository offers and install what you want. You are asked to confirm every install. A step-by-step guide is on the [website](https://nekomoapp.netlify.app/sources).
4. Installed sources appear in search and in the per-title **Choose source** menu.

Nekomo has **no built-in directory, search or one-click install** for sources, and the maintainers do not recommend, host or endorse any. Extensions run code with the app's permissions, so only install from people you trust. Each installed extension has a **Report** button that opens its author's issue tracker.

## 🌐 Official links

| | |
|---|---|
| 🌍 Website | [nekomoapp.netlify.app](https://nekomoapp.netlify.app) |
| 📦 Releases | [Nekomo-App/Nekomo/releases](https://github.com/Nekomo-App/Nekomo/releases) |
| 💻 App source | [Nekomo-App/neko-source](https://github.com/Nekomo-App/neko-source) |
| 🌐 Website source | [Nekomo-App/Nekomo-Main-Web](https://github.com/Nekomo-App/Nekomo-Main-Web) |
| ⚖️ Legal | [Terms](https://nekomoapp.netlify.app/terms) · [Privacy](https://nekomoapp.netlify.app/privacy) · [DMCA](https://nekomoapp.netlify.app/dmca) · [Support](https://nekomoapp.netlify.app/support) |
| 🐛 Bug reports | [Open an issue](https://github.com/Nekomo-App/Nekomo/issues) |
| 💬 Community | [Discord](https://discord.com/invite/E4Ezmgg7Ka) · [Telegram](https://t.me/nekomoapp) |

<details>
<summary><b>Join the Nekomo Discord server</b></summary>
<br>
<div align="center">
  <a href="https://discord.com/invite/E4Ezmgg7Ka">
    <img src="https://invidget.switchblade.xyz/E4Ezmgg7Ka" alt="Join the Nekomo Discord server">
  </a>
</div>
</details>

## � What does Nekomo mean?

**猫も** (*neko mo*) reads as **"cat too"** in Japanese. It is a small nod to the project's name and its community identity.

## �🚧 Project status

Nekomo is community-maintained, without guaranteed active development. It may receive updates, be rewritten, go quiet or welcome new contributors. Contributions and community participation are welcome within the project's guidelines.

## 🤝 Contributing

Code, bug reports, testing, docs, design feedback and ideas are all welcome. Use GitHub for code and issues, and Discord for discussion.

<details>
<summary><b>📋 Project guidelines</b></summary>
<br>

- Keep the project low-key; avoid aggressive promotion outside the community.
- Non-English localization is currently unsupported.
- Major UI redesigns and changes to the project name or logo are not currently accepted.
- 18+ content is allowed but **off by default**: it only appears after a user turns on "Show 18+" and confirms they are an adult. Do not post explicit material in community spaces.
- Please discuss substantial changes with the community before starting work.

</details>

## 📜 License

Nekomo began as a fork of Shiro (MIT) and now includes GPL-3.0 components (the CloudStream API, NiceHttp, NewPipeExtractor and Zangetsu-derived code). The distributed app is therefore licensed under the **GNU GPL v3.0 or later**, and the complete corresponding source is in [neko-source](https://github.com/Nekomo-App/neko-source). The full list of libraries and licenses is in [`THIRD_PARTY_LICENSES.md`](https://github.com/Nekomo-App/neko-source/blob/main/THIRD_PARTY_LICENSES.md) and in the app under **Settings → About → Open-source licenses**.

Extensions, repositories and sources you install keep their own licenses.

## 🙏 Credits

Nekomo builds on the work of earlier projects and their contributors.

| Project | Thanks to |
|---|---|
| **Kuro No** | [Deceptions](https://github.com/deceptions) — original Kuro developer ([repo](https://github.com/deceptions/no) · [backup](https://gitee.com/deceptionss/no)) |
| **Shiro** | [MarshMeadow/shiro-app](https://github.com/MarshMeadow/shiro-app) and its original authors |
| **CloudStream** | [LagradOst, Blatzar and contributors](https://github.com/recloudstream/cloudstream) |
| **Aniyomi / Mihon** | [Aniyomi](https://github.com/aniyomiorg/aniyomi) and [Mihon](https://github.com/mihonapp/mihon) — extension API this project is compatible with |
| **Zangetsu** | [Spyou/zangetsu](https://github.com/Spyou/zangetsu) — JavaScript source format and reference bridges |
| **NewPipe** | [TeamNewPipe/NewPipeExtractor](https://github.com/TeamNewPipe/NewPipeExtractor) |

> [!CAUTION]
> The [original Kuro Discord server](https://discord.gg/YgeFkTMmxh) may have been compromised or taken over. Join at your own risk.

<details>
<summary><b>🗄️ Archived Kuro No downloads</b></summary>
<br>

| Build | Version | Download |
|---|---|---|
| 📱 Mobile | 2.2.3 | [APK](https://github.com/deceptions/no/releases/download/2.2.3/2.2.3.apk) |
| 📺 Android TV | 2.2.3 | [APK](https://github.com/deceptions/no/releases/download/2.2.3/2.2.3-TV.apk) |

</details>

<details>
<summary><b>🔄 Other apps worth a look</b></summary>
<br>

[Dantotsu](https://dantotsu.app/) · [CloudStream](https://github.com/recloudstream/cloudstream) · [Aniyomi](https://github.com/aniyomiorg/aniyomi) · [Mihon](https://github.com/mihonapp/mihon) · [Miru](https://github.com/miru-project/miru) · [Anilab](https://anilab.to/)

</details>

## ⭐ Support the project

If Nekomo is useful to you, a star helps others find it.

<div align="center">

[![Star Nekomo](https://img.shields.io/badge/⭐%20Star%20Nekomo-on%20GitHub-f5c542?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nekomo-App/Nekomo/stargazers)

<details>
<summary><b>📈 Star history</b></summary>
<br>
<a href="https://star-history.com/#Nekomo-App/Nekomo&Date">
  <img src="https://api.star-history.com/svg?repos=Nekomo-App/Nekomo&type=Date" alt="Star history chart">
</a>
</details>

</div>

## ⚖️ DMCA & Legal Disclaimer

<details>
<summary><b>Read the full legal disclaimer</b></summary>
<br>

**Application and content**
- Nekomo is an open-source application. It does not host, store, upload, distribute or provide media content.
- Nekomo does not include, recommend, operate or control any source, repository, extension, streaming server or content provider. Users add and install these themselves.
- Metadata, artwork, titles and descriptions come from third-party APIs such as AniList, MyAnimeList and Kitsu.

**Third-party services and intellectual property**
- Nekomo is not affiliated with, endorsed by or sponsored by AniList, MyAnimeList, Kitsu, TMDb, CloudStream, Aniyomi, Mihon, Zangetsu or any other company, service or trademark owner unless explicitly stated.
- All trademarks, copyrights, logos, names and media belong to their respective owners.

**User responsibility**
- Users are solely responsible for what they install and use, and must comply with all applicable local, national and international laws and the terms of the services they access.
- Developers, contributors, maintainers and community members are not responsible for how third parties use the application.

**Copyright and takedown requests**
- If you believe content infringes your rights, contact the service, source, provider or website hosting it. Nekomo cannot remove content it does not host, own, control or distribute. See the [DMCA page](https://nekomoapp.netlify.app/dmca).

**Distribution and app stores**
- Do not upload Nekomo, Kuro No, Shiro or any fork to Google Play or another app store without ensuring compliance with the platform's terms and applicable law.

By using Nekomo, you acknowledge that you are responsible for your use of the software.

</details>

---

<div align="center">

<img src="assets/logo.png" alt="Nekomo logo" width="72" height="72" />

**猫も · Nekomo — Cat too. Built by the community.**

[Website](https://nekomoapp.netlify.app) · [GitHub](https://github.com/Nekomo-App) · [Discord](https://discord.com/invite/E4Ezmgg7Ka) · [Telegram](https://t.me/nekomoapp)

<sub>Community-driven · Android · Android TV</sub>

</div>

> **Nekomo is in beta/alpha.** The latest build is [v2.9.0 (pre-release)](https://github.com/Nekomo-App/Nekomo/releases/tag/v2.9.0). The same APKs and `latest.json` are kept in the [`apks`](apks) folder here and in [Neko-Source](https://github.com/Nekomo-App/Neko-Source/tree/main/apks).

## Which build should I download?

| Channel | Phone app | Android TV app |
|---|---|---|
| Stable | `Nekomo-phone-release.apk` (`app.nekomo`) | `Nekomo-TV-release.apk` (`app.nekomo.tv`) |
| Beta | `Nekomo-phone-beta.apk` (`app.nekomo.beta`) | `Nekomo-TV-beta.apk` (`app.nekomo.tv.beta`) |
| Alpha (debug) | `Nekomo-phone-alpha.apk` (`app.nekomo.debug`) | `Nekomo-TV-alpha.apk` (`app.nekomo.tv.debug`) |

Every Android TV build has **TV** in its app name and file name. Channels install side by side because they use different package names. Requires Android 7.0 or newer. The TV APKs can also be installed on a phone for testing.

## Highlights

- **Details for every title:** poster, banner, synopsis, genres, rating, season, studio, release date, episodes and an in-app **trailer** (built-in player with play/pause).
- **Metadata is separate from streaming:** titles opened through an installed extension are completed from the built-in catalogue, so incomplete extension data no longer leaves blank pages.
- **Backup metadata APIs** and a stale-page cache, so details still open when one service is down.
- **Sources dropdown** on every title: your default source first, other installed sources as alternatives, a clear message when none match.
- **Tracker mode:** with no sources installed you can still search, save to an offline library, track episodes and sync to AniList later.
- **Playback:** pop-out (picture-in-picture), external players, subtitles, and clear errors instead of endless spinners.
- **Home customization:** choose metadata providers, official link-out rows and sections, and reorder them.
- **Privacy:** incognito mode, an off-by-default 18+ switch with optional device lock, and movies/TV shows off by default.
- **Loading and error screens** when opening a title, with Try again / Go back.

## The optional Nekomo repository and the Extensions manager

Nekomo ships with no sources installed. Open **Settings > Extensions** to reach the Extensions manager, one place for:

- **Repositories and sources:** CloudStream plugins (`.cs3`) and Zangetsu scripts (`.js`). Enable, disable, update, uninstall, view details and per-provider switches.
- **Metadata APIs (built in):** AniList (main), Kitsu, MyAnimeList via Jikan, TVMaze and TMDB (needs your own key). Backups switch on automatically when the main API is down or rate-limited.
- **Automatic updates:** on or off, frequency (6 hours to 7 days), manual check, update all or one by one, and an update history that records every install, update, removal and error. A failed update keeps the previous version.
- **APK extensions (Aniyomi, Mihon):** listed separately. Nekomo never downloads, installs or updates these automatically; you install them yourself.

An **optional official repository** (free and legal sources only) can be added from the same screen with a repository URL or code. Nothing is installed until you add it and confirm the third-party-code warning, and you can remove it, with the sources it installed, at any time. Any other repository can be added manually by URL; Nekomo does not host or vouch for those.

## Project links

- Website: https://nekomoapp.netlify.app ([screenshots](https://nekomoapp.netlify.app/gallery), [sources guide](https://nekomoapp.netlify.app/sources))
- App: [Nekomo](https://github.com/Nekomo-App/Nekomo) and its code in [Neko-Source](https://github.com/Nekomo-App/Neko-Source)
- Docs: [Nekomo-Docs](https://github.com/Nekomo-App/Nekomo-Docs) and [Nekomo-Extensions](https://github.com/Nekomo-App/Nekomo-Extensions)
- Website source: [Nekomo-Main-Web](https://github.com/Nekomo-App/Nekomo-Main-Web)
- Legal: [Nekomo-DMCA](https://github.com/Nekomo-App/Nekomo-DMCA)
- Companion app: [NEX](https://github.com/Nekomo-App/NEX) (Nekomo Extension Exchange), a manager for repositories and extensions across Nekomo, Mihon, Aniyomi, CloudStream and Zangetsu
- Brand: [Nekomo-Branding](https://github.com/Nekomo-App/Nekomo-Branding)
- Fun: [Neko-Run](https://github.com/Nekomo-App/Neko-Run) (the pixel cat game on the website's 404 page)
- History: [OG-Kuro-No-Source](https://github.com/Nekomo-App/OG-Kuro-No-Source) (archive) and [Nekomo-Web](https://github.com/Nekomo-App/Nekomo-Web) (retired)
