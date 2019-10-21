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

Old-time Windows used either a 16 or a 20 color palette, so the idea is to try to keep icons in this icon set
adhering to that palette to remain consistent with the rest. This is by no means a requirement, though. Some
things look just awful in 16 colors, so exceptions can be made. Also, providing several versions of the same
icon with varying levels of "technological purity" should also be fine.

A GIMP palette file with Windows' original 20 colors is provided in the `palette` directory, as well as an image of that palette.

To work with GIMP, you can just import the palette file (right click->"Import Palette..." on the palettes 
list), and then select Image->Mode->Indexed... to create a palettized version of your image. Be sure to try
out different dithering modes, as some modes will look terrible for some images.

Indexed mode, custom palette
---

If the default color palette just can't be made to work, another option is to create a custom palette with a very low color count. In GIMP, you can select Image->Mode->Indexed..., select "Generate Optimum Palette" with a low color count (8, 10, 12, depending on the icon), and try different dithering modes. This won't be as 90's, but it'll probably look pretty good!


Contributing
============

Please feel free to send merge requests with new/improved icons, backgrounds, or even themes! (only 90's-era
themes, please).

Contribution rules will initially be governed by the Contributor Covenant: https://www.contributor-covenant.org/
I'm no expert on the strengths/weaknesses of different code of conduct models, but this one looks reasonable
at first glance, so we'll go with that for now.

