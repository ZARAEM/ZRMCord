# ZRMCord

ZRMCord is a private fork of [Equicord](https://github.com/Equicord/Equicord) (itself a fork of [Vencord](https://github.com/Vendicated/Vencord)), maintained by Streets with additional userplugins and personalizations.

---

## Building from Source

### Dependencies

[Git](https://git-scm.com/download) and [Node.JS LTS](https://nodejs.dev/en/) are required.

Install `pnpm`:

> :exclamation: This next command may need to be run as admin/root depending on your system, and you may need to close and reopen your terminal for pnpm to be in your PATH.

```shell
npm i -g pnpm
```

> :exclamation: **IMPORTANT** Make sure you aren't using an admin/root terminal from here onwards. It **will** mess up your Discord/ZRMCord instance.

Clone ZRMCord:

```shell
git clone https://github.com/mearaj/ZRMCord
cd ZRMCord
```

Install dependencies:

```shell
pnpm install --frozen-lockfile
```

Build:

```shell
pnpm build
```

Inject into your desktop client:

```shell
pnpm inject
```

Build for web:

```shell
pnpm buildWeb
```

---

## Added Userplugins

These are plugins added on top of Equicord's built-in plugin set, living in `src/userplugins/`. All original authors are credited below.

| Plugin | Description | Original Source |
|--------|-------------|-----------------|
| **NitroSniper** | Automatically redeems Nitro gift links spotted in chat | [neoarz/NitroSniper](https://github.com/neoarz/NitroSniper) |
| **BoostCounts** | Right-click a server to view all boosters and their boost counts | [Reathe/BoosterCount](https://github.com/Reathe/BoosterCount) |
| **TypingFriends** | See which friends are typing anywhere — friends list section and server icon badges | [debxylen/Vencord (typingFriends)](https://github.com/debxylen/Vencord/tree/main/src/plugins/typingFriends) |
| **EmbeddedURLs** | Converts TikTok, Twitter/X, and Instagram links to embeddable proxies before sending | [ddadiani/Vencord-EmbeddedLinks](https://github.com/ddadiani/Vencord-EmbeddedLinks) |
| **StereoScreenshareAudio** | Patches WebRTC SDP to fix stereo audio while watching streams on Vesktop | [nerdwave-nick/Vencord-Stereo-Fix](https://github.com/nerdwave-nick/Vencord-Stereo-Fix) |
| **KeepGifPickerOpen** | Prevents the GIF picker from closing after sending a GIF | [pacxwheaa/KeepGifPickerOpen](https://github.com/pacxwheaa/KeepGifPickerOpen) |
| **CrashHandlerEnhanced** | Advanced crash recovery with memory monitoring, detailed logging, and statistics | [Mifu999/Equicord-Userplugins](https://github.com/Mifu999/Equicord-Userplugins/tree/main/userplugins/crashHandlerEnhanced) |
| **CustomStreamTopQ** | Replace stream preview thumbnails with custom images, supports profiles and slideshows | [MrTopQ/customStream-Vencord](https://github.com/MrTopQ/customStream-Vencord) |
| **FakeDeafen** | Adds a button to fake-deafen yourself in voice channels | [hyyven/Vencord-FakeDeafen](https://github.com/hyyven/Vencord-FakeDeafen) |
| **DiscordLock** | Password-locks Discord on startup, inactivity, or when entering specific servers/channels/DMs | [vejcowski/DiscordLock](https://github.com/vejcowski/DiscordLock) |
| **OpSec** | AI-powered grammar autocorrect using Claude (optional API key), with regex fallback | [1nject-s-Vencord-Plugins/OpSec](https://github.com/1nject-s-Vencord-Plugins/OpSec) |
| **vAnalyzer** | Security scanner — analyzes URLs and files in messages using VirusTotal, FishFish, and more | [nay-cat/vAnalyzer](https://github.com/nay-cat/vAnalyzer) |

---

## Credits

- [Vendicated](https://github.com/Vendicated) for creating [Vencord](https://github.com/Vendicated/Vencord)
- [Equicord](https://github.com/Equicord/Equicord) team for the upstream fork this is based on
- [verticalsync](https://github.com/verticalsync) for [Suncord](https://github.com/verticalsync/Suncord)
- All original plugin authors listed in the table above

---

## Disclaimer

Discord is a trademark of Discord Inc., mentioned here solely for descriptive purposes.
Client modifications are against Discord's Terms of Service. Use at your own risk.

<details>
<summary>More on ToS</summary>

Discord is generally indifferent toward client mods and there are no known cases of bans for personal use. However, if your account is critical to you, consider the risk before using any client mod.

Do not use plugins that automate abusive behavior or violate platform rules beyond personal customization.

</details>
