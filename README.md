# wren-colors

Print fancy messages to the terminal. Until Wren supports importing you'll have
to copy `colors.wren` into your source file and create new instances of
`AnsiPrinter` to get colored logging.

```dart
var a = new AnsiPrinter(AnsiColors.BLUE, AnsiColors.WHITE_B, AnsiColors.BLINK)
a.print("This text should be blue on a white background and blink.")

var b = new AnsiPrinter(AnsiColors.BLUE, AnsiColors.WHITE_B)
b.print("This text should be blue on a white background.")

var c = new AnsiPrinter(AnsiColors.BLUE)
c.print("This text should be blue.")
```