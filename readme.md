# goArtisan

Current project was created use Cobra Generator.
https://github.com/spf13/cobra/blob/master/cobra/README.md

Cobra docs.
https://github.com/spf13/cobra

```
$ cobra -h
$ cobra init artisanCxdTv -a farwish --pkg-name github.com/farwish/goArtisan
```

## Create command

```
$ cobra add -h
$ cobra add [command name] [flags]
```

## Run command

```
$ go run main.go [command name]
```

## Cobra behavior config ( default: $HOME/.cobra.yml )

https://github.com/spf13/cobra/blob/master/cobra/README.md#configuring-the-cobra-generator

for example:
```
author: ethan <farwish@foxmail.com>
year: 2020
license:
  header: This file is part of CLI application.
  text: |
    {{ .copyright }}
```

## Cobra cmd application config ( default: $HOME/.goArtisan.yml )

See in cmd/root.go

## Apply ide code completion

```
$ go mod download
```
