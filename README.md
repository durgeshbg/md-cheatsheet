# _Headings_

<!-- Headings -->

> Raw:

```markdown
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

> Rendered:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

# _Emphasis_

<!-- Text Emphasis -->

> Raw:

```markdown
This is **bold** text

This is _Itallic_ text

This is **_Itallic & Bold_** text

This is ~~Striked Text~~ text

This is **bold** text
```

> Rendered:

<!-- Bold text -->

This is **bold** text

<!-- Italic text -->

This is _Itallic_ text

<!-- Italic & Bold text -->

This is **_Itallic & Bold_** text

<!-- Striked text -->

This is ~~Striked Text~~ text

<!-- Bold text -->

This is **bold** text

---

# _Block Quote_

<!-- Block quote -->

> Raw:

```markdown
> This is a quote.
>
> > This is a nested quote.

> This is the second line of the quote.
```

> Rendered:

> This is a quote.
>
> > This is a nested quote.

> This is the second line of the quote.

---

# _Horizontal Rule_

<!-- Horizontal rule -->

> Raw:

```markdown
---

---
```

> Rendered:

---

---

# _Comments_

<!-- Comments -->

> Raw:

```markdown
<!-- This is a comment -->
```

> Rendered:

_Comments are not visisble when rendered._

<!-- This is a comment -->

---

# _Lists_

<!-- Lists -->

### _Unordered list_

<!-- Unordered list -->

> Raw:

```markdown
-   Item 1
-   Item 2
    -   This item is nested
-   Item 3
```

> Rendered:

-   Item 1
-   Item 2
    -   This item is nested
-   Item 3

### _Ordered list_

<!-- Ordered list -->

> Raw:

```markdown
1. Item 1
2. Item 2
    1. This item is nested.
3. Item 3
```

> Rendered:

1. Item 1
2. Item 2
    1. This item is nested.
3. Item 3

---

# _Code_

<!-- Code -->

### _Python_

<!-- Python Code -->

> Raw:

````markdown
    ```python
        def sum(a,b):
            return a+b
    ```
````

> Rendered:

```python
    def sum(a,b):
        return a+b
```

### _Bash_

<!-- Bash Script -->

> Raw:

````markdown
    ```bash
    git commit -am "Initial commit."
    ```
````

> Rendered:

```bash
    git commit -am "Initial commit."
```

---

# _Links & Images_

### _Link_

<!-- Link -->

> Raw:

```markdown
[This is a link](https://twitter.com/Durgesh_B_G)
```

> Rendered:

[This is a link](https://twitter.com/Durgesh_B_G)

### _Image_

<!-- Image -->

> Raw:

```markdown
![Alternate Text](./sample.png)
```

> Rendered:

![Alternate Text](./sample.png)

---

# _Table_

<!-- Table -->

> Raw:

```markdown
| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Item 1   | Item 2   | Item 3   |
| Item 4   | Item 5   | Item 6   |
| Item 7   | Item 8   | Item 9   |
```

> Rendered:

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Item 1   | Item 2   | Item 3   |
| Item 4   | Item 5   | Item 6   |
| Item 7   | Item 8   | Item 9   |

---

# _Task List_

<!-- Task List -->

> Raw:

```markdown
-   [x] Task 1
-   [x] Task 2
-   [ ] Task 3
-   [x] Task 4
-   [ ] Task 5
-   [ ] Task 6
```

> Rendered:

-   [x] Task 1
-   [x] Task 2
-   [ ] Task 3
-   [x] Task 4
-   [ ] Task 5
-   [ ] Task 6

---

# _Heading IDs_

<!-- Linking headers in a same page -->

> Raw:

```markdown
[Headings](#headings)  
[Emphasis](#emphasis)  
[Block Quote](#block-quote)  
[Horizontal Rule](#horizontal-rule)  
[Comments](#comments)  
[Lists](#lists)  
[Code](#code)  
[Links & Images](#links--images)  
[Table](#table)  
[Task List](#task-list)
```

> Rendered:

[Headings](#headings)  
[Emphasis](#emphasis)  
[Block Quote](#block-quote)  
[Horizontal Rule](#horizontal-rule)  
[Comments](#comments)  
[Lists](#lists)  
[Code](#code)  
[Links & Images](#links--images)  
[Table](#table)  
[Task List](#task-list)
