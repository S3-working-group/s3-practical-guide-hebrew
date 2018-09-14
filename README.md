# S3 Practical Guide (Hebrew Version)

The Hebrew translation of "Sociocracy 3.0 Practical Guide""

## Build Process

* add translated files from [S3 Practical Guide Crowdin project](https://crowdin.com/project/sociocracy-30)  to `content`
* use [illustration translations](https://crowdin.com/project/sociocracy-30-illustrations) to translate illustrations and copy translated illustrations to `img` 
* update version number in `config/project.yaml`
* run buildscript (`build.sh`)
* to make pdf, run `make single` and make a pdf from `docs/_site/all.html`
