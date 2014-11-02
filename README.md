bem-font (dev) [![Build Status](https://travis-ci.org/voischev/bem-font.svg?branch=master)](https://travis-ci.org/voischev/bem-font)
========

В этой библитеке мы постараемся собрать самый лучший набор открытых веб-шрифтов. 
Так же упор будет сделан на скорость загрузки шрифтов.

## Использование в bem проектах

Подключить в сборку проекта в make файле.

Подключение в deps.js
На примере подключения шрифтов для всего проекта в блоке `page`
```js
({
    mustDeps : [
        { block : 'font', elem : 'grands' },
        { block : 'font', elem : 'futurafuturis', mods : { face : 'light'} },
        { block : 'font', elem : 'pt-sans', mods : { face : ['regular', 'bold', 'italic']} }
    ],
    shouldDeps : []
})
```


## Fonts

- [Grands](http://grawl.github.io/Grands/) (social icons)
- PT Sans 


## Поддержка браузерами 

Шрифты в формате [WOFF](http://caniuse.com/#search=woff) зашифрованы в [BASE64](http://caniuse.com/#search=base64) сейчас поддерживаются всеми последними версиями браузеров, кроме Opera-Mini.
