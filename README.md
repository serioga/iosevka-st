# Iosevka ST

Custom build of the [Iosevka](https://github.com/be5invis/Iosevka) font.

## Character styles

This build customizes the following character styles.

- `D` with more rounded shape; without serifs
- `G` with tootheless (corner) body, and inward hook terminal; without top serif
- `I` with short serifs
- `L` with motion serif at bottom right
- `W` with curly body; without serifs
- `f` with a flat top hook and a crossbar at x-height in both styles. The upright has no bottom serif or hook. The italic has a descending bottom hook.
- `i` with shorter top serif and full bottom serif
- `k` with standard shape; without serifs, to override default italic
- `l` with top serif and curly-then-flat tail
- `t` with body with flat hook, and a shorter neck
- `w` with curly body; without serifs
- `y` with straight shape, and a tail turns leftward; without serifs
- Greek small Lambda (`λ`) with straight upper and a tail turns leftward
- Cyrillic Capital Zhe (`Ж`) with curly legs
- Cyrillic Lower Zhe (`ж`) with curly legs
- Cyrillic Capital Ze (`З`) with a serif at the top, to distinguish it from `3`
- Cyrillic Capital Ka (`К`) with straight shape; without serifs
- Cyrillic Lower Ka (`к`) with straight shape; without serifs
- Cyrillic Lower Ef (`ф`) with standard shape and without serifs, to override default italic
- `0` with oval body shape, and tall slash
- `2` with straight neck; without serifs
- `4` with closed contour; without serifs
- `5` with an oblique upper-left bar and an arched middle part, without serifs
- `7` with straight stem, and serifs
- `8` looks like two circles joined together
- Asterisk (`*`) with five-pointed shape, and medium position
- Higher circumflex `^`
- Straight Guillemets (`« »`)
- Number sign with slanted bars
- At symbol (`@`) with four-fold body, and solid inner
- Dollar symbol with interrupted strike-through vertical bar
- Percent % with rings and continuous bar

## Ligations

- Vertically align some of the operators (like `*`) to the center position it is before or after a "center" operator (like `+`).
- Plus (`+`) and Minus (`-`) will trigger other operator characters at left to be centered.
- Plus (`+`) and Minus (`-`) will trigger other operator characters at right to be centered.
- Equal (`=`) will trigger other operator characters at left to be centered.
- Equal (`=`) will trigger other operator characters at right to be centered.
- Less (`<`) and Greater (`>`) will trigger other operator characters at inside to be centered.
- Less (`<`) and Greater (`>`) will trigger other operator characters at outside to be centered.
- Treat colon (`:`) as operator and perform chained centering.
- Move connecting dotty punctuations closer, like for `::`, `:::` and `...`.
- Move consecutive bars closer, like for `||`, `|||` and `//`.

## Shape

- SemiBold, Bold, and ExtraBold use shape weights of 700, 800, and 900, respectively. Each is 100 above the corresponding Iosevka default. Their menu and CSS weights are 600, 700, and 800.

## Screenshots

![Highlighted characters](screenshot_iosevka-customizer-highlight.png?raw=true)
![All characters](screenshot_iosevka-customizer-all.png?raw=true)
