# Glesys Bash Client

## Instructions
- Set config in `./config`
- Template path is not required, you can use the default ones.
- Options path will be required, so you can customize your requests: i.e. `./glesys send server/create ./custom-options/server/create-medium-8core-projectX`
- Both will be inferred based on the url parameter if omitted.
- `Are you sure? [Y/n]:` Bypassed by adding a `Y` as the 5th parameter.

## Usage
`./glesys <show|send|help> <url> <options> <template> <Y>`

## Examples
```
./glesys help
./glesys help server/create
./glesys show server/create
./glesys show server/create ./custom-options/server/create
./glesys send server/create ./custom-options/server/create ./custom-templates/server/create
```

## Todo
- Changing content type not yet supported, and probably won't be.

## Links
- https://github.com/GleSYS/API
- https://google.github.io/styleguide/shell.xml
- http://kvz.io/blog/2013/11/21/bash-best-practices/
