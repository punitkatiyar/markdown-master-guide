# Mermaid Diagrams in Markdown

**Mermaid is a JavaScript-based diagramming tool that lets you create flowcharts, UML diagrams, sequence diagrams, Gantt charts, ER diagrams, mind maps, and more using simple text inside Markdown.**

## Why Use Mermaid?

- ✅ Easy to write
- ✅ Version control friendly
- ✅ Works with GitHub, GitLab, Obsidian, Notion (limited), VS Code
- ✅ Great for documentation
- ✅ No need to use drawing software
- ✅ Easy to update

```mermaid
flowchart LR
A[Input]
B(Run)
C{Success?}
D[(Database)]
E((End))
A --> B
B --> C
C --> D
D --> E
```



```mermaid
flowchart LR
A[Rectangle]
B(Rounded)
C((Circle))
D{Decision}


A --> B
B --> C
C --> D
D --> E

```

