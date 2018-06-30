# Padrão de configuração do Prettier - Cubos

## Como usar

Execute `yarn add -D @cubos/prettier` e então inclua a seguinte propriedade no seu `.prettierrc.js`:
```js
const defaultConfig = require("@cubos/prettier");

module.exports = {
    ...defaultConfig,
    // aqui suas customizações
};
```