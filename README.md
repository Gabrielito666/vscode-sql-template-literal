# vscode-sql-template-literal

Syntax highlighting for code like:

```js
const query = sql`SELECT * FROM users`;

//Or with comments so that javascript doesn't crash
const query2 = /*sql*/`SELECT * FROM users`;
```

## Publishing

May require token, stored in last pass. Go to
https://forbeslindesay.visualstudio.com/_details/security/tokens if token needs
regenerating.

```
npm install -g vsce
vsce publish
```