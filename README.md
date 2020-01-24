# atom-config

## Set up

```
$ sudo apt update
$ sudo apt install atom
$ git clone https://github.com/windy1/atom-config ~/.atom
$ cd ~/.atom
$ apm install --packages-file packages.txt
```

## Generate package list

```
$ cd ~/.atom
$ ls packages | xargs -n 1 echo | cut -d/ -f1 > packages.txt
```
