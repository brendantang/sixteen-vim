# sixteen.vim

Have VIM use the 16 ANSI colors defined in your terminal theme so that it matches other output.

Largely copied & simplified from Jeff Kreeftmeijer's [Dim](https://github.com/jeffkreeftmeijer/vim-dim).
  - This is basically just `default-light.vim` from that repo, except that I use `13` ("bright magenta" by ANSI convention) to highlight visual selections instead of inverting colors.
    - `10` (bright green) is also unused, if you want to swap that out as the visual selection color.
    - Unlike `dim.vim`, I don't distinguish between light and dark backgrounds.

Noah Frederick's [noctu](https://github.com/noahfrederick/vim-noctu) is another good choice for this purpose with more testing, but I found it didn't work for me with light backgrounds.

