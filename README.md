# Default Member List Versions of Dark+ and Azurite Now Integrated!

The default member list variants of the **Dark+** and **Azurite** themes are now part of their main theme version!

If you're using the default member list version, please download the latest versions of the themes directly from the BetterDiscord website:

* [Dark+ Theme](https://betterdiscord.app/theme/Dark%2B)
* [Azurite Theme](https://betterdiscord.app/theme/Azurite)

Once downloaded, follow the steps below to enable the default member list version in each theme:


## Azurite

1. **Open the theme file** in a text editor.
2. **Comment out** the main theme import:

   ```css
   /*@import url('https://devevil99.github.io/devevil/BetterDiscordAddons/Theme/Azurite/Azurite.theme.css');*/
   ```
3. **Uncomment** the default member list version:

   ```css
   @import url('https://devevil99.github.io/devevil/BetterDiscordAddons/Theme/Azurite/Azurite-Default-Member-List.theme.css');
   ```
4. **Save the file** and reload your theme in BetterDiscord.
