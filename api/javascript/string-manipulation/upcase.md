---
layout: api-command
language: JavaScript
permalink: api/javascript/upcase/
command: upcase
io:
    -   - string
        - string
related_commands:
    downcase: downcase/
    match: match/
    split: split/
---

# Command syntax #

{% apibody %}
string.upcase() &rarr; string
{% endapibody %}

# Description #

Upcases a string.

__Example:__

```js
r.expr("Sentence about LaTeX.").upcase().run(conn, callback)
```

Result:

```js
"SENTENCE ABOUT LATEX."
```
