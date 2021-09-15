# S8 ESlint

Конфигурация всех линтеров через package.json:

```
{
    "prettier": "s8-eslint/prettier",
    "eslintConfig": {
        "extends": "./node_modules/s8-eslint/eslint/index.js"
    },
    "stylelint": {
        "extends": "s8-eslint/stylelint"
    },
    "commitlint": {
        "extends": ["./node_moduless8-eslint/commitlint"]
    }
}
```
