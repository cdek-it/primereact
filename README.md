### Чтобы добавить шрифты
Указываем шрифты в `_fonts.scss` в формате
```scss
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-display: swap;
  font-weight: 400;
  src: url(./fonts/roboto-cyrillic-ext-400-normal.woff2) format('woff2'), url(./fonts/roboto-cyrillic-ext-400-normal.woff) format('woff');
  unicode-range: U+0460-052F,U+1C80-1C8A,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F;
}
```

Далее запускаем баш скрипт `./copy-fonts.sh`, которые положит указанные шрифты в папку
