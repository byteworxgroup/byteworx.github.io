# byteworx.github.io

Company website

## Getting started

build the site with command: <br><br>`hugo`

deploy site locally with command: <br><br>`hugo server -w --disableFastRender`<br>
<br>this enables auto reload on file changes and more consistent renders.

## Notes
Never modify something in folder public since it is rendered on running the `hugo` command.
<br>
<br>
the`config.toml` file contains most params which are used in `layouts/partials/**` files.
<br><br>The`config.toml` file also contains route definitions.
<br><br> In the same location `index.html` composes all the other pages.
<br><br>When you add a parameter make sure you specify the key in the `i18n` folder and use the parameter by doing: <br>
`{{ i18n "learnmore" }}` in a template file.