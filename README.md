# My UltiSnips Snippets
Here is a collection of my UltiSnips snippets.
These may be helpful for typesetting math in LaTeX or generating templates for code.

## UltiSnips
Refer to [SirVer/UltiSnips](https://github.com/sirver/UltiSnips) to install UltiSnips.

## Installation
Run
```bash
git clone https://github.com/sudoerena/my-snippets.git
```
or download the zip file.

### Vanilla Vim
Move root directory or `*.snippets` under `~/.vim/my-snippets/`, and put 
```vim
let g:UltiSnipsSnippetDirectories=['my-snippets']
```
in your `.vimrc`. 

### NeoVim
Move root directory or `*.snippets` under `~/.config/nvim/my-snippets/`, and put 
```vim
let g:UltiSnipsSnippetDirectories=['my-snippets']
```
in your `init.vim`. 

## Customization
To create new directories for snippets, make sure they are located where vim will check.
Edit your `.vimrc` as above.

Additional snippet files for the same filetype can be created by prepending `_*` or `/*` before `.snippets`.
E.g. `tex.snippets`, `tex_my.snippets`, and `tex/01.snippets` will all be sourced as distinct `tex` snippet files.

## Credits
A number of LaTeX math snippets (fractions, auto-sub/superscript, sympy, among others) are sourced from [Gilles Castel's post](https://castel.dev/post/lecture-notes-1/).
Check out his github at [gillescastel](https://github.com/gillescastel).
