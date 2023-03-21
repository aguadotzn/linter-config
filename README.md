# Linter configuration 🔦

This repository contains several configurations for linters, formatters or others useful tools to improve your codebase.

## Basic config (TS projects)
By default, I installed the following stuff for my typescript projects

```
# ESLint
npm install --save-dev eslint

# Extra plugins 
npm install --save-dev @typescript-eslint/eslint-plugin eslint-plugin-prettier

# Prettier and dependencies
npm install --save-dev prettier prettier-eslint eslint-config-prettier
```
What's being installed?
- `eslint` is the main ESLint library, the core.
- `@typescript-eslint/eslint-plugin` is a plugin that contains a bunch of TypeScript-specific rules.
- _Prettier_ is the Prettier library, nothing else.
- `eslint-config-prettier` helps us to disable all ESLint rules that may conflict with Prettier
- `eslint-plugin-prettier` runs Prettier as an ESLint rule.
  
### Extra (Testing)
I also try to install [ESLint for Jest](https://www.npmjs.com/package/eslint-plugin-jest)

## License

This source content is licensed under the _MIT License_ - see the [LICENSE](LICENSE.md) for details.

---

Authored and maintained by [Adrián Aguado](https://github.com/aguadotzn). Copyright © 2023.

> For any inquiries, you can contact me on [Twitter](https://twitter.com/aguadotzn).
