# Contact me through Discord

[![Discord](https://img.shields.io/discord/1196075698301968455?style=social&logo=discord&label=ΛVΛRIΛ)](https://discord.gg/avia)

# Timestamp Tweaks

Bring back a more detailed timestamp on hover (+ more readable edited-message-timestamp) and create bordered timestamps! Both are customizable!

### Bordered timestamps
Before:\
![Image](https://github.com/user-attachments/assets/3e292344-ec2b-4ec7-976b-7e216f3e925e)

After:\
![Image](https://github.com/user-attachments/assets/e4e9570e-6589-48db-93b5-0aa4ce4be1f3)

### Full timestamps
Before:\
![Image](https://github.com/user-attachments/assets/bb3766f1-e3bc-4ab2-8d8f-da9c48ee99c9)

After:\
![Image](https://github.com/user-attachments/assets/4fb937d3-4a4f-47f8-896e-7ed875826936)

# Installing it to your Discord

Use [Vencord](https://github.com/Vendicated/Vencord) or an equivalent client mod that allows you to install themes.

Paste the following link into your online theme links:
```
https://raw.githubusercontent.com/MEWPASCO/timestamp-tweaks/main/timestamps.css
```

### Other method 
Paste this into your QuickCSS (Or any non-Vencord equivalent) to make it a little easier:
> [!NOTE]
> Must be at the top of your code, @import does not work otherwise - this is for all the @import code you might have - put it to the top!  
```
/* timestamp-tweaks */
@import url('https://raw.githubusercontent.com/MEWPASCO/timestamp-tweaks/main/timestamps.css');
```

Alternatively if your client does not support online themes you can download the theme file found in this repository and put it into your theme folder.

# Configuration

Put this into your QuickCSS (Or any non-Vencord equivalent) to configure some behavior of this theme:
```css
/* timestamp-tweaks */
:root{
  /* Timestamp - Border */
  /* the / <number> in the hsl code refers to the opacity */
    --timestamp-border-color: hsl(120 100% 50% / 100%) !important;

  /* Colored EDITED-Timestamp on hover */
[role="article"]:hover .timestamp_c19a55:has(.edited_c19a55) > [class^="hiddenVisually_"] {
  color: #ff00a6 !important;   /* !!custom color!! */
}
}
```

Thanks to the creator of the wonderful website of [HSL Color Picker](https://hslpicker.com/#00ff00fa), this will help you pick your HSL value/s!
