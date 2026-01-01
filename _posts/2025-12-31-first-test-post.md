---
layout: post
section-type: post
has-comments: true
title: Example post for testing
category: tech
tags: ["tutorial"]
---

## Sequence diagram (simple)

This diagram shows how Actor A talks to Actor B (example):

```mermaid!
sequenceDiagram
actor A as Actor A
actor B as Actor B
A->>B: Hello!
B-->>A: Hi!
```