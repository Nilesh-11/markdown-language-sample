<!-- Header -->

# hello

## hello world

### h3

#### h4

##### h5

###### h6

<!-- Italic -->
<!-- we can also use * for italic

for example :

*hello*

will return "hello" in italic but when we save it vscode automatically converts it into the second style which uses underscore

-->

_hello world_ is italic
_This text_ is italic

<!-- Strong text -->
<!--
We can also use double underscore for strong text
like


__hello__


will display "hello" as a strong text
but when we save it vs code converts it into first style which uses double asterisk **

-->

**hello world** is italic
**This text** is italic

<!-- Strikethrough -->
<!-- we use double tilda for strikethrough -->

~~This text~~ is strikethrough

<!-- Horizontal Rule -->
<!-- we can use

triple hyphen ---

or


triple underscore

but when saved vsCode converts triple underscore to triple hyphen


-->

---

---

<!-- We can escape the characters using backslash -->

_hello_ is italic
but

\*hello\* is not italic

<!-- Blockquotes -->

> this is a blockquote

<!-- Links

text for link goes inside []

and the link goes inside () adjacent to []

and the title should be next to the link in double quotes (or single quotes)

title will be shown when the mouse hovers over the link


-->

[Text for link](https://www.google.com)

[Text for link](https://www.google.com "Google")

<!-- Unordered list

We can use asterisk or hyphen

* thing 1
* thing 2
* thing 3

or

- thing 1
- thing 2
- thing 3

but when saved vscode converts it into hyphen

-->

- thing 1
- thing 2
- thing 3
  - nested thing 1
    - nested nested thing 1
      - nested nested nested thing 1

<!-- Ordered list

Nested list "Don't know"


-->

1. Thing 1
1. Thing 2

<!-- Inline Code Block -->

`<p>This is a paragraph</p>`

<!-- Images -->
<!-- similar to links but we have to put an exclamation mark before square brackets -->

<!-- ![Markdown Logo](https://markdown-here.com/img/icon256.png) -->

<!-- Github Markdown -->

<!-- Code Blocks -->

```
  npm install

  npm run dev
```

<!-- For Code blocks of bash language -->

```bash
  ./hello.sh
```

or

```BASH
  ./hello.sh
```

<!-- For Code blocks of javascript language -->

```javascript
function add(num1, num2) {
  return num1 + num2;
}
```

<!-- For Code blocks of python language -->

```python
def add(num1,num2):
  return num1+num2
```

<!-- Tables -->

| Name  | Email  |
| ----- | ------ |
| Name1 | email1 |
| Name2 | email2 |

<!-- Task Lists -->

- [x] Task 1
- [x] Task 2
- [ ] Task 3
