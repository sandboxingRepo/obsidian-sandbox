---
public: true
---
---
tags:
  - dataviewjstest
name: lorem ipsum
---

dataviewjs block outside of callout:
<span><span><p dir="auto">-</p></span></span>

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
    at async mainConverting (plugin:obsidian-mkdocs-publisher:15052:10)</pre>
>  dataviewjs block with > character only on first and last line of block
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
    at async mainConverting (plugin:obsidian-mkdocs-publisher:15052:10)</pre>
> dataview block with > character on each line
>  | File | name |
> | ---- | ---- |
> 
> dataview block with > character only on first and last line
>  | File | name |
> | ---- | ---- |
> 
> 
> End of testing

