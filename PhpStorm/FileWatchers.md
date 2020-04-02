# File Watchers

## SASS (scss)

Algfailid on kaustas `/scss/*` ja kompileeritud tulemus peaks olema kaustas: `/htdocs/css/*`

### Seaded:

| Väli | Väärtus |
| ----- | ----- |
| **Name:** | `SCSS` |
| **File type:** | `SCSS Style Sheet` [x] Track only root files |
| **Scope:** | *Lisa kaust, mille sisu jälgitakse* |
| **Program:** | `sass` |
| **Arguments:** | ´--update $FileName$:$ProjectFileDir$/www/css/$FileNameWithoutExtension$.css´ |
| **Output paths to refresh:** | `$ProjectFileDir$/www/css/$FileNameWithoutExtension$.css:$ProjectFileDir$/www/css/$FileNameWithoutExtension$.css.map` |
| **Working directory:** | $FileDir$ |


## SASS Minified (scss)

Algfailid on kaustas `/scss/*` ja kompileeritud tulemus peaks olema kaustas: `/htdocs/css/*`

### Seaded:

| Väli | Väärtus |
| ----- | ----- |
| **Name:** | `SCSS Minimize` |
| **File type:** | `SCSS Style Sheet` [x] Track only root files |
| **Scope:** | *Lisa kaust, mille sisu jälgitakse* |
| **Program:** | `sass` |
| **Arguments:** | ´--style compressed --update $FileName$:$ProjectFileDir$/htdocs/css/$FileNameWithoutExtension$.min.css´ |
| **Output paths to refresh:** | `$ProjectFileDir$/htdocs/css/$FileNameWithoutExtension$.min.css:$ProjectFileDir$/htdocs/css/$FileNameWithoutExtension$.min.css.map` |
| **Working directory:** | $FileDir$ |

