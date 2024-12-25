---
title: Your Post Title
description: A brief description of your post
date: 2024-12-25 14:30:00+0800
image: cover.jpg
math: true
---

# Your Post Title

Welcome to your post! This template includes various Markdown features supported by Hugo Theme Stack.

## Math Typesetting

### Inline Math

This is an inline mathematical expression: $\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…$

```markdown
$\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…$
```

### Block Math

$$    \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } $$

```markdown
$$    
\varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } 
$$
```

## Markdown Syntax

### Headings

# H1
## H2
### H3
#### H4
##### H5
###### H6

### Paragraph

This is a sample paragraph. You can write your content here.

### Blockquotes

> This is a blockquote. You can use *Markdown syntax* within a blockquote.

### Lists

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

- List item
- Another item
- And another item

#### Nested List

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

### Tables

| Name  | Age |
|-------|-----|
| Bob   | 27  |
| Alice | 23  |

### Code Blocks

#### Inline Code

This is an inline code block: `print("Hello, World!")`.

#### Code Block with Backticks

```python
def hello_world():
    print("Hello, World!")
```

#### Diff Code Block

```diff
[dependencies.bevy]
git = "https://github.com/bevyengine/bevy"
rev = "11f52b8c72fc3a568e8bb4a4cd1f3eb025ac2e13"
- features = ["dynamic"]
+ features = ["jpeg", "dynamic"]
```

### Other Elements

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.

## Shortcodes

### Bilibili Video

{{< bilibili "BV1d4411N7zD" >}}

### Tencent Video

{{< tencent "g0014r3khdw" >}}

### YouTube Video

{{< youtube "0qwALOOvUik" >}}

### Generic Video File

{{< video "https://www.w3schools.com/tags/movie.mp4" >}}

### Gist

{{< gist CaiJimmy e2751a943de10b2a5b3a8a6c2120cb86 >}}

### GitLab

{{< gitlab 2589724 >}}

### Quote

{{< quote author="A famous person" source="The book they wrote" url="https://en.wikipedia.org/wiki/Book">}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
{{< /quote >}}

---