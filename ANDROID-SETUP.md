# Apply Imperial Machina on Android

This kit contains the artwork and design tokens. Android manufacturers use different theme engines, so the exact steps depend on the phone model.

## 1. Wallpaper
1. Open `wallpapers/imperial-machina.svg` from the repository.
2. If your Gallery app does not support SVG, open it in a browser or a vector editor (for example, Inkscape) and export it as a **1440 × 3200 PNG**.
3. Save the PNG to your phone.
4. In Settings → Wallpaper (wording varies), set it for the home screen and lock screen. Adjust the crop so the crest sits below the clock.

## 2. Launcher layout
For the most control, use a launcher that supports custom icon packs, grid size, dock styling and label visibility (for example, Nova Launcher or Lawnchair; feature availability can vary by version).
- Set a 5-column grid.
- Hide icon labels for a cleaner imperial-console look.
- Use a 4-icon dock.
- Prefer dark folders and translucent/black surfaces.
- Keep the main clock widget above the central crest, not over the lower skyline.

## 3. Icons
`icons/imperial-machina-icons.svg` is a **reference sheet**, not an installable icon-pack APK. Export individual symbols as transparent PNGs in a square canvas, then assign them through your launcher's per-app icon editing feature. The sheet includes Clock, Royal, System, Phone, Notes, Mail, Power, Files, Messages, Browser, Settings and Camera.

For a complete automatic icon pack, the symbols must be packaged into an Android icon-pack app and mapped to the package names of installed apps. This repository does not yet contain that APK.

## 4. Widgets
A widget app such as KWGT can reproduce the style:
- Background: `#090910` at 80–90% opacity
- Border/divider: `#C69A48`
- Main text: `#E9DFC9`
- Accent: `#36E6E0`
- Secondary accent: `#7546B8`

Suggested widgets:
- Compact digital clock with small date line
- Battery percentage in a thin gold-ring meter
- Minimal weather line with cyan temperature
- Avoid large opaque widget cards; let the wallpaper remain visible.

## 5. Lock screen
Use the phone's built-in lock-screen customization where available:
- Choose a clean clock face in ivory or gold.
- Keep notification previews discreet.
- Use a dark notification style if your device offers it.
- Avoid placing shortcuts over the central crest.

## 6. Manufacturer notes
- **Samsung:** Galaxy Themes and Good Lock modules may offer additional lock-screen, home-screen and icon controls, depending on model and region.
- **Xiaomi / Redmi / POCO:** the Themes app may support complete themes; availability and third-party theme installation vary by region.
- **Pixel / Motorola / many other Android devices:** use wallpaper settings plus a compatible launcher and widget app.

## What I need to make this a truly installable theme
Send the exact phone brand and model (for example, Samsung Galaxy A54, Tecno Camon 30, Infinix Note 40, Pixel 8). I can then tailor the setup to its theme engine and screen resolution.