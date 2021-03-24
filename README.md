# WebPageToEpub
For learn how to work go-docker library and I used the pandoc docker image to convert web pages into an epub.

I highly recommend that you use better the pandoc tool instead of my library for this purpose.

## Install

```sh
$ go get github.com/stescobedo/WebPageToEpub
```

## How to use

```
A simple tool to convert web pages into epub

Usage:
  pageToepub [command]

Available Commands:
  convert     Convert output into a epub file
  help        Help about any command

Flags:
  -h, --help   help for linkstobook

Use "pageToepub [command] --help" for more information about a command.
```

ex
```sh
$ pageToepub convert --web https://blog.friendsofgo.tech/posts/crear-tu-primer-cli-en-go/,https://blog.friendsofgo.tech/posts/dockerizando-tu-aplicacion-en-go/
```
