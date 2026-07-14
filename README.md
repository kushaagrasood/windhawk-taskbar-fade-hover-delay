# Taskbar Fade+ (Hover Delay)
Automatically dims or hides the taskbar when the computer is idle.

This mod is designed to prevent OLED burn-in and reduce visual distractions by lowering the taskbar's opacity when it is not in use.

> This is a fork of [Taskbar Fade](https://github.com/lukvbp) by Lukvbp, with an added hover-fade delay setting.

### Features
* **Idle Dimming:** The taskbar fades to a lower transparency level (configurable) when the mouse is away.
* **Idle Hiding:** Optionally hides the taskbar completely after a set timeout.
* **Instant Wake:** Moving the mouse to the taskbar or the bottom of the screen restores full opacity immediately.
* **Hover Fade Delay:** (New in this fork) Waits a configurable amount of time after the cursor leaves the taskbar before starting the dim fade, so brief accidental exits don't trigger it.
* **Smart Idle:** (Optional) Only hide the taskbar if the desktop is focused. If windows are open, keep the taskbar dimmed instead.
* **Clean Desktop:** (Optional) Hide desktop icons when the taskbar hides for a completely black screen.
* **Customization:** Settings available for fade speed, transparency levels, and timeout duration.

### Configuration
* **Default Transparency:** The opacity level when the taskbar is dimmed (0-100%).
* **Hover Fade Delay:** Milliseconds to wait after the cursor leaves the taskbar before the dim fade begins.
* **Enable Idle Hiding:** Check this to make the taskbar vanish completely after a timeout.
* **Smart Idle:** If checked, idle hiding is disabled when any window is open/focused.
* **Hide Desktop Icons:** If checked, desktop icons will also vanish when idle.
* **Idle Timeout:** Seconds of inactivity before the taskbar hides.
* **Fade Speed:** Duration of the fade animation in milliseconds.

### Changelog
* **v2.2.0** — Added configurable Hover Fade Delay to prevent accidental brief cursor exits from triggering the dim animation.
