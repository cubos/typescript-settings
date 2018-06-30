# Padrão de configuração do Typescript - Cubos

## Como usar

Execute `yarn add -D @cubos/tsconfig` e então inclua a seguinte propriedade no seu `tsconfig.json`:
```json
{
    "extends": "./node_modules/@cubos/tsconfig/tsconfig.json"
}
```

Ou, caso seja um projeto web:
```json
{
    "extends": "./node_modules/@cubos/tsconfig/web.tsconfig.json"
}
```