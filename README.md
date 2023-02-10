# markdown
Markdown guide and practice

The heading with asterisk(`*`) is extended Markdown feature.
Note that not all Markdown processors support those features.

## Heading

To create a heading, add number signs (#) in front of a word or phrase.
The number of number signs corresponds to the heading level.
The heading of this section is level-2 heading
and is create by

```
## Heading
```

Put a blank line before and after heading for compatibility.

## Paragraph

Use a blank line before a new paragraph.

## Line Break

Two or more spaces at the end of the line makes a line break.

## Emphasis

You can emphasize a text
by embracing it with asterisks (`*`) or underscores (`_`).
For compatibility, use asterisks.

The rendered output varies according to the number of asterisks.
- Italic : with an asterisk
    - Markdown : `Try to use *Markdown*.`
    - Output : Try to use *Markdown*.
- Bold : with two asterisks
    - Markdown : `Try to use **Markdown**.`
    - Output : Try to use **Markdown**.
- Bold Italic : with three asterisks
    - Markdown : `Try to use ***Markdown***.`
    - Output : Try to use ***Markdown***.

## Strikethrough*

To strike through a word or a pharase,
enclose it in 2 tilde symbols(`~~`).

`~~strikethrough~~` yields ~~strikethrough~~

## Ordered List

Start a line with a number followed by a period (`.`).

```
1. First item
2. Second item
3. Third item
4. Fourth item
```

The rendered output is:

1. First item
2. Second item
3. Third item
4. Fourth item

## Unordered List

Start a line with a number
followed by a dash (`-`), asterisk(`*`) or plus sign (`+`).

```
- First item
- Second item
- Third item
- Fourth item
```

The rendered output is:

- First item
- Second item
- Third item
- Fourth item

## Nesting in List

You can nest list, paragraph, blockquote
by indenting them with 4 spaces or a tab.

```
- First item
- Second item
    - Nested first item
    - Nested second item
```

The rendered output is:

- First item
- Second item
    - Nested first item
    - Nested second item

## Task List*

Task list is a list of items with checkboxes.
To create a task list,
add a pair of square bracket with space in them after dashes.
To check the items,
replace the space in the brackets with `X`.

```
- [ ] First item
- [ ] Second item
- [X] Third item
```

The rendered output is:

- [ ] First item
- [ ] Second item
- [X] Third item

## Definition List*

To create a definition list,
write a term on the first line,
and provide a definition preceded by a colon and a space on the next line.

```
Term1
: This is the definition of Term1.

Term2
: This is the first definition of Term2.
: This is the second definition of Term2.
```

The rendered output is:

Term1
: This is the definition of Term1.

Term2
: This is the first definition of Term2.
: This is the second definition of Term2.

## Blockquote

Adding `>` at the beginning of the line creates a blockquote.
Use a blank line before and after a blockquote for compatibility.

```
> This is a blockquote.
```

The rendered output is:

> This is a blockquote.

You can nest a blockquote using `>>`.

```
> This is a blockquote.
>> This is a nested blockquote.
```

The rendered output is:

> This is a blockquote.
>> This is a nested blockquote.

## Code

To denote a word or phrase as code, enclose it in backticks (`).

```
For formatted printing in C language, use `printf()` function.
```

The rendered output is:

For formatted printing in C language, use `printf()` function.

## Code Block

To denote a block as code,
indent every line in the block by 4 spaces or a tab.

```
    int main()
    {
        printf("Hello.\n");
        
        return(1);
    }
```

The rendered output is:

    int main()
    {
        printf("Hello.\n");
        
        return(1);
    }

## Link

To create a link,
enclose the link text in square brackets(`[]`)
and provide the URL in parenthesis immediately after it.
You can also specify the alternate text for the link in the parenthesis.

```
- [Google](https://www.google.com)
- [Naver](https://www.naver.com "Korean Search Engine")
```

The rendered output is:

- [Google](https://www.google.com)
- [Naver](https://www.naver.com "Korean Search Engine")

*There are some other ways to create link.*

## Image

To insert an image,
use the same method of creating the link
and add an exclamation mark(`!`) in front of the link.

## Horizontal Rule

3 or more dashes(`---`), asterisks(`***`) or underscores(`___`)
creates a horizontal rule.

`---`

The rendered output is:

---

## Table*

To create a table, use the following format.
The number of dashed(`-`) should be 3 or more.

```
| City  | Nation |
| ---   | ---    |
| Seoul | Korea  |
| Tokyo | Japan  |
```

The rendered output is:

| City  | Nation |
| ---   | ---    |
| Seoul | Korea  |
| Tokyo | Japan  |

To align the table contents,
use colon(`:`) in the following manner.

```
| City  | Nation | Continent |
| :---  | :---:  | ---:      |
| Seoul | Korea  | Asia      |
| Tokyo | Japan  | Asia      |
```

The rendered output is:

| City  | Nation | Continent |
| :---  | :---:  | ---:      |
| Seoul | Korea  | Asia      |
| Tokyo | Japan  | Asia      |

## Fenced Code Block

## Heading ID

[Emoji](#emoji)

[Emphasis](#emphasis)

## Emoji* {#emoji}

You can use emoji by providing emoji name in colons.

`:smile: :rage: :cry:` yields :smile: :rage: :cry:.

Emoji names vary from application to application.
[Here](https://gist.github.com/rxaviers/7360908) is an example list of emoji names.
