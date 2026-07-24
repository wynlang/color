# color - Official Wyn Package

Named terminal colors. Pure Wyn.

## Install

```bash
wyn pkg install github.com/wynlang/color
```

## Usage

```wyn
import color

println(color.red("Error!"))
println(color.green("Success!"))
println(color.bold(color.blue("Bold blue")))
```

Each helper wraps its argument in an ANSI SGR sequence and a reset, so the
returned string is safe to `println` or concatenate.

Colors: `red green yellow blue magenta cyan white gray`
Styles: `bold dim underline`
