# WordPress related stuff

## Use WordPress CLI to find and replace strings in database

Instead of editing the .sql file in a text editor it's better to use the CLI tool that WordPress provides.

```sh
wp search-replace 'https://project.ddev.site' 'https://real-life-domain.xyz'
```
