# フロントエンド ボイラープレート

## Sass
- 依存なし

```bash
$ yarn add --dev sass
```

## ESLint
- 依存なし

```bash
$ yarn add --dev eslint eslint-config-standard eslint-plugin-jest
```

## TypeScript
- ESLint に依存

```bash
$ yarn add --dev typescript @types/node @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

## Jest
- TypeScript に依存

```bash
$ yarn add --dev jest ts-jest @types/jest
```

## Prettier
- ESLint に依存

```bash
$ yarn add --prettier eslint-config-prettier
```

## Stylelint
- Sass に依存

```bash
$ yarn add --dev stylelint stylelint-config-standard-scss stylelint-config-recess-order postcss
```

## Cypress
- ESLint に依存

```bash
$ yarn add --dev cypress eslint-plugin-cypress
```