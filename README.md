# WebFont Exo 2 Condensed

Пакет для установки веб-шрифта: Exo 2 Condensed.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-exo2-condensed
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-exo2-condensed": "github:getscope/npm-webfont-exo2-condensed"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Exo 2 Condensed', sans-serif;
}
```

Для импорта веб-шрифта в `SCSS`, Вы можете воспользоваться следующими путями:

#### Импорт начертаний `normal`

```scss 
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_all-normal.scss";
```

или

```scss 
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_100-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_200-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_600-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_800-normal.scss";
@import "node_modules/@getscope/npm-webfont-exo2-condensed/src/scss/_900-normal.scss";
```
