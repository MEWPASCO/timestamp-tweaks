# Contact me through Discord

[![Discord](https://img.shields.io/discord/1196075698301968455?style=social&logo=discord&label=ΛVΛRIΛ)](https://discord.gg/avia)

# Timestamp Tweaks

This is a small collection of tweaks to the timestamps, as example making timestamps sent in chat more readable, bring back the more detailed message timestamp and also show the exact timestamp of when a message got edited (with only css)((will replace the "edited" text))

### More readable timestamps
Before:\
![Image](https://github.com/user-attachments/assets/3e292344-ec2b-4ec7-976b-7e216f3e925e)

After:\
![Image](https://github.com/user-attachments/assets/e4e9570e-6589-48db-93b5-0aa4ce4be1f3)

### Detailed timestamps
Before:\
![Image](https://github.com/user-attachments/assets/4fd5f0ab-837c-41c9-8732-9a91a4a13bbd)

After:\
![Image](https://github.com/user-attachments/assets/11e296c9-24f1-4a4c-98da-a71c4f8e7e5a)

### Edited timestamps
Before:\
![Image](https://github.com/user-attachments/assets/200187df-b419-46c4-9e80-af93f864f479)

After:\
![Image](https://github.com/user-attachments/assets/c4f9588e-3a04-4005-8043-cccfc1fc0ea9)

# Installing it to your Discord

Use [Vencord](https://github.com/Vendicated/Vencord) or an equivalent client mod that allows you to install themes.

Paste the following link into your online theme links:
```
https://raw.githubusercontent.com/MEWPASCO/timestamp-tweaks/refs/heads/main/timestamps
```

### Other method 
Paste this into your QuickCSS (Or any non-Vencord equivalent) to make it a little easier:
> [!NOTE]
> Must be at the top of your code, @import does not work otherwise - this is for all the @import code you might have - put it to the top!  
```
/* timestamp-tweaks */
@import url('https://raw.githubusercontent.com/MEWPASCO/timestamp-tweaks/refs/heads/main/timestamps');
```

Alternatively if your client does not support online themes you can download the theme file found in this repository and put it into your theme folder.

# Configuration

Put this into your QuickCSS (Or any non-Vencord equivalent) to configure some behavior of this theme:
```css
/* timestamp-tweaks */
:root{
  /* the / <number> in the hsl code refers to the opacity */
    --timestamp-border-color: hsl(120 100% 50% / 100%) !important; 
}
```

Thanks to the creator of the wonderful website of [HSL Color Picker](https://hslpicker.com/#00ff00fa), this will help you pick your HSL value/s!
