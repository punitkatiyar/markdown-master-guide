# Express With Markdown

> npm install marked

```javascript
const { marked } = require("marked");

const markdown = `
# Welcome

This is Markdown.
`;

const html = marked(markdown);

console.log(html);
```
