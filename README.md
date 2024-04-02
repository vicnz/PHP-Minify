# PHP-Minify
A simple PHP code minifier, written in PHP and executed as a windows (.exe) command line system.
Minifier Engine is forked from this repository [PHP Minify](https://github.com/basselin/php-minify).

### Download
Download the (.exe) app from the release page. [minifier.exe](https://github.com/vicnz/PHP-Minify/releases/).

### USAGE
```cmd
minifier.exe [arguments]
minifier.exe --source=./ --target=./dist/
```
### OPTIONS
| options | example |
|-|-|
| `--source` | `--source=./` `--source=./app/` |
| `--target` | `--target=./dist/` |
| `--banner` | `--banner="comments prepended to the minified code"` |
| `--extensions` | `--extension="php,phtm,inc"` |
| `--excludes` | `--excludes="md,js,css"` |
