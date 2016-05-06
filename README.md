### Vim and Angular 2 snippets

Port of [John Papa's VSCode Snippets](https://github.com/johnpapa/vscode-angular2-snippets)

### TypeScript Snippets

```typescript
ng2-component-root  // Angular 2 root App component
ng2-bootstrap     // Angular 2 bootstraping, for main.ts
ng2-component     // Angular 2 component
ng2-pipe          // Angular 2 pipe
ng2-route-config  // Angular 2 @RouteConfig
ng2-route-path    // Angular 2 routing path
ng2-service       // Angular 2 service
ng2-subscribe     // Angular 2 observable subscription
```

### HTML Snippets

```html
ng2-ngClass
ng2-ngFor
ng2-ngIf
ng2-ngModel
ng2-routerLink
ng2-ngStyle
ng2-ngSwitch
```

### Installation

####[vundle](https://github.com/gmarik/vundle)

    Plugin 'mhartington/vim-angular2-snippets'

to `.vimrc`, and then run `:PluginInstall`.

####[pathogen.vim](https://github.com/tpope/vim-pathogen)

    cd ~/.vim/bundle
    git clone https://github.com/mhartington/vim-angular2-snippets.git

Then reload vim, run `:Helptags`

####[apt-vim](https://github.com/egalpin/apt-vim)

    apt-vim install -y https://github.com/mhartington/vim-angular2-snippets.git

For those who need it, a tarball is available from
[here](https://github.com/mhartington/vim-angular2-snippets/archive/master.zip).

### Note

Only `snipemate` format at the moment. Works with [NeoSnippets](https://github.com/Shougo/neosnippet.vim), my preferred snippets plugin.
If you're up for adding UltiSnips compatibility, feel free to send a PR.
