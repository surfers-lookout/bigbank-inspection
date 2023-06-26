# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "bsGitRepository" : "github.com?owner=surfers-lookout&repo=bigbank-inspection",
  "gitopsAccount" : "davlloyd",
  "gitopsEmail" : "davidlloyd@gmail.com",
  "gitopsEnabled" : false,
  "pageColor" : "green",
  "projectName" : "bigbank-inspection"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/*]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug tests/unit/test_models.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml, mkdocs.yml, techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [bigbankloanaccelerator->bigbank-inspection]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [https://github.com/surfers-lookout/bigbank-accelerator-kyc->https://github.com/s...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Condition (#gitopsEnabled) evaluated to false
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[3] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [value: blue->value: green, : bigbankloanaccelerator->: bigbank-inspection]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [BigBankLoanAccelerator->bigbank-inspection, bigbank-loan-accelerator->bigbank-inspection, bigbankloanaccelerator->bigbank-inspection]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [surfers-flask-accelerator->bigbank-inspection, bigbankloanaccelerator->bigbank-inspection]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mkdocs.yml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml matched [mkdocs.yml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [mkdocs.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [bigbankloanaccelerator->bigbank-inspection]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [https://github.com/surfers-lookout/bigbank-accelerator-kyc->https://github.com/s...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[6].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[6].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [techdocs_publish.sh]
┃ ┃ ┃ ┃ ┃ ┃ Debug .DS_Store didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/kyc_process.svg didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/.DS_Store didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/.DS_Store didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/pagelayout.css didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/bb-logo.png didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh matched [techdocs_publish.sh] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/.DS_Store didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [techdocs_publish.sh] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[6].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [kyc->bigbank-inspection]
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
