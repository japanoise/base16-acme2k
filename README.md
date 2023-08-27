# base16-acme2k

Templates for generating a base16 colorscheme C header for use with
[acme2k][acme2kUpstream], or [forks thereof][acme2kforks].

## Usage

1. Build using your builder of choice (I like the [Go][gobuilder] one)
2. Header files should be created in the directory `acme2k/`
3. Copy your chosen header into your acme source tree
4. Replace the color block in `config.h` with your chosen theme, e.g.:

```c
#include "base16-snazzy.h"
```

Finally, recompile acme using `mk install`.

## Copying

Licensed MIT.

[acme2kUpstream]: https://github.com/karahobny/acme2k
[acme2kforks]: https://github.com/japanoise/acme2k
[gobuilder]: https://github.com/tinted-theming/base16-builder-go
