# atom-config

## Set up

```
$ sudo apt update
$ sudo apt install atom
$ cd ~/.atom
$ git clone https://github.com/windy1/atom-config
$ cp -r atom-config/. .
$ rm -rf atom-config
$ chmod +x pre-commit
$ cp pre-commit /.git/hooks
$ apm install --packages-file packages.txt
```
