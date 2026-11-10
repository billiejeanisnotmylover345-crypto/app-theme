# Imperial Machina — Infinix Hot 50i setup

Device target: Infinix Hot 50i (720 × 1600, 20:9), shipped with Android 14 and XOS 14.5. Regional software updates and menu names can differ.

## A. Apply the wallpaper
1. Open `wallpapers/hot-50i-imperial-machina.svg` in Chrome or another browser.
2. If your Gallery cannot set an SVG directly, convert/export it to PNG at 720 × 1600 using a vector editor.
3. Save the PNG locally.
4. Open **Settings → Personalization** or **Settings → Wallpaper & style** (the exact label varies by XOS build), choose the image, and apply it to Home screen and Lock screen.
5. On the lock screen, keep the clock in the clear upper area; on the home screen, avoid placing large widgets over the central crest.

## B. Use XOS theme controls first
Open the built-in **Themes / XTheme** app if it is present on your firmware. Look for wallpaper, icon and font customization. Apply the wallpaper there if offered. Theme-store catalogues and theme-package support can vary by region and firmware; this repository does not contain a proprietary XTheme package.

## C. Home-screen arrangement
- Use a 4- or 5-column grid, whichever keeps icons comfortably spaced.
- Keep the dock to Phone, Messages, Browser and Camera.
- Use dark folders and hide icon labels if your launcher supports it.
- Avoid stacking multiple widgets; the Helio G81 and battery will benefit from a restrained layout.

## D. Icon styling
`icons/imperial-machina-icons.svg` is a 12-symbol reference sheet, not an installable icon pack. Export each symbol separately as a square transparent PNG and assign it through XOS icon editing (if available) or a launcher with per-app icon support. For automatic icon replacement, the artwork needs to be packaged as an icon-pack app and mapped to installed app package names.

## E. Widgets
Use the built-in widgets or a compatible widget app to create:
- Compact clock/date: ivory text, gold divider
- Battery: slim gold ring with cyan percentage
- Weather: small cyan temperature with muted ivory details

Palette: obsidian `#090910`, violet `#7546B8`, cyan `#36E6E0`, antique gold `#C69A48`, bronze `#704A2C`, ivory `#E9DFC9`.

## F. What Android will not let a normal theme change
A wallpaper/launcher theme cannot safely replace every system element. Status bar, quick settings, system dialogs, navigation gestures and some lock-screen elements remain controlled by XOS. Changing those deeply may require firmware-specific support or root; this kit does not root or modify firmware.

## Notes
This is a visual customization kit, not an APK or a flashable ROM. Back up your current wallpaper and launcher layout before changing settings.
