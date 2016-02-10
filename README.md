# eslint-config-pwmckenna

I use the same eslint config on all my projects. This makes it super simple for me to configure .eslintrc. I would recommend __*against*__ anyone else using this. This is kept in sync with [babel-preset-pwmckenna](https://github.com/pwmckenna/babel-preset-pwmckenna) so that eslint enforces the same syntax that babel can compile.

> .eslintrc

```js
{
  "extends": "pwmckenna"
}
```
