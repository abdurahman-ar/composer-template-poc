# composer-template-poc
poc for making a composer template that creates somthing (we gonna see)

## How to use
```bash
composer create-project abdurahman-ar/composer-template-poc <project name>
```
note: if composer couldn't find it use the following command
```bash
composer create-project --repository="{\"type\": \"vcs\", \"url\": \"https://github.com/author/repo-name.git\"}" --stability=dev abdurahman-ar/composer-template-poc <project name>
```


## How to use cliApp
```bash
cd ./<project root dir>
php cliApp
```
