# clipboard-cli

> Access the system clipboard (copy/paste) - cross-platform

Supports: macOS, Windows, Linux, OpenBSD, FreeBSD, Android with [Termux](https://termux.com).

_NOTE: This is a fork of the original [`clipboard-cli`][0] and is only used for distribution purposes. [I'll][2] do my best to automate it so it's always in sync with the upstream [branch][1]._

## Install

```shell
npm install --global clipboard-cli
```

## Usage

```
$ clipboard --help

  Example
    $ echo 🦄 | clipboard
    $ clipboard
    🦄
```

## Tip

Run it with `$ cb` instead by adding `alias cb=clipboard` to your `.zshrc`/`.bashrc`.

## Related

- [clipboardy](https://github.com/sindresorhus/clipboardy) - API for this module

[0]: https://github.com/sindresorhus/clipboard-cli
[1]: https://github.com/sindresorhus/clipboard-cli/tree/main
[2]: https://4lch4.dev
