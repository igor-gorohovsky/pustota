# pustota

[pustota](https://ru.wikipedia.org/wiki/%D0%9F%D1%83%D1%81%D1%82%D0%BE%D1%82%D0%B0) is a minimalistic VSCode theme inspired by old-fashioned hobbies.

[Preview it online](https://vscode.dev/editor/theme/sobolevn.pustota) on `vscode.dev` with default settings.

## Core features

- Minimalistic
- Borderless
- High contrast for the needed parts
- Small amount of colors
- Only statically known parts are highlighed

Unlike many other themes, this one only highlights a few things:
1. Comments (`#626A73`) ![#626A73](https://placehold.it/15/626A73/626A73?text=+)
2. Strings (`#C2D94C`) ![#C2D94C](https://placehold.it/15/C2D94C/C2D94C?text=+)
3. Constants (`#E6B450`) ![#E6B450](https://placehold.it/15/E6B450/E6B450?text=+)
4. Keywords and operators (`#FF8F40`) ![#FF8F40](https://placehold.it/15/FF8F40/FF8F40?text=+)
5. Function definitions (`#FFB454`) ![#FFB454](https://placehold.it/15/FFB454/FFB454?text=+)
6. Type definitions (`#59C2FF`) ![#59C2FF](https://placehold.it/15/59C2FF/59C2FF?text=+)

Everything else is just white (`#B3B1AD`) ![#B3B1AD](https://placehold.it/15/B3B1AD/B3B1AD?text=+)

Basically, this is it.

Pairs greatly with [`FiraCode`](https://github.com/tonsky/FiraCode) font and [`sobole`](https://github.com/sobolevn/sobole-zsh-theme) theme for ZSH.

This theme does not include an icon theme, so you can use any:
- `Ayu` has a great one that I am using
- `Seti` - the default one - is also fine

You can also check my [`.dotfiles`](https://github.com/sobolevn/dotfiles) with the whole setup.

## Installation

[Install it from the official website](https://marketplace.visualstudio.com/items?itemName=sobolevn.pustota) or install it with CLI: `code --install-extension sobolevn.pustota`

And then choose `Preferences: Color Theme` to be `"pustota"`.

## Supported languages

This theme [supports a lot of languages](https://github.com/pustota-theme/pustota/tree/master/test), starting from mainstream ones
like Python, TypeScript, and Java.
And ending with languages like Elixir, Lisp, and Haskell.

If you want to contribute a language support, please feel free!
It is quite easy to do, since there are only 5 major colors :)

## Ports

- Neovim port is available at [pustota.nvim](https://github.com/igor-gorohovsky/pustota.nvim).

## Showcase

Theme with [my VSCode settings](https://github.com/sobolevn/dotfiles/tree/master/vscode):

![minimal](https://raw.githubusercontent.com/pustota-theme/pustota/master/assets/minimal.png)

![main](https://raw.githubusercontent.com/pustota-theme/pustota/master/assets/main.png)

Theme with default VSCode settings:

![default](https://raw.githubusercontent.com/pustota-theme/pustota/master/assets/default.png)

![default-terminal](https://raw.githubusercontent.com/pustota-theme/pustota/master/assets/default-terminal.png)

## Recommended settings

[Full list of the settings I use](https://github.com/sobolevn/dotfiles/blob/master/vscode/settings.json).

Major ones:
- `"editor.semanticHighlighting.enabled": false` to turn off semantic syntax
- `"editor.matchBrackets": "never"` to turn off parens highlight

## Thanks to

- [Ayu Dark](https://github.com/ayu-theme/vscode-ayu) which was the main source of the style and colors (and even some tests)
- [Alabster](https://github.com/tonsky/vscode-theme-alabaster) for the concept of "small visual noise"
