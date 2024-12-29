# Everest-libs
## What is it for?
This repository contains the latest libraries needed for Everest in answer to [this issue](https://github.com/EverestAPI/Everest/issues/720). In short: Everest bundled libraries are mismatched and could have been built anywhere, the purpose of this repository is to guarantee the provenance of the libs using Github Actions.

## Libraries Versions

### Open-Source Libraries
These libraries are open source and are built in CI.  

- SDL2 `2.28.5`
- SDL2_image `2.8.2`
- FNA `24.01`
- FNA3D `24.01`
- FAudio `24.01`
- Theorafile [48d74af](https://github.com/FNA-XNA/Theorafile/tree/48d74afcbf838fe95ca56cec142efae07bb56f65)
- MoltenVK `1.2.11`
- Vulkan Loader `1.3.296`
- Piton [21c7868](https://github.com/EverestAPI/Piton/tree/21c7868d06007f0c5e7d9030a0109fe892df1bf3)

### Closed-Source Libraries
These libraries are closed source and cannot be _built_ in CI.  
Some are not accessible without an account, and therefore need to be vendored as a binary blob.

- DiscordGameSDK `3.2.1` (downloaded: https://dl-game-sdk.discordapp.net/3.2.1/discord_game_sdk.zip)
- FMOD Engine `1.10.14` (vendored: [Download (Requires account)](https://www.fmod.com/download#fmodengine), [License](https://github.com/EverestAPI/Everest-libs/blob/main/binaries/fmod/EULA-FMOD.txt))
- Steamworks SDK `1.40` (with Steamworks.NET `10.0.0`) (vendored: [Download (Offical, Requires account)](https://partner.steamgames.com/downloads/list), [Download (via Steamworks.NET)](https://github.com/rlabrecque/Steamworks.NET/releases/tag/10.0.0))
