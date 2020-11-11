# NordBuddy

A Nordic  inspired dark and light colorscheme using [tjdevries/colorbuddy.vim](https://github.com/tjdevries/colorbuddy.vim)

This plugin is also an example of how easy it is to customize and make new colorschemes based on `colorbuddy`.

Check out [`lua/onebuddy.lua`](lua/onebuddy.lua)

A Fork of  [Th3Whit3Wolf/onebuddy](https://github.com/Th3Whit3Wolf/onebuddy) colorscheme

## Screenshots

TODO ::

Dark theme

![dark theme](assets/dark.png)

Light theme

![light theme](assets/light.png)

*Font:* Space Mono
*Statusline:* lightline

### Getting Started

You have to make sure you install [tjdevries/colorbuddy.vim](https://github.com/tjdevries/colorbuddy.vim) Only termguicolors are supported and that will not change.

#### Vim Plug

```vim
Plug 'tjdevries/colorbuddy.vim'
Plug 'adishourya/nordbuddy'

" And then somewhere in your init.vim, to set the colorscheme
lua require('colorbuddy').colorscheme('nordbuddy')
```


### NOTE

- Vim is not supported because the theme is written in lua.
- If you feel like a language should be highlighted differently please open an issue.

### TODO

- [ ] Better LSP Highlighting
- [ ] Better Diagnostic Highlighting
- [x] Better Tree Sitter Highlighting
