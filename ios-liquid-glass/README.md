# iOS Liquid Glass Theme

A modern, glass‑morphism iOS‑inspired theme for Home Assistant.

## Features
- Sticky + responsive wallpapers  
- Glass cards, dialogs, chips  
- Glass sliders & toggles  
- Bubble pop‑ups with glass styling  
- Animated pop‑up transitions  
- State‑based accents  
- Light & dark modes  

## Installation

Place this folder inside:

```
/config/themes/ios-liquid-glass/
```

Then enable themes in `configuration.yaml`:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

Restart Home Assistant and select the theme in your profile/dashboard.

