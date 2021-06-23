# The ELSAToolbox Package

The `elsatoolbox` package loads several commonly used packages, which makes preparing LaTeX documents easier. One can access the user manual of this package through `user-manual/main.pdf`, where the draft and the supplementary material can be accessed by `user-manual/main.drft.pdf` and `user-manual/supp.pdf`, respectively.

## Quickstart

1. Copy the style file `elsatoolbox.sty` to your LaTeX project.
2. Use the `elsatoolbox`package by adding `\usepackage{elsatoolbox}`.

## Provided Options

There are four options that users can use to control the behavior of `elsatoolbox`.

### `draft`

The `elsatoolbox` package provides an option for enabling draft mode. To enable it, add the option `draft` to `elsatoolbox` as the following:

```latex=
\usepackage[draft]{elsatoolbox}
```

After the draft mode is enabled, the following features are turned on:

- **Draft Mode** showing at the top of each page
- FiXme annotations
- The list of corrections showing on the first page
- Colored hyperlinks

### `noalgo`

The `elsatoolbox` package loads the `algorithm2e` package. In order to disable it, add the option `noalgo` to `elsatoolbox` as the following:

```latex=
\usepackage[noalgo]{elsatoolbox}
```

### `nosubcap`

The `elsatoolbox` package loads the `subcaption` package. In order to disable it, add the option `nosubcap` to `elsatoolbox` as the following:

```latex=
\usepackage[nosubcap]{elsatoolbox}
```

### `nosetspace`

The `elsatoolbox` package loads the `setspace` package. In order to disable it, add the option `nosetspace` to `elsatoolbox` as the following:

```latex=
\usepackage[nosetspace]{elsatoolbox}
```

## Loaded Packages

|`inputenc`|`microtype`|`atbegshi`|`etoolbox`|`tikz`|
|---|---|---|---|---|
|`algorithm2e`|`fixme`|`zref`|`afterpage`|`graphicx`|
|`subcaption`|`hyperref`|`amssymb`|`amsthm`|`bbm`|
|`mathrsfs`|`mathtools`|`xfrac`|`setspace`|`array`|
|`booktabs`|`multicol`|`multirow`|`tabu`|`tabularx`|
|`tabulary`|

## Reference

[View this project on ELSA LaTeX](https://elsa-latex.cs.nthu.edu.tw/read/ftdgjyffhwms)
