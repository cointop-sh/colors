# cointop colors

> Standard colorschemes (themes) for [cointop](https://github.com/miguelmota/cointop/)

[![License](http://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/cointop-sh/colors/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

## Contents

- [Installation](#installation)
- [Colorschemes](#colorschemes)
- [Contributing](#contributing)
- [FAQ](#FAQ)
- [License](#license)

## Installation

Clone into config directory:

```bash
$ cd ~/.cointop
$ git clone git@github.com:cointop-sh/colors.git
```

Edit `~/.config/cointop/config.toml` and set colorscheme:

```toml
colorscheme = "matrix"
```

## Colorschemes

In alphabetical order:

### [cointop](./cointop.toml)

<img width="900" alt="cointop" src="https://user-images.githubusercontent.com/168240/115508779-906c1900-a232-11eb-8123-f5e39e15394f.png">

### [crimson](./crimson.toml)

<img width="900" alt="crimson" src="https://user-images.githubusercontent.com/168240/115508821-99f58100-a232-11eb-9349-77b4d534c3be.png">

### [grayscale](./grayscale.toml)

<img width="900" alt="grayscale" src="https://user-images.githubusercontent.com/168240/115508856-a11c8f00-a232-11eb-9a71-8e2ff87c3392.png">

### [homebrew](./homebrew.toml)

<img width="900" alt="homebrew" src="https://user-images.githubusercontent.com/168240/115508886-a8439d00-a232-11eb-9c66-c4b81eeb8954.png">

### [iceberg](./iceberg.toml)

<img width="900" alt="iceberg" src="https://user-images.githubusercontent.com/168240/115508907-af6aab00-a232-11eb-9395-320344632eaa.png">

### [mars](./mars.toml)

<img width="900" alt="mars" src="https://user-images.githubusercontent.com/168240/115508943-b98ca980-a232-11eb-93d1-963a5282aebb.png">

### [matrix](./matrix.toml)

<img width="900" alt="matrix" src="https://user-images.githubusercontent.com/168240/115508997-c7dac580-a232-11eb-8c6f-3994dc2f59d1.png">

### [synthwave](./synthwave.toml)

<img width="900" alt="synthwave" src="https://user-images.githubusercontent.com/168240/115509029-ce693d00-a232-11eb-9cbc-1915c4e7abd0.png">

### [system](./system.toml)

Uses system default color.

<img width="850" alt="system" src="https://user-images.githubusercontent.com/168240/116793901-6d393900-aa7e-11eb-8a78-7428b5a4ec6d.png">

### [xray](./xray.toml)

<img width="900" alt="xray" src="https://user-images.githubusercontent.com/168240/115509042-d45f1e00-a232-11eb-9a2d-29bf6fbd8c6f.png">

## Contributing

If you have a cool and unique theme that you'd like to share, please fork and submit a PR!

Supported colors are:

- `black`
- `blue`
- `cyan`
- `green`
- `magenta`
- `red`
- `white`
- `yellow`
- `default` - system default

<!-- - xterm display hex colors; view [cheat sheet](https://jonasjacek.github.io/colors/) -->

## FAQ

- Q: Why don't colorschemes support RGB or hex colors?

  - A: Some of the cointop underlying rendering libraries don't support true colors. See [issue](https://github.com/nsf/termbox/issues/37).

## License

[MIT](LICENSE)