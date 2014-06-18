# serverspec-snippets

This is vim snippets for [Serverspec](http://serverspec.org/).

<p><a href="http://vimeo.com/98406679">serverspec-snippets</a> from <a href="http://vimeo.com/glidenote">glidenote</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
<a href="http://vimeo.com/98406679"><img src="http://i.vimeocdn.com/video/479112148_640.jpg"/></a>

## Requirement

 * [Shougo/neosnippet.vim](https://github.com/Shougo/neosnippet.vim)

## Install

### Vundle

1. Setup the [vundle](https://github.com/gmarik/vundle) package manager
2. Set the bundles for [serverspec-snippets](https://github.com/glidenote/serverspec-snippets)

``` vim
Bundle 'glidenote/serverspec-snippets'
```

3. Open up Vim and start installation with `:BundleInstall`

### Neobundle

1. Setup the [neobundle](https://github.com/Shougo/neobundle.vim) package manager
2. Set the bundles for [serverspec-snippets](https://github.com/glidenote/serverspec-snippets)

``` vim
NeoBundle 'glidenote/serverspec-snippets'
```

3. Open up Vim and start installation with `:NeoBundleInstall`

## Setup

Set serverspec-snippets directory(`~/.vim/bundle/serverspec-snippets`) in your .vimrc.


``` vim 
" setting example
let g:neosnippet#snippets_directory = [
      \'~/.vim/snippets',
      \'~/.vim/bundle/serverspec-snippets',
      \]
```

### Usage

open Serverspec files and set filetype `ruby.serverspec`

``` vim
:set ft=ruby.serverspec
```

## License

Lcense: Same terms as Vim itself (see [license](http://vimdoc.sourceforge.net/htmldoc/uganda.html#license))
