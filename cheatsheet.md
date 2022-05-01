# *Headings*
<!-- Headings -->

>Raw:
```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

>Rendered:  

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
---
# *Emphasis*
<!-- Text Emphasis -->

>Raw:
```markdown
This is **bold** text 

This is *Itallic* text 

This is ***Itallic & Bold*** text 

This is ~~Striked Text~~ text

This is **bold** text
```

>Rendered:  

<!-- Bold text -->
This is **bold** text 
<!-- Italic text -->
This is *Itallic* text 
<!-- Italic & Bold text -->
This is ***Itallic & Bold*** text 
<!-- Striked text -->
This is ~~Striked Text~~ text
<!-- Bold text -->
This is **bold** text

---
# *Block Quote*
<!-- Block quote -->

>Raw:  
```markdown
> This is a quote.
>> This is a nested quote.

> This is the second line of the quote.
```

>Rendered: 

> This is a quote.
>> This is a nested quote.  

> This is the second line of the quote.
---
# *Horizontal Rule*
<!-- Horizontal rule -->

>Raw:  
```markdown
---
___
```

>Rendered:

---
___
# *Comments*
<!-- Comments -->

>Raw:  
```markdown
<!-- This is a comment -->
```

>Rendered:  

*Comments are not visisble when rendered.*
<!-- This is a comment -->

---
# *Lists*
<!-- Lists -->

### *Unordered list*
<!-- Unordered list -->

>Raw:  
```markdown
* Item 1  
* Item 2  
    * This item is nested
* Item 3
```

>Rendered:  

* Item 1  
* Item 2  
    * This item is nested
* Item 3

### *Ordered list*  
<!-- Ordered list -->

>Raw:  
```markdown
1. Item 1  
2. Item 2  
    1. This item is nested.
3. Item 3
```

>Rendered:  

1. Item 1  
2. Item 2  
    1. This item is nested.
3. Item 3

---
# *Code*
<!-- Code -->

### *Python*
<!-- Python Code -->

>Raw:  
```markdown
    ```python
        def sum(a,b):
            return a+b
    ```
```

>Rendered:  

```python
    def sum(a,b):
        return a+b
```
### *Bash*
<!-- Bash Script -->

>Raw:  
```markdown
    ```bash
    git commit -am "Initial commit."
    ```
```

>Rendered:  

```bash
    git commit -am "Initial commit."
```

---
# *Links & Images*
### *Link*
<!-- Link -->

>Raw:  
```markdown
[This is a link](https://twitter.com/Durgesh_B_G)  
```

>Rendered:  

[This is a link](https://twitter.com/Durgesh_B_G)  

### *Image*
<!-- Image -->

>Raw:  
```markdown
![Alternate Text](./sample.png)
```

>Rendered:  

![Alternate Text](./sample.png)

---
# *Table*
<!-- Table -->

>Raw:  
```markdown
| Header 1 | Header 2 | Header 3 |  
| --- | --- | --- |  
| Item 1 | Item 2 | Item 3 |  
| Item 4 | Item 5 | Item 6 |  
| Item 7 | Item 8 | Item 9 |  
```

>Rendered:  

| Header 1 | Header 2 | Header 3 |  
| --- | --- | --- |  
| Item 1 | Item 2 | Item 3 |  
| Item 4 | Item 5 | Item 6 |  
| Item 7 | Item 8 | Item 9 |  

---
# *Task List*
<!-- Task List -->

>Raw:
```markdown
- [x] Task 1
- [x] Task 2
- [ ] Task 3
- [x] Task 4
- [ ] Task 5
- [ ] Task 6
```

>Rendered:  

- [x] Task 1
- [x] Task 2
- [ ] Task 3
- [x] Task 4
- [ ] Task 5
- [ ] Task 6

---
# *Heading IDs*
<!-- Linking headers in a same page -->

>Raw:
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

>Rendered:  

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

