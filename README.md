font-menlo-extra
================

### What?
`Menlo Regular`, patched to support glyphs from FontAwesome, Powerline, Octicons and more.

### Why?
As I found, [everyone](https://github.com/gabrielelana/awesome-terminal-fonts) [else](https://github.com/ryanoasis/nerd-fonts) uses `Meslo` - customized version of `Menlo` with 'fixed' verical line spacing and changes baseline alignment of asterisk.

As for me, I like original `Menlo` spacings and aligns, so I decided to stick with original `Menlo`, but to patch it to add support for glyphs and icons from other modern and popular libs/collections.

### Used icons/collections
+ Font Awesome (+ andrelzgava/font-awesome-extension)
+ Material Design Icons
+ Octicons
+ Powerline (inc. ryanoasis/powerline-extra-symbols)
+ Pomicon
+ Weather Icons
+ IEC Power Symbols
+ Font Linux

### Who is who (versions)
+ `*-Full` - version with all icons and glyphs.
+ `*-Normal` - version with added `powerline`(with ext), `font awesome`(with ext) and `octicons`.
+ `*-FullV2` - same version as `*-Full`, but with aligned `powerline` glyphs.
+ `*-NormalV2` - same version as `*-Normal`, but with aligned `powerline` glyphs.
+ `*-Mono` - same version, but in monospace variant (with single-width glyphs).

### Can I preview these glyphs in app like Symbols Viewer?
I guess you can't. These glyphs placed in `Private Use Area` (starting from U+E000) and Symbols Viewer cannot show them.
On OS X, use `Font Book.app`.

Also, you can use helper scripts [from here](https://github.com/ryanoasis/nerd-fonts/tree/master/bin/scripts/lib) to test glyphs in terminal.
