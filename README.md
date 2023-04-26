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
$ yarn add --dev typescript ts-node @types/node @typescript-eslint/eslint-plugin @typescript-eslint/parser
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

## Storybook
- TODO: やる

## reg-suit
- TODO: やる

## Next.js
- TODO: やる
- Next に限らないほうがいいけど、現実的に Next が第一候補になるから Next でいいか
  - 他のフレームワークの場合でも改変すればいけるだろう
