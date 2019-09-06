<img src="image/xvrf-title-icon-1280x640.png" width="50%"/>

<!--[🔙](../README.md) | -->
[`User's Manual`](manual.md) | `Controls` | ~`History`~ | ~`Debug Tools`~ | `English` | [`Japanese`](ja/controls.md)

## 🎮 How to Control / Input Device

<!-- > This is preliminary-->
> Contents may change

* Gamepad is mainly used.
  * For combat, `🄻🕹️` (left stick) and 4 buttons are mainly used.
  * Additional buttons are also used auxiliary.
  * `Skill` (Command inputs) will be short (in planned).
* Though gamepad is recommended, you can also play with Keyboard/Mouse.

<!-- * `deprecated` ~You can customize the input bindings on `Input` tab of Configuration dialog.~ -->
* Virtueld now works with the Unity [New Input System](https://github.com/Unity-Technologies/InputSystem).
  * Since 4 buttons of any gamepad are mapped as `Ⓝ`/`Ⓔ`/`Ⓦ`/`Ⓢ` below under the New Input System. So I think you can play by default as expected bindings.

### Abstract Gamepad on New Input System (overview)

* Look the following chart as a gamepad 🎮.

| - | - | - | - | - | - | - | - |
|----|----|----|----|----|----|----|----|
| `Lt` | | | | | | | `Rt` |
| `Ls` | | | | | | | `Rs` |
| |`↑`| | | | |`Ⓝ`| |
|`←`|`🄻🕹️`|`→`|`Select` | `Start` |`Ⓦ`|`🅁🕹️`|`Ⓔ`|
| |`↓`| | | | |`Ⓢ`| |

### Gamepad Bindings on Virtueld (default)

* Following notations are for generalize input devices.
* Symbols are shown as similar icons in game screen.

| - | - | - | - | - | - | - | - |
|----|----|----|----|----|----|----|----|
| `🄻₂` | | | | | | | `🅁₂` |
| `🄻₁` | | | | | | | `🅁₁` |
| |`↑`| | | | |`Ⓐ`| |
|`←`|`🄻🕹️`|`→`|`🔙` | `▶️` |`Ⓣ`|`🅁🕹️`|`Ⓚ`|
| |`↓`| | | | |`Ⓖ`| |

* ⚠ Arrows are `🄻🕹️` inputs (not D-pad).

#### Notations and Input Bindings 

|Symbols (notations)|<!-- ~Name on `Input` tab~ (deprecated)-->|Basic Usage|🎮Gamepad|⌨Keyboard|🖱Mouse|
|----|----|----|----|----|----|
|`Ⓐ`|<!--Ⓐ Attack-->|Attack|`Ⓝ`|`[↑]` or Left `[Alt]`|`Left`|
|`Ⓚ`|<!--Ⓚ Kick-->|Kick|`Ⓔ`|`[→]` or `[Z]`|`Right`|
|`Ⓣ`|<!--Ⓣ Throw-->|Throw / Face to Opponent / Clinch|`Ⓦ`|`[←]` or `[X]`|`Middle`|
|`Ⓖ`|<!--Ⓖ Guard-->|Guard|`Ⓢ`|`↓` or `Space`|`Forward`|
|←/→|<!--Left Stick Horizontal-->|Move / Naviagte on Menu|`←`/`→`|`[A]`/`[D]`|-|
|↑/↓|<!--Left Stick Vertical-->|Move / Navigate on Menu|`↑`/`↓`|`[W]`/`[S]`|-|
|🄻¹|<!--L1-->|-|`Ls`|`[R]` (temporal)|-|
|🅁¹|<!--R1-->|-|`Rs`|`[R]` (temporal)|-|
|🔙|<!--Back-->|Go Back on Menu / Open Escape Menu|`Select`|`[Esc]`|-|
|📷|<!-- - -->|Open `📷Screenshot` Screen|Hold `🔙`|`[F12]`|-|
|🔨|<!-- - -->|Enter `🔨Debug Toolbar` (when debug tools is enabled)|Hold `▶️`|`[F11]`|-|

### Controls in Menu

|Controls|Basic Usage|⌨Keyboard (Alternative)|
|----|----|----|
|↑/↓/←/→|Navigate (`🄻🕹️`)||
|⯅/⯆/⯇/⯈|Navigate (D-pad)||
|`Ⓖ`|Select / OK||
|`Ⓚ`|Cancel||
|🄻₁/🅁₁|Switch Tab|Hold `[Tab]`/`[Tab]`|
|🄻₂/🅁₂/`🅁🕹️`|Scroll on Scroll Rect||
|🔙|Go Back to Previous Screen||

### Controls in Combat

* **Your Position** and **Opponent Position** indicate required conditions.
* **Skills** are optional: character customizable features (in planned).
* ⚠ Note that described as when you are facing rightward view in screen.

|Controls|Your Position|Opponent Position|Default Move|Skills (optional)|
|----|----|----|----|----|
|🄻₁+🅁₁|-|-|Reset Combat in Training Mode|-|
|→|`Stand`|-|`Run Forward`|-|
|←|`Stand`|-|`Step Backward`|-|
|↑|`Stand`|-|`Step Leftward`|-|
|↓|`Stand`|-|`Step Rightward`|-|
|↗|`Stand`|Your Closed Forward|`Step Around Left`|-|
|↘|`Stand`|Your Closed Forward|`Step Around Right`|-|
|`Ⓐ`|`Stand`|Your Forward|-|`Punch`|
|`Ⓐ`|`Stand`|Your Behind|-|`Round Back Fist`|
|`Ⓐ`|`Punch`|-|-|`Jab`|
|→`Ⓐ`|`Stand`|-|-|`Splash`|
|←`Ⓐ`|`Stand`|-|-|`Dosal Tackle`|
|`Ⓚ`|`Stand`|-|-|`Low Kick`|
|→`Ⓚ`|`Stand`|-|-|`Sliding Kick`|
|←`Ⓚ`|`Stand`|-|-|`Round Kick`|
|`Ⓖ`|`Stand`|-|`Guard`|-|
|→`Ⓣ`|`Stand`|`Stand` + Your Closed Forward|`Jumping Closed Guard`|
|←`Ⓣ`|`Stand`|`Stand` + Your Closed Forward|`Round Throw`|
|`Ⓣ`|`Stand`|`Supine`/`Prone`|-|`Kneeling Mount`|
|`Ⓣ`|`Stand`|Not Face Forward|-|`Turn` to face forward|
|`Ⓐ`|`Kneeling Mount`|`Supine`/`Prone`|-|`Kneeling Slam`|
|→|`Kneeling Mount`|-|`On All Fours`|-|
|→|`Supine`|-|`Get up off`|-|
|←|`Supine`|-|`Kip up`|-|
|→|`Prone`|-|`Get up off via Crouch`|-|
|↑/↓|`Supine`/`Prone`|Not Mounted|`Roll Over`|-|
|etc…|…|…|…|…|

### How to open the Configuration dialog

> ⚠ `0.3.101`+: Follwing is no longer available on `Unity 2019.3.0b1`+.  
> Instead, press `[F1]` to open `Screen Settings` screen ingame.

~~Open Virtueld's `.exe` file with holding `[Ctrl]` to start the game app.~~
> ⚠ Configuration for the New Input System is not provided in current versions. I apologize for the inconvenience.
> The existing `Input` tab is left blank.

--------
🆇🅴🅻🅵
©2018-2019 XELF

