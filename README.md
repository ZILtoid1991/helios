# Helios

Variable width bitmap font project, to be used in pixel-art games, low-power embedded devices with a matrix display, etc.

# Currently available sizes and their limitations

## Size 5

![Image displaying the font](/pics/helios5large.png) ![Image displaying the font](/pics/helios5small.png)

Uppercase-only due to readability issues with lowercase letters. No diacritics.

The variable width makes certain letters like the `M`, `N`, `W`, `H` easier to distinguish compared to other 5 pixel tall fonts. Easy to condense vertically.

## Size 6

One extra pixel per height allows for lowercase letters. Most diacritics are supported, except for combined diacritics used in languages like Vietnamese. With some line spacing modifications, these could be added for a special version.

Line condensed version allows for 6+1 line height, otherwise the normal one uses 6+4 to avoid the diacritics touching the next line. Languages where lower-diacritics are also heavily used might require extra line spacing.