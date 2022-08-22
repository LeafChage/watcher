# watcher
common hot reloader

## Install
```
curl https://raw.githubusercontent.com/LeafChage/envy/main/envy > ./envy
chmod +x ./envy
```

## How to use
```sh
$ watcher help
watcher common hot reloader

EXAMPLE:
  watcher php -S localhost:8080

DESCRIPTION:
  When you change your file, restart command.
  If you want to specify ignore file, you should put .watchignore on c
```

## Example
```sh
# A terminal
$ watcher php -S localhost:8080
> PHP 8.1.7 Development Server...

# B terminal
$ echo "hello" >> ./README.md

# A terminal
> Rerun!!!
> PHP 8.1.7 Development Server...
```