<img src="image/xvrf-title-icon-1280x640.png" width="50%"/> May the XVRF with you

<!--[🔙](../README.md) | -->
`User's Manual` | [`Controls`](controls.md) | ~`History`~ | ~`Debug Tools`~ | `English` | [`Japanese`](ja/manual.md)

----

# Virtueld | User's Manual

* Although this software is a form of game, please think of it as a prototype (early access) still under development.
* I'm hoping you enjoy as an app with your favorite VRM characters moving around.
* I will update this work and descriptions as often as possible.

* ☛ [Virtueld Dowload Site](https://xelf.booth.pm/items/1341365)

# About Title

Right now considering the official title name along with the logo.
The following are current candidates:

* `Virtueld` /` 🆅i🆁tueld` / `Vertueld`
* 🔈 /və́ːrtʃuəld/, /vɜːrtjuəld/, /vɝtʃuəld/ for `English`
* 🔈 /ヴァーチュエルド/ for `Japanese`
* I coined it from the followings:

|`English` Words|Related Words|Related `Japanese` Words|
|--|--|--|
|virtue|| 剛勇 武勇 美徳|
|virtual reality|| 仮想現実|
|eld|age, era| 時代 世代 古代|
|world|(hu)man + age|世界|

## 💻 Recommended System Requirements

| |Recommended Specifications|
|----|----|
|Operating System|Windows 10 64-bit|
|Video|DirectX 11 or later `*1`|
|Memory|4GB RAM|
|Storage|25GB available space|
|Broadband Internet connection|✅ (as currently planned)|
|Input Device|🎮Gamepad/⌨Keyboard/🖱Mouse: See☛[`Controls`](controls.md)|

> only as a guide

## `*1`
* Environment on `Intel HD Graphics` (some or all), it does not work properly (at `🏠Lobby` screen) with a phenomenon similar to the following report.
  ☛ [Problems with Intel HD Graphics causing crashes](https://forum.unity.com/threads/problems-with-intel-hd-graphics-causing-crashes.635704/)
  > Estimated from feedback received
  * As this page shows, it is considered neither the game nor a Unity side, but a crash or a defect of the **graphics driver**.
  * Please forgive that the problem is not the priority of the current measures, as it may not be perfect even if the problem is fixed, or the problem may be found in other parts.

# How to start

1. Unzip all files in the zip file. (first time after download)
2. Open the `Virtueld.exe` in the unzipped folder📁.

> * About protections by the Operating System `Windows 10` and/or anti-virus softwares, please treat with generic ways.
> * For update versions, download it again, and do same way to start 🙇

## About `Latest Version Checker`

* After launching, it will automatically check if the download site has the latest version.
  * ➡ If it can be determined that the latest version is **not available**
    * ➡ Regardless of the expiration date below, go to `🏠Lobby` and play as it is.
    > There is no message display.
  * ➡ If it is determined that the latest version is **available**
    * You will see the message `Newer Version Found`.
      * ➡ Press `OK` to open the download site in your web browser and exit the current game. Please download the latest version of the page and try the latest version according to the startup method mentioned above.
      * ➡ Press `Back` to proceed to the confirmation process of the expiration date. If it is within the expiration date, you can play as it is.
  * ➡ When the presence or absence of the latest version **could not be confirmed**
    > Network errors / Errors due to changes in download site specifications / Errors due to file format changes / Changes in publishing method etc.
    * ➡ Proceed to the confirmation process of the expiration date. If it is within the expiration date, you can play as it is.

## About `Expilation`

* As the **early access version**, an expiration date is set for each version.
* The expiration date of the version ends when the expiration date `Expilation` at the bottom of the screen is reached.
When start after the expiration date, a message containing the phrase `Expired on` will be displayed.
Please look for the latest version on [Download Site](https://xelf.booth.pm/items/1341365).

> * Display is in UTC (Coordinated Universal Time).
> * Treatment of future expiration dates are undecided.

# `🏠Lobby`

* After launching the game, you will see the `🏠Lobby`.

> Please note that pictograms described here and in-game icons will look different.

|||
|---|---|
|`Quit`|Quit the game. (with confirmation)|
|||
|`👤🆚🤖`|Open `Single Player Menu` (Player versus AI). (See below)|
|`🤖🆚🤖`|Start demo as AI versus AI.|
|`👤Character Selection`| Move to Character selection screen. (See below)|
|`🔎👤🆚👤`|Move to Lobby Search screen. Under dvelopment as `Discord`-related features. (See below)|
|`💬Discord`|Open the invitation page for Virtueld public channel.|
|`Web`| Open the [Offical Web Site](.).|
|`📜Report`|Report form for this software behavior. If there is no problem with the content, you can `Send`. If this is not available and let me know by other contact methods. (See below)|
|`⚙Settings`|Open the `⚙Settings` screen. (See below)|

# `Single Player Menu`

Selection screen for Single Player game mode.

|||
|---|---|
|`Back`|Back to the previous screen.|
|||
|`Duel`|Start normal match `Duel` mode. It will be decided when either of `Life` becomes 0. Regardless of the result, the next new round will begin.|
|`Survival`|Start `Survival` mode. It will be decided when either of `Life` becomes 0. If you win a round, you will advance to the next round. It will be difficult every round. If you do not win, the game is over.|
|`Training`|Start `Training` mode. Each `Life` will regenerate over time. There is no end of the round. A round reset operation is available.|

> Depending on versions, game modes may change the content or increase/decrease.

# `⚙Settings`

There are `Common`/`Screen`/`Scene` tabs in this screen. Tab move operation or mouse🖱 click to switch each screen.

## `Common` tab

|||
|---|---|
|`Back`|Back to the previous screen.|
|||
|`Audio`|Master volume can be adjusted by slider.|
|`Music`|Music volume can be adjusted by slider.|
|`Sound Effect`|Sound Effect volume can be adjusted by slider.|
|`AI Level`|AI's capability can be adjusted by slider. In the current versions, it is simply involved in the percentage of guard actions.|
|`Active Camera`|When ☑, the camera moves around the subject.|
|`Debug Tools`|When ☑, `Debug Tools` related UI are displayed. (See below)|
|`Move by Mouse`|When ☑, The relative movement of the mouse pointer corresponds to the movement input (equivalent to the left stick`🄻🕹` on the gamepad 🎮).|
|`English` / `Japanese`|☑ language is preferred. This setting is only reflected to the part that supports multiple languages. The initial setting depends on the execution environment (`Windows`).|

> * Each setting is saved when you change it.

## `Screen` tab

|||
|---|---|
|`Back`|Back to the previous screen.|
|||
|`Resolution`|Screen resolution: Width×Height `pixels` (Refresh rate `Hz`). Refresh rate may not be reflected.|
|`Mode`|`Full Screen Window`/`Maximized Window`/`Window`|
> * Each setting is saved when you change it.

## `Scene` tab

|||
|---|---|
|`Back`|Back to the previous screen.|
|||
|`Sky`|You can select either `Sunny` / `Cloudy` / `Starry`.|
|`Vine Density`|You can adjust the amount of vines generated in the background (`⇐` None - Many `⇒`). Press `⟳` to start regeneration. It doesn't affect gameplay directly, but please note that it may be **high loaded** until the process is completed after game startup or `⟳`.|

> * Each setting is saved when you change it.

## `Protocol` tab

Enable/Disable of the feature which makes the game startable from URL.

### Overview

* If you enable this feature, you can launch Virtueld on your Windows from the link `▶️Virtueld` on the page https://xelfia.github.io/Virtueld/.

### `Bind Protocol`

1. Press `Bind` to open `Bind Protocol` screen.
> * If you already have some settings, you will see `Bind Protocol (overwrite)`.
> * If you want to register Virtueld of different folder📁 (or version), please follow the activation procedure again.

2. Press `OK` to start to enable.
> * Usually, there is security confirmation by Windows.

3. Launch the secondary game app with white screen and close it shortly.
4. If `Succeeded` is displayed in the primary Virtueld game app, it has been successfully enabled.

### `Unbind Protocol`

* When already registered something:
  * ➡ Press `Unbind` to open `Unbind Protocol` screen. It is the same way as `Bind Protocol`.
> Please use especially when you want to disable (remove).

* When not registered anything:
  * ➡ Press `Unbind` to will display `Protocol Not Found`.

# `Escape Menu`

In the combat screen as `👤🆚🤖` (Single Player), input 🔙 to display the `Escape Menu`.

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
|`📂Open Folder`|Open the local VRM Folder📁. (See below)|
|`⟳`|Reloads the list of character models.|
|`⚙`|`VRoid Hub` can be `Link`ed or `Unlink`ed. (See below)|
|`Local`|Enable/Disable the local VRM files. (See below)|
|`VRoid Hub`|Enable/Disable your `VRoid Hub` character models. (See below)|
|`VRoid Hub💛`|Enable/Disable your favorite `VRoid Hub` character models. (See below)|
|`VRoid Hub★`|Enable/Disable the recommended `VRoid Hub` character models. (See below)|

> * If you do `VRoid Hub` related operations without `VRoid Hub Link`, it will be the screen of `VRoid Hub Link` as well as `⚙`.
> * The recommended character models are fixed in-game side and are subject to change without notice.

## Way to select a character

* First, please confirm (set) the state ☑ or ☐ of `P1` and `P2`.
* Depending on the filters at the almost bottom of the screen, character model icons will be displayed at the abeve.

> * If not found, it will be blank.
> * If 🛇 is displyed, it can not be used because it does not meet the conditions of use.

* Once a character model icon is selected, its descriptions are displayed on the screen.
* With the character model icon is selected, select it again to determine to use that character.
* `Loading...` after a while and combat starts.

> * If there is any problem with the compatibility between XVRF and the selected chartacter model, unusual behavior may occur during or after `Loading...`.
> * Please let me know if there is a posslbility of new discorveries☺

## Link to VRoid Hub

1. In-game `👤Character Selection` screen, press `⚙`.
2. Web browser will automatically open and display the `VRoid Hub` authorization code.
3. `Copy` the authorization code in that page.
4. The authorization code is automatically pasted on the game screen.
> If you can not enter the authorization code, please contact me (XVRF side) because there is a possibility of specification change etc.

5. Once you have confirmed that the authorization code is pasted, press `Link`.
6. If it `Succeeded`, go to the next step.

> If it `Failed. Please retry.`, Check the input content / internet connection / service running status etc and retry.

## Play with character model on VRoid Hub

1. After linking, let's search your favorite character in [VRoid Hub](https://hub.vroid.com).
2. Let's press ♡ in that page.
> * In XVRF, characters are only available for `Violence: YES` under the conditions of use.

3. In-game `👤Character Selection` screen, press `VRoid Hub` to turn it into ☑.
4. You will surely find the character and you can play with it.

## Play with your character model on VRoid Hub

1. After linking, in-game `👤Character Selection` screen, press `VRoid Hub` to turn it into ☑.
2. You will surely find the character and you can play with it.

> * In XVRF, you can always play with your character in `VRoid Hub`, regardless of conditions of use.
> * If it does not work better than the bundled or standard characters, please refer:
> ☛ `Japanese` [XVRF Model Definitions / XVRFで良く動くVRMのために](https://scrapbox.io/XVRF/XVRF_Model_Definitions_%2F_XVRF%E3%81%A7%E8%89%AF%E3%81%8F%E5%8B%95%E3%81%8FVRM%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AB)

## Play with local VRM files

You can also use your self-made VRM files or others-made VRM files that meet the conditions.

> ☛ [About VRM](https://vrm-consortium.org/#vrm) in `Japanese`

1. `👤Character Selection` screen ingame, press `📂Open Folder` to open the folder📁 of the following format.
  * `≪drive_letter≫:\Users\≪user_name≫\Documents\VRM`
2. Place VRM files (`.vrm` format) into this folder📁.
3. `👤Character Selection` screen ingame, press `Local` to turn it into ☑.
4. You will surely find the character and you can play with it.

> * In XVRF, characters are only available for `Violence: YES` under the conditions of use.
> * If it does not work better than the bundled or standard characters, please refer:
> ☛ `Japanese` [XVRF Model Definitions / XVRFで良く動くVRMのために](https://scrapbox.io/XVRF/XVRF_Model_Definitions_%2F_XVRF%E3%81%A7%E8%89%AF%E3%81%8F%E5%8B%95%E3%81%8FVRM%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AB)

## Skill List

> * Detailed explanation of the `Skill List` is in preparation.

## Share the Model Characteristics

> This page contains `not translated`: Please also refer to the [`Japanese`](ja/manual.md) edition using machine translation etc. 🙇

`not translated`

## ⚠Known Issues

`not translated`

## Discord-related features

* Experiments / tests are being conducted for some of tester-only features related to `Discord`.
> * As of `0.3.21`
>   * `Discord` features can be started mainly from `🔎👤🆚👤` button that opens the lobby search in `🏠Lobby` screen.
>   * Also, if you can connect to the `Discord` client on your operating system, `Discord` user information is displayed in `P1`.

* How to apply for `XVRF Discord Related Testers` is explained below.

☛ [XVRFのDiscord関連機能テスター応募方法](https://scrapbox.io/XVRF/XVRF%E3%81%AEDiscord%E9%96%A2%E9%80%A3%E6%A9%9F%E8%83%BD%E3%83%86%E3%82%B9%E3%82%BF%E3%83%BC%E5%BF%9C%E5%8B%9F%E6%96%B9%E6%B3%95) in `Japanese` language

## ✒Update Logs

☛ `English (N/A)` | [`Japanese`](ja/history.md)

## 🎮Controls and Input Devices

☛ [`English`](controls.md) | [`Japanese`](ja/controls.md)

## `📷Screenshot`

* On each screen, press `[F12]` key or hold `🔙` on gamepad 🎮 to open `📷Screenshot` screen.
* At this time, a screenshot is taken, and the following menu and a preview of the screenshot are displayed.

|||
|---|---|
|`Back`|Back to the **previous screen** to continue.|
|||
|`Capture`|Take a screenshot on the **previous screen** again. The same is true if you press `[F12]` key or hold `🔙` on gamepad 🎮 on `📷Screenshot` screen.|
|`Save`|Save the preview screenshot as an image file and open the local image folder📁 (in the format below) with the file.|

* `≪drive_letter≫:\Users\≪user_name≫\Pictures\Virtueld`

<!--
## 📜 Feedback / Report a Bug

> This is preliminary

* You can send via the `Report` in-game. Most of fields are automatically filled and read-only. `Log` is editable. Please confirm that there is no problem to submitting with that content, press `Send`.

> Feel free to give your feedback. Even if there is no issue, it is also able to know your system environments as statistics☺️

* If the in-game `Report` is not available, use the web form instead (in planned).
-->

## 📜How to manually report a issue

> * If you can not report the operation from the `📜Report` in-game, and if it seems that you need a log to identify the problem, please report it according to the following procedure.

1. On Windows running Virtueld, files in the folder hierarchy of the following format have a log when they were probably last run by the Unity player.
Look for this text file (`.log` format).

* `≪drive_letter≫:\Users\≪user_name≫\AppData\LocalLow\XELF\Virtueld\Player.log`
> The part of `≪≫` differs depending on the environment.

2. If the file is found, open that file.
3. Copy the text of the content to the clipboard.
4. Open the form below.

☛ 📜[Virtueld report form](https://docs.google.com/forms/d/e/1FAIpQLSdjhUb6AhpkO7nlG3015DIAD3Rq1K6cQPe_yP5--oi6qfcIZg/viewform)

5. Paste it into `Log` of the form.
> * If the log is long and it does not fit, please paste in the range from the top as priority.

6. Enter other fileds.
> * Rquired fields may be in a range that you know. For fields that you do not know, please enter an appropriate sentence (e.g. `Unknown`).

7. Press `Send`.
8. If you do not mind, it would be appreciated if you could post the form via Twitter etc.
> * Sorry to trouble you🙇

## 📧Contacts

* recommended Twitter hashtags (priliminary): `#Virtueld`
> `#XVRF`
* ☛ [xelfia@twitter.com](https://twitter.com/xelfia)
* [License](LICENSE.md)

> Thank you very much for everyone who `retweet`s/`like`s 🙇

--------
🆇🅴🅻🅵
©2018-2019 XELF
