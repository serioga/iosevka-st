# Iosevka ST

Custom build of the [Iosevka](https://github.com/be5invis/Iosevka) font.

## Character styles

Based of default configuration with changes:

- `D` with more rounded shape; without serifs
- `G` with tootheless (corner) body, and inward hook terminal; without top serif
- `I` with short serifs
- `W` with curly body; without serifs
- `f` with flat top hook, descending extension, and crossbar at X-height
- `i` with shorter top serif and full bottom serif
- `k` with standard shape; without serifs, to override default italic
- `l` with top serif and curly-then-flat tail
- `t` with body with flat hook, and a shorter neck
- `w` with curly body; without serifs
- `y` with straight shape, and a tail turns leftward; without serifs
- Greek small Lambda (`λ`) with straight upper and a tail turns leftward
- Cyrillic Capital Lower Zhe (`Ж`) with curly legs
- Cyrillic Lower Zhe (`ж`) with curly legs
- Cyrillic Capital Ze (`З`) with serif at both top and bottom, to distinguish from `3`
- Cyrillic Capital Ka (`К`) with straight shape; without serifs
- Cyrillic Lower Ka (`к`) with straight shape; without serifs
- Cyrillic Lower Ef (`ф`) with standard shape and without serifs, to override default italic
- Zero (`0`) with oval shape; without slash
- `2` with straight neck
- `4` with closed contour
- `5` with an oblique-arched left bar
- `8` looks like two circles joined together
- `9` with a more open contour
- Asterisk (`*`) with five-pointed shape, and medium position
- Higher circumflex `^`
- Parenthesis with larger contour, like that in Monaco
- More straight braces
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

- Bold is one step bolder than standard.

## Screenshots

![Highlighted characters](screenshot_iosevka-customizer-highlight.png?raw=true)
![All characters](screenshot_iosevka-customizer-all.png?raw=true)
