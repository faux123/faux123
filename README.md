# faux123

I build open source Vulkan drivers for Android handhelds and phones, and the tools to check what they do. I test every release on hardware I own.

## Drivers

Built from upstream Mesa and packaged for AdrenoTools. Import the `.adpkg.zip` from a release in GameNative, Winlator, or any app with an AdrenoTools driver picker. No root required.

| Driver | GPU | Tested on |
|---|---|---|
| [turnip-faux123-driver](https://github.com/faux123/turnip-faux123-driver) | Adreno 6xx, 7xx, 8xx | AYN Odin 3 (830), Retroid Pocket Duo (722), Galaxy S23 (740), S22 (730), S21+ (660), S20+ (650), S10 (640) |
| [turnip-faux123-droiddeck](https://github.com/faux123/turnip-faux123-droiddeck) | Adreno 6xx, 7xx, 8xx, for [DroidDeck](https://github.com/Droid-Deck/DroidDeck) | AYN Odin 3 (830) |
| [panvk-faux123-driver-ace](https://github.com/faux123/panvk-faux123-driver-ace) | Mali-G610 | GameForce Ace |
| [panvk-faux123-driver-rp4pro](https://github.com/faux123/panvk-faux123-driver-rp4pro) | Mali-G77 | Retroid Pocket 4 Pro |
| [panvk-faux123-driver-rg556](https://github.com/faux123/panvk-faux123-driver-rg556) | Mali-G57 | Anbernic RG556 |
| [panvk-faux123-driver-pixel7](https://github.com/faux123/panvk-faux123-driver-pixel7) | Mali-G710 | Google Pixel 7 |

The DroidDeck repository holds the same Turnip as a two-driver bundle (Android display driver plus Linux runtime driver) that DroidDeck imports in one step.

Since v1.0.0 the four PanVK repositories ship one universal Mali driver with one name: the same file, `panvk_faux123_<version>.adpkg.zip`, in all four.

Every driver and the graphics chips it runs on: [canonspike.com/drivers](https://canonspike.com/drivers/).

## Test your driver

- **[FauxVkTest](https://play.google.com/store/apps/details?id=com.faux.vktest&referrer=utm_source%3Dgithub%26utm_campaign%3Dprofile_readme)** (free, Google Play): compare a driver against your stock driver on your own device. [What it checks, in 6 minutes](https://www.youtube.com/watch?v=CpEBlNcZmwo).
- **[FauxVkDB](https://fauxvkdb.canonspike.com/?src=github)**: see how other devices score with stock and custom drivers.

## Get help and follow releases

- [r/faux123](https://www.reddit.com/r/faux123/): release posts, game reports, test results, and help.
- [FauxApps Discord](https://discord.gg/ceyPguKNbu): release news and questions.
- [YouTube](https://www.youtube.com/@faux123)
- [All FauxApps](https://fauxapps.canonspike.com/): more apps from me.
