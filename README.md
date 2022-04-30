# MBF Classrooms Website

Source of the MBF Classrooms website. See https://eeiitb.github.io/mbfclassrooms/

Built using [MkDocs](https://www.mkdocs.org/) with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

## Updating the site
Follow these steps to update the site.
- Make sure the Material for MkDocs theme is installed. You can install it via `pip install mkdocs-material`. This command will also install MkDocs.
- Run `mkdocs serve` in the directory containing this repository. Any changes to documents can be previewed at `http://127.0.0.1:8000/`
- Commit your changes to the repo via `git add <filenames>` and `git commit -m"Commit message"`. You can also use VSCode to do this step.
- Run `mkdocs gh-deploy --force` to push the changes to Github Pages. The site should be updated in a few minutes.