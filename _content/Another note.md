---
public: true
---


dataviewjs block outside of callout:
<span><span><p dir="auto">Another note</p></span></span>

> [!NOTE] Title
>  dataviewjs block with > character on each line
> <pre class="dataview dataview-error">Evaluation Error: SyntaxError: Unexpected token '&gt;'
    at DataviewInlineApi.eval (plugin:dataview:18885:21)
    at evalInContext (plugin:dataview:18886:7)
    at asyncEvalInContext (plugin:dataview:18896:32)
    at DataviewJSRenderer.render (plugin:dataview:18922:19)
    at DataviewJSRenderer.onload (plugin:dataview:18464:14)
    at e.load (app://obsidian.md/app.js:1:1166456)
    at DataviewApi.executeJs (plugin:dataview:19465:18)
    at DataviewCompiler.dataviewJS (plugin:obsidian-mkdocs-publisher:14548:22)
    at convertDataviewQueries (plugin:obsidian-mkdocs-publisher:14630:39)
    at async mainConverting (plugin:obsidian-mkdocs-publisher:15055:10)</pre>


