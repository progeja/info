# File Watchers

## SASS (scss)

Algfailid on kaustas `/scss/*` ja kompileeritud tulemus peaks olema kaustas: `/htdocs/css/*`

### Seaded:

| Väli | Väärtus |
| ----- | ----- |
| **Name:** | `SCSS` |
| **File type:** | `SCSS Style Sheet` :ballot_box_with_check: Track only root files |
| **Scope:** | *Lisa kaust, mille sisu jälgitakse* |
| **Program:** | `sass` |
| **Arguments:** | `--update $FileName$:$ProjectFileDir$/htdocs/css/$FileNameWithoutExtension$.css` |
| **Output paths to refresh:** | `$ProjectFileDir$/www/css/$FileNameWithoutExtension$.css:$ProjectFileDir$/www/css/$FileNameWithoutExtension$.css.map` |
| **Working directory:** | $FileDir$ |
**PS.** Kui on tegu mitme seotud projektikaustaga, siis võib kasutada ka `$ProjectFileDir` asemel `$FileParentDir$`, sest `$ProjectFileDir$` on seotud vaid põhiprojekti juurkaustaga.


## SASS Minified (scss)

Algfailid on kaustas `/scss/*` ja kompileeritud tulemus peaks olema kaustas: `/htdocs/css/*`

### Seaded:

| Väli | Väärtus |
| ----- | ----- |
| **Name:** | `SCSS Minimize` |
| **File type:** | `SCSS Style Sheet` :ballot_box_with_check: Track only root files |
| **Scope:** | *Lisa kaust, mille sisu jälgitakse* |
| **Program:** | `sass` |
| **Arguments:** | `--style compressed --update $FileName$:$ProjectFileDir$/htdocs/css/$FileNameWithoutExtension$.min.css` |
| **Output paths to refresh:** | `$ProjectFileDir$/htdocs/css/$FileNameWithoutExtension$.min.css:$ProjectFileDir$/htdocs/css/$FileNameWithoutExtension$.min.css.map` |
| **Working directory:** | $FileDir$ |

