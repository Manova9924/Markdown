# All the syntax in Markdown
# GitHub-Flavored Markdown (GFM) Complete Example
***What is GitHub Flavored Markdown (GFM)?***
 is GitHub's extended version of standard Markdown. It adds extra features that make writing documentation, README files, issues, pull requests, and discussions easier on GitHub.
 `a + b = c`

Markdown itself is a lightweight markup language for formatting text. GFM keeps all standard Markdown features and adds GitHub-specific enhancements.

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

## Text Formatting

Plain text

**Bold**

__Bold__

*Italic*

_Italic_

***Bold + Italic***

___Bold + Italic___

~~Strikethrough~~

`Inline code`

---

## Blockquotes

> Single level quote

> Multi-line quote
> continues here

> Nested quote
>> Level 2
>>> Level 3

---

## Horizontal Rules

---

***

___

---

## Lists

### Unordered

- Item A
- Item B
  - Nested Item
    - Deep Nested Item
      - Very Deep Nested Item

* Item C
* Item D

+ Item E
+ Item F

### Ordered

1. First
2. Second
3. Third

1. Item
   1. Nested Item
   2. Nested Item
2. Item

### Mixed

1. Fruits
   - Apple
   - Banana
2. Vegetables
   - Carrot
   - Potato

---

## Task Lists

- [x] Completed
- [x] Another completed item
- [ ] Pending item
- [ ] Future item

---

## Links

### Inline Link

[OpenAI](https://openai.com)

### Link With Title

[OpenAI](https://openai.com "OpenAI Homepage")

### Reference Links

[Google][google]

[google]: https://google.com

### Automatic Links

<https://github.com>

<test@example.com>

---

## Images

![Alt Text](https://example.com/image.png)

### Clickable Image

[![Image](https://example.com/image.png)](https://example.com)

---

## Code

### Inline

Use `npm install` to install packages.

### Fenced Code Block

```python
def hello():
    print("Hello World")
```

```javascript
function hello() {
  console.log("Hello World");
}
```

```html
<h1>Hello World</h1>
```

### Plain Code Block

```
No syntax highlighting
```

---

## Tables

| Name | Age | Country |
|------|-----|----------|
| John | 25  | USA      |
| Sara | 30  | India    |
| Alex | 28  | Canada   |

### Alignment

| Left | Center | Right |
| :--- | :----: | ----: |
| A    | B      | C     |
| D    | E      | F     |

---

## Escaping Characters

\*Not italic\*

\# Not a heading

\`Not code\`

---

## Footnotes

Markdown supports footnotes.[^1]

Another footnote.[^note]

[^1]: First footnote.

[^note]: Named footnote.

---

## Definition Lists
*(Supported in some Markdown processors)*

Term 1
: Definition 1

Term 2
: Definition 2

---

## Emoji

:smile:

:rocket:

:heart:

👍

🚀

🔥

---

## HTML Support

<div style="color:red;">
HTML inside Markdown
</div>

<details>
<summary>Click to Expand</summary>

Hidden content goes here.

- Item 1
- Item 2

</details>

---

## Keyboard Keys

<kbd>Ctrl</kbd> + <kbd>C</kbd>

<kbd>Ctrl</kbd> + <kbd>V</kbd>

---

## Superscript/Subscript
*(Supported in some flavors)*

X^2^

H~2~O

---

## Highlight
*(Supported in some flavors)*

==Highlighted Text==

---

## Line Breaks

First line.

Second paragraph.

First line with two trailing spaces.  
Second line.

---

## Checkboxes Inside Lists

1. Setup
   - [x] Install
   - [x] Configure
   - [ ] Deploy

---

## Nested Formatting

**Bold and _italic inside bold_ text**

~~Strikethrough with `inline code`~~

> Quote with **bold text** and a [link](https://example.com)

---

## GitHub Mentions

@username

#123

owner/repository

---

## GitHub Alerts
*(Supported in GitHub Markdown)*

> [!NOTE]
> Useful information.

> [!TIP]
> Helpful advice.

> [!IMPORTANT]
> Important information.

> [!WARNING]
> Warning message.

> [!CAUTION]
> Be careful.

---

## Collapsible Section

<details>
<summary>Show Content</summary>

### Hidden Heading

Lorem ipsum dolor sit amet.

```bash
echo "Hidden code block"
```

</details>

---

## Mathematical Expressions
*(GitHub supports this in some contexts)*

Inline: $E = mc^2$

Block:

$$
a^2 + b^2 = c^2
$$

---

## Sample Document Structure

# Project Name

## Description

Project description here.

## Installation

```bash
git clone https://github.com/example/repo.git
cd repo
npm install
```

## Usage

```bash
npm start
```

## Features

- Fast
- Simple
- Open Source

## License

MIT

---

End of Markdown Showcase 🚀