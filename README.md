# UltiSnips Snippets
Here is a repository for easy access of my UltiSnips snippets.
These may be helpful for typesetting math in LaTeX or generating templates for code.

## UltiSnips
Refer to [SirVer/UltiSnips](https://github.com/sirver/UltiSnips) to install UltiSnips.

## Installation
Run
```bash
git clone https://github.com/sudoerena/my-snippets
```

Copy contents to a directory discoverable by vim (`~/.vim/UltiSnips/`) or nvim (`~/.config/nvim/UltiSnips/`), or softlink with `ln` to allow for updates.

## Customization
Edit the files in your local directory with desired changes, or create a new discoverable directory (`~/.vim/MySnips/`; `~/.config/nvim/MySnips/`).
Add the following to your `.vimrc` or `init.vim`:
```vim
let g:UltiSnipsSnippetDirectories=['UltiSnips', 'MySnips']
```

## Credits
A number of LaTeX math snippets (fractions, auto-sub/superscript, sympy, among others) are sourced from [Gilles Castel's post](https://castel.dev/post/lecture-notes-1/).
Check out his github at [gillescastel](https://github.com/gillescastel).
