<img src="image/xvrf-title-icon.png"/> May the XVRF with you

[🔙](README.md) | `User's Manual` | [`Controls`](controls.md) | ~`History`~ | ~`Debug Tools`~ | `English (N/A)` | [`Japanese`](ja/manual.md)

----

# XVRF (working title) | User's Manual (priliminary)

* Although this software is a form of game, please think of it as a prototype (early access) still under development.
* I'm hoping you enjoy as an app with your favorite VRM characters moving around.
* I will update this work and descriptions as often as possible.

* ☛ [XVRF Dowload Site](https://xelf.booth.pm/items/1341365)

## 💻 Recommended System Requirements

| |Recommended Specifications|
|----|----|
|Operating System|Windows 10 64-bit|
|Video|DirectX 11 or later|
|Memory|4GB RAM|
|Storage|25GB available space|
|Broadband Internet connection|✅ (as currently planned)|

> only as a guide

# How to start

1. Unzip all files in the zip file. (first time after download)
2. Open the `XVRF.exe` in the unzipped folder.

> * About protections by the Operating System `Windows 10` and/or anti-virus softwares, please treat with generic ways.
> * For update versions, download it again, and do same way to start 🙇

## About `Expilation`

* As the **early access version**, an expiration date is set for each version.
* The expiration date of the version ends when the expiration date `Expilation` at the bottom of the screen is reached.
When start after the expiration date, a message containing the phrase `Expired on` will be displayed.
Please look for the latest version on [XVRF Download Site](https://xelf.booth.pm/items/1341365).

> * Display is in UTC (Coordinated Universal Time).
> * Treatment of future expiration dates are undecided.

# `🏠Lobby`

> This page contains `not translated`: Please also refer to the [`Japanese`](ja/manual.md) edition using machine translation etc. 🙇

* After launching the game, you will see the `🏠Lobby`.

> Please note that pictograms described here and in-game icons will look different.

|||
|---|---|
|`Quit`|Quit the game. (with Confirmation)|
|||
|`👤🆚🤖`| Start as Single Player (Player versus AI)|
|`🤖🆚🤖`| Start demo as AI versus AI.|
|`Enable to start from URL`|If you enable this feature, you can launch XVRF on your Windows from the link `▶️XVRF` on the page https://xelfia.github.io/XVRF-Outpost/. Usually, there is security confirmation by Windows. If you proceed, launch the secondary game app (with the Unity logo) and close it shortly. If `Succeeded` is displayed in the primary game app, it has been successfully enabled.|
|`👤Character Selection`| Move to Character selection screen. (See below)|
|`Discord`|(Provisional exposed. Under considering to describe in the future.)|
|`Web`| Open the [Offical Web Site](README.md).|
|`📜Report`| Report form for this software behavior. If there is no problem with the content, you can `Send`. If this is not available and let me know by other contact methods.|
|`⚙Settings`|Open the Settings screen. (See below)|

# `⚙Settings`

|||
|---|---|
|`Back`|Back to the previous screen.|
|||
|`Audio`|Master volume can be adjusted by slider.|
|`Music`|Music volume can be adjusted by slider.|
|`Sound Effect`|Sound Effect volume can be adjusted by slider.|
|`AI Level`|AI's capability can be adjusted by slider. In the current versions, it is simply involved in the percentage of guard actions.|
|`Active Camera`|When ☑, the camera moves around the subject.|
|`Debug Tools`|When ☑, Debug tools related UI are displayed. (See below)|
|`Move by Mouse`|When ☑, The relative movement of the mouse pointer corresponds to the movement input (equivalent to the L-stick on the gamepad 🎮).|

> * Each setting is saved when you change it.

# `Escape Menu`

In the combat screen as `👤🆚🤖` (Single play), input 🔙 to display the `Escape Menu`.

|||
|---|---|
|`Continue▶`|Back to the combat screen and continue.|
|||
|`AI Level`|AI's capability can be adjusted by slider. In the current versions, it is simply involved in the percentage of guard actions.|
|`👤Character Selection`|Open the `👤Character Selection`.|
|`🏠Lobby`|Back to `🏠Lobby`.|

> * Currently, combat does not pause. 

# Debug Tools

I have added features that can be used effectively by creative people such as VRM authors.

☛ `English (N/A)` [`Japanese`](ja/debug.md)

# Way to select a character / `👤Character Selection`

* Bundled character is one. `Reference` ☛ [`VRoid Hub` ᚡᛆᛚᚴᚤᚱᛄᛆ](https://hub.vroid.com/characters/5500341240985797385/)

> Bundles may be changed.

* Other characters are available in the following ways.

> Unexpected behavior may occur with not bundled characters.
> [VRoid Studio](https://studio.vroid.com/) characters with a standard design work as it is.
> What character is a good behavior, or would fit into the world, or funny, or will be an interesting behavior.
> Please share your experiment on social media etc. ☺

## Controls on `👤Character Selection` screen

|||
|---|---|
|`Back`|Back to the previous screen.|
|||
|`P1`|When ☑, after selecting the character, it applies to player 1 `P1` (or AI 1 `A1`).|
|`P2`|When ☑, after selecting the character, it applies to player 2 `P2` (or AI 2 `A2`).|
|`Select VRM`|Model name of the selected character is displayed here.|
|`Author`|Author name of the selected character is displayed here.|
|`Open Folder`|Open the local VRM Folder📁. (See below)|
|`⟳`|Reloads the list of character models.|
|`⚙`|VRoid Hub can be `Link`ed or `Unlink`ed. (See below)|
|`Local`|Enable/Disable the local VRM files. (See below)|
|`VRoid Hub`|Enable/Disable your `VRoid Hub` character models. (See below)|
|`VRoid Hub💛`|Enable/Disable your favorite `VRoid Hub` character models. (See below)|
|`VRoid Hub★`|Enable/Disable the recommended `VRoid Hub` character models. (See below)|

> * If you do `VRoid Hub` related operations without `VRoid Hub Link`, it will be the screen of `VRoid Hub Link` as well as `⚙`.
> * The recommended character models are fixed in the game side and are subject to change without notice.

## Way to select a character

* First, please confirm (set) the state ☑ or ☐ of `P1` and `P2`.
* Depending on the filters at the almost bottom of the screen, character model icons will be displayed at the abeve.

> * If not applicable, it will be blank.
> * If 🛇 is displyed, it can not be used because it does not meet the conditions of use.

* Once a character model icon is selected, its descriptions are displayed on the screen.
* With the character model icon is selected, select it again to determine to use that character.
* `Loading...` after a while and combat starts.

> * If there is any problem with the compatibility between XVRF and the selected chartacter model, unusual behavior may occur during or after `Loading...`.
> * Please let me know if there is a posslbility of new discorveries☺

## Link to VRoid Hub

1. In the game `👤Character Selection`, press `⚙`.
2. Web browser will automatically open and display the `VRoid Hub` authorization code.
3. `Copy` the Authorization code in that page.
4. The authorization code is automatically pasted on the game screen.
> If you can not enter the authorization code, please contact me (XVRF side) because there is a possibility of specification change etc.

5. Once you have confirmed that the authorization code is pasted, press `Link`.
6. If it `Succeeded`, go to the next step.

> If it `Failed. Please retry.`, Check the input content / internect connection / service running status etc and retry.

## Play with character model on VRoid Hub

1. After linking, let's search your favorite character in [VRoid Hub](https://hub.vroid.com).
2. Let's press ♡ in that page.
> * In XVRF, characters are only available for `Violence: YES` under the conditions of use.

3. In the game `👤Character Selection`, press `VRoid Hub` to turn it into ☑.
4. You will surely find the character and you can play with it.

## Play with your character model on VRoid Hub

1. After linking, in the game `👤Character Selection`, press `VRoid Hub` to turn it into ☑.
2. You will surely find the character and you can play with it.

> * In XVRF, characters are only available for `Violence: YES` under the conditions of use.
> * If it does not work better than the bundled or standard characters, please refer:
> ☛ `Japanese` [XVRF Model Definitions / XVRFで良く動くVRMのために](https://scrapbox.io/XVRF/XVRF_Model_Definitions_%2F_XVRF%E3%81%A7%E8%89%AF%E3%81%8F%E5%8B%95%E3%81%8FVRM%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AB)

## Play with local VRM files

You can also use your self-made VRM files or others-made VRM files that meet the conditions.

> ☛ [About VRM](https://vrm-consortium.org/#vrm) in `Japanese`

1. In the `👤Character Selection` screen, press `Open Folder` to open the folder📁 of the following format.
  * `≪drive_letter≫:\Users\≪user_name≫\Documents\VRM`
2. Place VRM files into this folder📁.
3. In-game `👤Character Selection` screen, press `Local` to turn it into ☑.
4. You will surely find the character and you can play with it.

> * In XVRF, characters are only available for `Violence: YES` under the conditions of use.
> * If it does not work better than the bundled or standard characters, please refer:
> ☛ `Japanese` [XVRF Model Definitions / XVRFで良く動くVRMのために](https://scrapbox.io/XVRF/XVRF_Model_Definitions_%2F_XVRF%E3%81%A7%E8%89%AF%E3%81%8F%E5%8B%95%E3%81%8FVRM%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AB)

## ⚠Known Issues

`not translated`

## ✒Update Logs

☛ `English (N/A)` | [`Japanese`](ja/history.md)

## 🎮Controls and Input Devices

☛ [`English`](controls.md) | [`Japanese`](ja/controls.md)

## 📧Contacts

* recommended Twitter hashtag (priliminary): `#XVRF`
* ☛ [xelfia@twitter.com](https://twitter.com/xelfia)
* [License](LICENSE.md)

--------
🆇🅴🅻🅵
©2018-2019 XELF
