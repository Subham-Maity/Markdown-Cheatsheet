# Chapters 
* [Headings](#headings)
* [Text styles](#text-styles)
* [Syntax Highlighting](#syntax-highlighting)
* Alignments
* Tables
* Links
* Images
* Lists
* Horizontal Rule
* Miscellaneous
* Bitbucket
* Tools





## **Headings**

There are few options to create headings. We can use Markdown or HTML or an alternative syntax to create our desired headings.

First, let’s talk about the markdown syntax.


```md
        # Heading 1
        ## Heading 2
        ### Heading 3
        #### Heading 4
        ##### Heading 5
```


The second option, using the HTML syntax.


```md
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
```


Finally, we can use an alternate syntax. This method only works for heading 1 and heading 2. Add any number of `=` or `-` below the text for heading 1 or heading 2.


```md
        Heading 1
        =
        Heading 2
        - 
```


Now, let’s see how it looks on GitHub.





        Headings

**Text styles**

Using markdown syntax, we can change texts’ styles, including bold, italic, blockquotes, monospaced, underlined, strike-through, boxed, subscript, and superscript.

We can use two asterisks (`**`), underscores (`__`), or an HTML tag `&lt;strong>` to make a text bold. To make text italic, we can use one asterisk (`*`), underscore (`_`), or an HTML tag `&lt;em>`. Also, we can make the text bold and italic at the same time.


```md
        Bold
        **The quick brown fox jumps over the lazy dog.**
        __The quick brown fox jumps over the lazy dog.__
        <strong>The quick brown fox jumps over the lazy dog.</strong>
        Italic
        *The quick brown fox jumps over the lazy dog.*
        _The quick brown fox jumps over the lazy dog._
        <em>The quick brown fox jumps over the lazy dog.</em>
        Bold and Italic
        **_The quick brown fox jumps over the lazy dog._**
        <strong><em>The quick brown fox jumps over the lazy dog.</em></strong>
```


Now, let’s see how it looks on GitHub.








        Bold and Italic text styles

To create blockquote, we can use the greater than sign `>`. We can create a single-line or multi-line blockquote. Also, blockquote inside a blockquote. We can add other text styles inside a blockquote, such as bold or italic text styles.


```md
        Blockquotes
        > The quick brown fox jumps over the lazy dog.
        > The quick brown fox jumps over the lazy dog.
```



        `>` 


```md
        > The quick brown fox jumps over the lazy dog.
```



        `>` 


```md
        > The quick brown fox jumps over the lazy dog.
        > The quick brown fox jumps over the lazy dog.
        >> The quick brown fox jumps over the lazy dog.
        >>> The quick brown fox jumps over the lazy dog.
        > **The quick brown fox** *jumps over the lazy dog.*
```


Now, let’s see how it looks on GitHub.





        Blockquotes text styles

We can achieve monospaced, and underlined styles using HTML tags `&lt;samp>` and `&lt;ins>`. For a strike-through style, we can use two tilda sign `~~`.


```md
        Monospaced
        <samp>The quick brown fox jumps over the lazy dog.</samp>
```





```md
        Underlined
        <ins>The quick brown fox jumps over the lazy dog.</ins>
```





```md
        Strike-through
        ~~The quick brown fox jumps over the lazy dog.~~
```


Now, let’s see how it looks on GitHub.








        Monospaced, Underlined, and Strike-through text styles

We can use an HTML `&lt;table>` tag to create a box.


```md
        Boxed
        <table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
```


Now, let’s see how it looks on GitHub.





        Boxed text style

We can achieve subscript and superscript styles using HTML tag `&lt;sub>` and `&lt;sup>`. It is useful when you’re writing a mathematical formula.


```md
        Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
        Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
```


Now, let’s see how it looks on GitHub.





        Subscript and Superscript text styles

**Syntax Highlighting**

We can use a single backtick ``` before and after the code block to create the following view.


```md
        A class method is an instance method of the class object. When a new class is created, an object of type `Class` is initialized and assigned to a global constant (Mobile in this case).
```


As you can see the word **Class** is highlighted.





        Code Highlighting

We can also use triple backticks ````` before and after the code block to create the following view.


```md
        ```
        public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
        ```
```



```
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```


Code Highlighting

We can add an optional language identifier to enable syntax highlighting. Refer to[ this](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml) and[ this](https://github.com/github/linguist/tree/master/vendor) GitHub documents to find all the valid keywords.


```md
        ```java
        public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
        ```
```


Now, let’s see how it looks on GitHub.



```java
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```

Syntax Highlighting

**Alignments**

By using HTML tags, we can align README contents.


```md
        <p align="left">
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
        </p>
```




<p align="left">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>

Left align


```md
        <p align="center">
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
        </p>
```




<p align="center">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>

Center align


```md
        <p align="right">
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
        </p>
```



<p align="right">
<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
</p>


Right align

Now, let’s align a text.


```md
        <h3 align="center"> My latest Medium posts </h3>
```





<h3 align="center"> My latest Medium posts </h3>

Center align

**Tables**

Let’s create a table without headers.


```md
        <table>
        <tr>
        <td width="33%">
        The quick brown fox jumps over the lazy dog.
        </td>
        <td width="33%">
        The quick brown fox jumps over the lazy dog.
        </td>
        <td width="33%">
        The quick brown fox jumps over the lazy dog.
        </td>
        </tr>
        </table>
```





<table>
<tr>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
<td width="33%">
The quick brown fox jumps over the lazy dog.
</td>
</tr>
</table>

Table without header

To create a table with headers we need to use dashes to separate each header cell and use pipes to separate columns. The outer pipes are optional. We can use any number of dashes and spaces to increase readability. We can use colons to align columns. For left-align text, use a colon to the left of dashes. For center-align text, use a colon on both sides of dashes. For right-align text, use a colon to the right of dashes. By default Left align is used.


```md
        | Default | Left align | Center align | Right align |
        | - | :- | :-: | -: |
        | 9999999999 | 9999999999 | 9999999999 | 9999999999 |
        | 999999999 | 999999999 | 999999999 | 999999999 |
        | 99999999 | 99999999 | 99999999 | 99999999 |
        | 9999999 | 9999999 | 9999999 | 9999999 |
        | Default    | Left align | Center align | Right align |
        | ---------- | :--------- | :----------: | ----------: |
        | 9999999999 | 9999999999 | 9999999999   | 9999999999  |
        | 999999999  | 999999999  | 999999999    | 999999999   |
        | 99999999   | 99999999   | 99999999     | 99999999    |
        | 9999999    | 9999999    | 9999999      | 9999999     |
        Default    | Left align | Center align | Right align
        ---------- | :--------- | :----------: | ----------:
        9999999999 | 9999999999 | 9999999999   | 9999999999
        999999999  | 999999999  | 999999999    | 999999999 
        99999999   | 99999999   | 99999999     | 99999999  
        9999999    | 9999999    | 9999999      | 9999999
```


| Default | Left align | Center align | Right align |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |
| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |
Default    | Left align | Center align | Right align
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999
999999999  | 999999999  | 999999999    | 999999999  
99999999   | 99999999   | 99999999     | 99999999   
9999999    | 9999999    | 9999999      | 9999999



Table with different alignments

Now display two tables side by side.


```md
<table>
<tr>
<th>Heading 1</th>
<th>Heading 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>

```





<table>
<tr>
<th>Heading 1</th>
<th>Heading 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>
Display two tables side by side

Let’s create a table with multiple lines using the HTML `&lt;br/>` tag.


```md
        | A | B | C |
        |---|---|---|
        | 1 | 2 | 3 <br/> 4 <br/> 5 |
```




| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |

A table with multiple lines

**Links**

We can create a link in four ways. The first one is by using an inline style. The second one uses reference style, the third one using relative links, and finally auto links.


```md
        [The-Ultimate-Markdown-Cheat-Sheet (https://github.com/lifeparticle/Markdown-Cheatsheet)
```




![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/67.png)

Inline-style

If you’re using the same link more the once, then using the reference style would be beneficial since you don’t have to write the link every time, and also, it’s easy to update the link. Moreover, you can use numbers for the reference text. Also, you can use the reference text as the link text.


```md
        [The-Ultimate-Markdown-Cheat-Sheet][reference text]
        [The-Ultimate-Markdown-Cheat-Sheet][1]
        [Markdown-Cheat-Sheet]
        [reference text]: https://github.com/lifeparticle/Markdown-Cheatsheet
        [1]: https://github.com/lifeparticle/Markdown-Cheatsheet
        [Markdown-Cheat-Sheet]: https://github.com/lifeparticle/Markdown-Cheatsheet
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/68.png)

Three variations of reference-style

We can also create relative links with all relative link operands, such as `./` and `../`.


```md
        [Example of a relative link](rl.md)
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/70.png)

Example of a relative link

GitHub can automatically create links from standard URLs.


```md
        Visit https://github.com/
```





Visit https://github.com/

Auto link

**Images**

We can add images using the similar techniques we used for links.


```md
        ![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80)
```





![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80)

Inline-style


```md
        ![alt text][image]
        [image]: https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80
```





<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>

Reference-style

Also, we can use the HTML `img` tag to add an image.


```md
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
```





<img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>

img tag

We can also embed GIF and SVG.


```md
        <img src="https://media.giphy.com/media/qLHzYjlA2FW8g/giphy.gif" />
```





<img src="https://media.giphy.com/media/qLHzYjlA2FW8g/giphy.gif" />


GIF


```md
        <img src="https://img.shields.io/badge/theultimatemarkdowncheatsheet-brightgreen.svg" />
```





<img src="https://img.shields.io/badge/theultimatemarkdowncheatsheet-brightgreen.svg" />

SVG

**Lists**

For lists, we can have ordered and unordered lists.


```md
        1. One
        2. Two
        3. Three
```




![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/89.png)

An ordered list

Now let’s create an ordered list with sub-items.


```md
        1. First level
           1. Second level
               - Third level
                   - Fourth level
        2. First level
           1. Second level
        3. First level
           1. Second level
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/90.png)

An ordered list with sub-items

To create an unordered list, we can asterisk, plus, or minus sign.


```md
        * 1
        * 2
        * 3
        + 1
        + 2
        + 3
        - 1
        - 2
        - 3
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/91.png)

Unordered lists

Now let’s create an unordered list with sub-items.


```md
        - First level
           - Second level
               - Third level
                   - Fourth level
        - First level
           - Second level
        - First level
           - Second level
```




![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/92.png)

An unordered list with sub-items

We can also use HTML to create a list.


```md
        <ul>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
        <li>Fourth item</li>
        </ul>
```






![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/93.png)

A list using HTML

Now let’s create a task list. We can create a task list using a hyphen followed by `[ ]`, and to mark a task complete, put an `x` inside the brackets.


```md
        - [x] Fix Bug 223
        - [ ] Add Feature 33
        - [ ] Add unit tests
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/94.png)

Tasklist

**Horizontal Rule**

We can use three hyphens, asterisks, or underscores to create a horizontal line.


```md
        ---
        ***
        ___
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/95.png)
Horizontal Rule

**Miscellaneous**

We can include comments inside a `.md` file.


```md
        <!--
        Lorem ipsum dolor sit amet
        -->
```


We can use a backslash to escape literal characters. Before escaping.


```md
        *   Asterisk
        \   Backslash
        `   Backtick
        {}  Curly braces
        .   Dot
        !   Exclamation mark
        #   Hash symbol
        -   Hyphen symbol
        ()  Parentheses
        +   Plus symbol
        []  Square brackets
        _   Underscore
```




![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/96.png)

Before escaping

After escaping.


```md
        \*   Asterisk
        \\   Backslash
        \`   Backtick
        \{}  Curly braces
        \.   Dot
        \!   Exclamation mark
        \#   Hash symbol
        \-   Hyphen symbol
        \()  Parentheses
        \+   Plus symbol
        \[]  Square brackets
        \_   Underscore
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/97.png)

After escaping

We can also include[ emojis](https://gist.github.com/rxaviers/7360908) in our `.md` file.


```md
        :octocat:
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/98.png)
An octocat emoji

We can mention a person or team by typing `@` with their username or team name.


```md
        @lifeparticle
```





![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/99.png)
Mention a person

We can also bring up a list of suggested issues and pull requests within the repository by typing `#`.


```md
        #
```




![](https://github.com/Subham-Maity/Markdown-Cheatsheet/blob/main/Images/100.png)

Referencing issues and pull requests

**Bitbucket**

Bitbucket Supported Markdown for[ READMEs](https://bitbucket.org/tutorials/markdowndemo/src/master/). Also,[ create a table of contents](https://support.atlassian.com/bitbucket-cloud/docs/add-a-table-of-contents-to-a-wiki/).

**Tools**

There are various tools for Markdown, which will help you to build a beautiful GitHub README faster.


1. 	Create a Markdown table of content —[ GitHub](https://github.com/ekalinin/github-markdown-toc)


2.	Create an empty Markdown table —[ Tablesgenerator](https://www.tablesgenerator.com/markdown_tables)


3.	Convert Excel to Markdown table —[ Tableconvert](https://tableconvert.com/)


4.	Markdown preview for Sublime Text 3 —[ Packagecontrol](https://packagecontrol.io/packages/MarkdownPreview)


5.	Markdown preview Visual Studio Code —[ Marketplace](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

 
