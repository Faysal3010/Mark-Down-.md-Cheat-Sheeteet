# Mark-Down-Cheat-Sheeteet

A single place for all the Markdown syntaxes I have learned so far. Sharing publicly so that you can learn and use them too.

---

## Table of Contents

1. [Headings](#headings)
2. [Code](#code)
3. [Unordered List of Items](#unordered-list)
4. [Ordered List of Items](#ordered-list)
5. [CheckBox Task List](#checkbox-task-list)
6. [Code Block](#code-block)
7. [Strikethrough Text](#strikethrough)
8. [Blockquote Text](#blockquote)
9. [Bold](#bold)
10. [Italic](#italic)
11. [Bold and Italic](#bold-and-italic)
12. [Link](#link)
13. [Image](#image)
14. [Linking an Image](#linking-an-image)
15. [Emojis](#emojis)
16. [Alerts](#alerts-github-flavored)
17. [Table](#table)
18. [Table With Alignments](#table-with-alignments)
19. [Horizontal Line](#horizontal-line)
20. [HTML](#html-inside-markdown)
21. [Embed YouTube Video](#embed-youtube-video)
22. [Mathematical Expressions](#mathematical-expressions-katexlatex)
23. [DropDown](#dropdown)
24. [Diagrams](#diagrams-mermaid)
25. [FootNote](#footnote)
26. [Comments](#comments)

---

### Headings

```markdown
# H1 - Heading 1

## H2 - Heading 2

### H3 - Heading 3

#### H4 - Heading 4

##### H5 - Heading 5

###### H6 - Heading 6
```
output:
# H1 - Heading 1

## H2 - Heading 2

### H3 - Heading 3

#### H4 - Heading 4

##### H5 - Heading 5

###### H6 - Heading 6

### Code

```markdown
`This is Code`
```
Output: `This is Code`

### Unordered List

```markdown
- Milk
- Tea
- Beer

* JavaScript
* TypeScript
* ReactJs
```

- Milk
- Tea
- Beer 

* JavaScript
* TypeScript
* ReactJs


### Ordered List

```markdown
1. Eat
2. Walk
3. Sleep
```
1. Eat
2. Walk
3. Sleep


### CheckBox Task List

```markdown
- [x] Code
- [ ] Review
- [ ] Commit
```

- [x] Code
- [ ] Review
- [ ] Commit

### Code Block

<pre>
```
This is a code block.
```
</pre>

With Language:

### JS
```js
function print() {
  console.log("JavaScript Code Block");
}
```
### Python
```py
print("Hello, Janina")
```

### bash
```bash
# This is bash
echo Hello
```
### CPP
```bash
using namespace std;
int main(void){
cout<<"Faysal";
}
```

### Strikethrough

```markdown
~~This is wrong.~~
```

output:
markdown

~~This is wrong.~~


### Blockquote

```markdown
> Life is what happens when you're busy coding.
```

### Bold

```markdown
**Bold Text**
```
### output:
**Bold Text**

### Italic

```markdown
_Italic Text_
```
### output:
_Italic Text_
### Bold and Italic

```markdown
**_Bold and Italic Text_**
```
### output:
**_Bold and Italic Text_**

### Link

```markdown
<!-- [alt](link) -->
[Visit My Site](https://https://github.com/Faysal3010)
```
### output:
[Visit My Site](https://github.com/Faysal3010)

### Image

```markdown
![Alt text](faysal.png)
```
### output:
![Alt text](faysal.png)
### Linking an Image

```markdown
[![Alt text](image.png)](https://github.com/Faysal3010/Faysal3010/raw/main/faysal.jpg)
```
### output:
[![Alt text](image.jpg)](https://github.com/Faysal3010/Faysal3010/raw/main/faysal.jpg)

### Emojis

```markdown
:mango: :rocket: :fire:
```

### Alerts (GitHub flavored)

```markdown
> [!NOTE]
> Note text.

> [!TIP]
> Tip text.

> [!IMPORTANT]
> Important text.

> [!WARNING]
> Warning text.

> [!CAUTION]
> Caution text.
```
### output:
> [!NOTE]
> Note text.

> [!TIP]
> Tip text.

> [!IMPORTANT]
> Important text.

> [!WARNING]
> Warning text.

> [!CAUTION]
> Caution text.



### Table

```markdown
| Fruit | Emoji   |
| ----- | ------- |
| Mango | :mango: |
| Lemon | :lemon: |
```
### output:
| Fruit | Emoji   |
| ----- | ------- |
| Mango | :mango: |
| Lemon | :lemon: |

### Table With Alignments

```markdown
| Fruit (left) | Emoji (center) |       Taste (right) |
| :----------- | :------------: | ------------------: |
| Mango        |    :mango:     | Sweet and delicious |
| Lemon        |    :lemon:     |    Sour and healthy |
```
### output:
| Fruit (left) | Emoji (center) |       Taste (right) |
| :----------- | :------------: | ------------------: |
| Mango        |    :mango:     | Sweet and delicious |
| Lemon        |    :lemon:     |    Sour and healthy |


### Horizontal Line

```markdown
---
```
### output:
---
### HTML inside Markdown

```html
<p align="center">This is centered paragraph using HTML.</p>
```
### output:
<p align="center">This is centered paragraph using HTML.</p>

### Embed YouTube Video

```markdown
[![Video Title](thumbnail.png)](https://youtube.com/@faysalmahmud7248)
```
### output:
[![Video Title](faysal.png)](https://youtube.com/@faysalmahmud7248)

### Mathematical Expressions (KaTeX/LaTeX)

Inline:

```markdown
$√{3} + 1$
```
### output: 
$√{3} + 1$

Block:

```markdown
$$
\sqrt{3} + 1
$$
```
### output:
$$
\sqrt{3} + 1
$$

Full:

```markdown
When $a \ne 0$, two solutions to $(ax^2 + bx + c = 0)$ are:

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$
```

### output:
When $a \ne 0$, two solutions to $(ax^2 + bx + c = 0)$ are:

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

### DropDown

#### Open by Default

```html
<details open>
  <summary>Click to Expand</summary>
  <br />
  This content is always visible on page load.
</details>
```

### output:
<details open>
  <summary>Click to Expand</summary>
  <br />
  This content is always visible on page load.
</details>

#### Hidden by Default

```html
<details>
  <summary>Click to Expand</summary>
  <br />
  This content appears only when clicked.
</details>
```

### output:
<details>
  <summary>Click to Expand</summary>
  <br />
  This content appears only when clicked.
</details>


## Diagrams

**Syntax:**
- Use the *mermaid* syntax
- Additional syntax: TD means Top Down, LR means Left Right, BT means Bottom Top, RL means Right Left 

TD variant
```
    ```mermaid
        graph TD;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
    ```
```

**Output:**

 ```mermaid
        graph TD;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
```

LR variant
```
    ```mermaid
        graph LR;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
    ```
```

**Output:**

 ```mermaid
        graph LR;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
```

BT variant
```
    ```mermaid
        graph BT;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
    ```
```

**Output:**

 ```mermaid
        graph BT;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
```

RL variant
```
    ```mermaid
        graph RL;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
    ```
```

**Output:**

 ```mermaid
        graph RL;
            A-->B;
            B-->C;
            C-->D;
            D-->E;
```

## FootNote

**Explanation:**
<br>Footnotes allow you to add notes and references without cluttering the body of the document. 
<br>When you create a footnote, a superscript number with a link appears where you added the footnote reference. 
<br>Readers can click the link to jump to the content of the footnote at the bottom of the page.

**Syntax:**

```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

```
**Output:**

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.


## Comments

**Explanation:**
<br>Comments are text notes added to a program or a document to provide explanatory information.
<br>You can hide content from the rendered Markdown by placing the content in a comment.


**Syntax**

```
This is Line Number 1. 
<!---This is Line Number 2 and would not be rendered as this is a comment. --->
This is Line Number 3.
```

**Output**

This is Line Number 1. 
<!---This is Line Number 2 and would not be rendered as this is a comment. --->
This is Line Number 3.


Thanks to all the ⭐ stargazers! Let's keep learning Markdown together!
