Headers
-------
```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Header 1
========
Header 2
--------
```

Lines
-----
```markdown
***
---
___
```

Text
----
```markdown
**bold**
*italic*
~~strike~~

> Quotation
```

Lists
-----
```markdown
1. Item 1
1. Item 2
    - Item 2.1
    - Item 2.2

- [x] Item 1
- [-] Item 2
- [ ] Item 3
    - [ ] Item 3.1
    - [ ] Item 3.2
```

Links
-----
```markdown
https://github.com
[GitHub](https://github.com)

[Link]
[Link][1]

[Link]: https://github.com
[1]: https://github.com
```

Images
------
```markdown
![Image1](URL)

![Image2]
[Image2]: URL

[![Image3](URL)](https://github.com)
```

Code
----
```markdown
```python
import random
x = 10
```
```

Footnotes
---------
```markdown
This is a footnote[^1]. Another footnote[^2].

[^1]: Reference 1
[^2]: Reference 2
```

Tables
------
```markdown
| Left  | Center | Right   |
| ----- | :----: | ------: |
| One   | Two    | $10.00  |
| Three | Four   | $9.00   |
```

Collapsed Details
-----------------
```markdown
<details>
<summary>Title for the collapsed block</summary>
Some hidden text
</details>
```
<details>
<summary>Title for the collapsed block</summary>
Some hidden text
</details>
 
Special Additions
-----------------
`#` - tag git entity

`@` - tag person

`\` - escape character

`:` - paste emoji

Alerts
------
```markdown
> [!NOTE]
> Note text

> [!IMPORTANT]
> Important text

> [!WARNING]
> Warning
```
> [!NOTE]
> Note text

> [!IMPORTANT]
> Important text

> [!WARNING]
> Warning

Graphs
------
```markdown
graph TD;
    A-->B;
    A-->C;
```
