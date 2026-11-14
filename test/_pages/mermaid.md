---
title: "Mermaid Diagrams"
layout: single
permalink: /mermaid/
---

Mermaid code fences render automatically without a front matter setting.

## Flowchart

```mermaid
flowchart LR
  A[Write Markdown] --> B[Build with Jekyll]
  B --> C[Render diagram in the browser]
```

## Sequence diagram

```mermaid
sequenceDiagram
  accTitle: Request and response
  accDescr: A visitor requests a page and the server returns HTML.
  Visitor->>Server: Request page
  Server-->>Visitor: HTML & assets
```

## Regular code

This JavaScript block should remain a code block:

```javascript
const message = "Mermaid diagrams render alongside regular code blocks.";
```
