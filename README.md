# Monogram for Zoom.us on macOS (Unofficial)

This is a collection of Monogram key presets for the Zoom.us app on macOS.

### Prerequisites ###

- Mac (OS version 10.12 or later required, 10.13 or later recommended)
- [Monogram Creator](https://monogramcc.com/download/) (Version 4.1 or later recommended)
- [Monogram Creative Console](https://monogramcc.com/) (note:  Palette Gear dial, button, or slider modules _must_ be connected to a Monogram core module to work as intended.)
- [Zoom.us macOS Client](https://zoom.us/download#client_4meeting) (Version 5.4.1 or later recommended)

---

## Setup Instructions ##

### Add integration bundle to Monogram Creator ###

1. In Monogram Creator, go to File > Preferences > Integrations.
2. Hit the + button (lower right); this should open a file browser.
3. Browse for your <code>mono-zoom-mac-main</code> folder, then double-click it to look inside for the <code>zoommac</code> folder.
4. Select the <code>zoommac</code> folder without opening it, then hit "Select Folder" (bottom right).

---

## Disclaimers ##

This is purely a homebrewed set of Monogram presets for Zoom.us based off of keyboard shortcuts. A few things to keep in mind:

- It isn't developed or endorsed by either company. 
- It's provided with no warranty and it may not work on your system.
- Future Zoom.us or Monogram updates might break it.
- It's licensed under <a href="https://opensource.org/licenses/MIT">MIT</a>. Pull requests and issues are welcome :)

### Known Limitations ###

- By default, these actions only work when a Zoom.us window is focused; this may cause problems when sharing your screen or using remote access.
- Workaround for above: go to Zoom.us > Preferences > Keyboard Shortcuts, and select "Enable Global Shortcuts" next to any/all desired shortcuts.
- Some assignments depend on keyboard shortcuts and may not work with certain non-US/non-English localizations or non-QWERTY keyboard layouts.
- Workaround for above: Please create custom key command assignments in Monogram Creator using the Customize > Keyboard Mode dialogue. For example, assign the Spacebar to a key/button in order to create a push-to-talk command.
