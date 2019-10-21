90's Phone Theme
================

This theme was originally created by Suricrasia Online and shared in this Mastodon post, which subsequently exploded in
popularity:
https://cybre.space/@SuricrasiaOnline/102993060452718260

She posted the icons and background she used on Google Drive, which I've compiled here with the idea of
expanding on it and provide a more extensive set of icons and background formats (for different phone
resolutions, mainly).


Creating new icons
==============

Finding icons
---

An approach used by Suricrasia which I have also found useful is to just get the favicon from a related
website, scale it down to 32x32 (the original icon size for Windows), and then rescale it up to 256x256 with
"None" for the interpolation type. This will give you a properly pixelated image. 

Color palette
---

Old-time Windows (before Windows95) used either a 16 or a 20 color palette, but by Windows95 it used a
changing 235 color palette with a predefined set of 20 colors that could not be changed. Those 20 colors are
the same as the old 20-color palette.

At the time of Windows95, icons were a mix, with some made for the 20-color palette, and some made with more
colors.

The idea for this theme is to try to keep icons using a low number of colors, so as to remain consistent with
the rest.  

If one wants to use the old 20-color palette, a GIMP palette file with Windows' original palette is provided
in the `palette` directory, as well as an image of that palette.

To work with GIMP, you can just import the palette file (right click->"Import Palette..." on the palettes 
list), and then select Image->Mode->Indexed... to create a palettized version of your image. Be sure to try
out different dithering modes, as some modes will look terrible for some images.

If one wants to emulate one of the 235 color palettes instead, another option is to create a custom palette
with a very low color count. In GIMP, you can select Image->Mode->Indexed..., select "Generate Optimum
Palette" with a low color count (8, 10, 12, depending on the icon), and try different dithering modes. This
won't be as 90's, but it'll probably look pretty good!


Contributing
============

Please feel free to send merge requests with new/improved icons, backgrounds, or even themes! (only 90's-era
themes, please).

Contribution rules will initially be governed by the Contributor Covenant: https://www.contributor-covenant.org/
I'm no expert on the strengths/weaknesses of different code of conduct models, but this one looks reasonable
at first glance, so we'll go with that for now.

