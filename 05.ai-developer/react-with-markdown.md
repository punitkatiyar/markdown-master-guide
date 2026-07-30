# React With Markdown

> npm install react-markdown

```javascript
import ReactMarkdown from "react-markdown";

function App() {
  const markdown = `
# React Markdown

**Hello World**

- Python
- React
- Node
`;

  return <ReactMarkdown>{markdown}</ReactMarkdown>;
}

export default App;

```
