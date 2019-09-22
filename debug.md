<img src="image/xvrf-title-icon-1280x640.png" width="50%"/>

<!--[🔙](../README.md) | -->
[`User's Manual`](manual.md) | `Controls` | ~~`History`~~ | `Debug Tools` || **English** | [**Japanese**](ja/controls.md)

----

# Debug Tools

Features that can be used effectively by creative people such as VRM authors.

It is supposed to be used so that the results can be seen more quickly in the following situations.

* How well does your VRM character animate as an example?
* How compliant is your VRM character with the XVRF specification?

## ⚠Notes
> * There is no guarantee for the functions classified as debug.
> * The debug functions may be changed / increased at any time.
> * In many cases, it is useful to make verification easier or to save time.
> * However, if there is a function that can be foreseen if an inappropriate problem occurs, please refrain from using it.

## Debug Toolbar

When `Debug Tools` is enabled☑ in `⚙Settings`, you can use the debug tools (developer functions) at the bottom of the screen.

* Press `[F11]` or hold the gamepad🎮 `▶` to move into `🔨Debug Toolbar`. 
> If another screen overlaps before the `🔨Debug Toolbar`, you cannot directly operate the `🔨Debug Toolbar` button with a mouse click, so please do the above operation first.

* Press 🔙 to leave the `🔨Debug Toolbar`.

|||
|---|---|
|`🏠`|Forcibly returns to the `🏠Lobby` screen.|
|`👤`|Toggle show/hide of the character icon on the combat screen.|
|`Skill`|Show/Hide the Skill List.|
|`❙◁`|Restart the combat round.|
|`▷❙`|Start the next combat round.|
|`⊝P1`|Set the health of `P1` or` A1` to 0.|
|`⊝P2`|Set the health of `P2` or` A2` to 0.|
|`In Fight`|Move both to a close position.|
|`On Edge`|Force both to move onto the ring boundary. However, since it is currently prevented from falling off the ring, it will be pushed back slightly inward.|
|`Ring Out`|Force both to move out of the ring. However, it is currently pushed back inward because it does not fall out of the ring.|
|`Supine`|Force both to be `Supine`.|
|`0.25x`|0.25x speed|
|`0.5x`|0.5x speed|
|`1.0x`|1x speed|
|`2.0x`|2x speed|
|`AI🆚AI`|Immediately switch to AI versus AI.|
|`P🆚AI`|Immediately switch to Player versus AI.|

## `Debug`

~~If `Debug Tools` is enabled☑ in `⚙Settings`, the `Debug` UI (user interface) is displayed in `🏠Lobby`.~~
> `0.3.161+`: Temporarily hidden. Not available.

<!--
> * This feature is completely prototype.
> * Commentary pending for prototype stage
-->

## Statistics Monitor `Graphy`

* If you display `Graphy`, you can check statistics about operation performance.

> If you feel performance problems against the specification of the execution environment, it would be greatly appreciated if you could share the screenshots / videos showing `Graphy` with the contents of the `Report`.

### Outline
* The following states are displayed in `Graphy` activated.
  * FPS (Frames Per Second)
  * Memory Usage
  * Output Volume

### Controls in Virtueld
* It is hidden at startup.
* Toggle between show/hide with `[Ctrl]`+`[H]`.
* Switch the format with `[Ctrl]`+`[G]`.

> * Controls are subject to change.
> * For FPS, if vertical synchronization (V-SYNC) is enabled and sufficient performance is achieved, a number close to that will be displayed.
>   * A typical value is 60 fps (60 Hz). (Varies depending on the environment)
> * Decreases when `👤Character Selection` list is being updated / loading characters.

`Reference` ☛ [`Graphy`](https://github.com/Tayx94/graphy/)

--------
🆇🅴🅻🅵
©2018-2019 XELF
