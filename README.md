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


```
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
```


Finally, we can use an alternate syntax. This method only works for heading 1 and heading 2. Add any number of `=` or `-` below the text for heading 1 or heading 2.


```
        Heading 1
        =
        Heading 2
        - 
```


Now, let’s see how it looks on GitHub.




<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



        Headings


## **Text styles**

Using markdown syntax, we can change texts’ styles, including bold, italic, blockquotes, monospaced, underlined, strike-through, boxed, subscript, and superscript.

We can use two asterisks (`**`), underscores (`__`), or an HTML tag `&lt;strong>` to make a text bold. To make text italic, we can use one asterisk (`*`), underscore (`_`), or an HTML tag `&lt;em>`. Also, we can make the text bold and italic at the same time.


```
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



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")




<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")




<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")



        Bold and Italic text styles

To create blockquote, we can use the greater than sign `>`. We can create a single-line or multi-line blockquote. Also, blockquote inside a blockquote. We can add other text styles inside a blockquote, such as bold or italic text styles.


```
        Blockquotes
        > The quick brown fox jumps over the lazy dog.
        > The quick brown fox jumps over the lazy dog.
        >
        > The quick brown fox jumps over the lazy dog.
        >
        > The quick brown fox jumps over the lazy dog.
        > The quick brown fox jumps over the lazy dog.
        >> The quick brown fox jumps over the lazy dog.
        >>> The quick brown fox jumps over the lazy dog.
        > **The quick brown fox** *jumps over the lazy dog.*
```


Now, let’s see how it looks on GitHub.




<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")



        Blockquotes text styles

We can achieve monospaced, and underlined styles using HTML tags `&lt;samp>` and `&lt;ins>`. For a strike-through style, we can use two tilda sign `~~`.


```
        Monospaced
        <samp>The quick brown fox jumps over the lazy dog.</samp>

        Underlined
        <ins>The quick brown fox jumps over the lazy dog.</ins>

        Strike-through
        ~~The quick brown fox jumps over the lazy dog.~~
```


Now, let’s see how it looks on GitHub.



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")




<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")




<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")



        Monospaced, Underlined, and Strike-through text styles

We can use an HTML `&lt;table>` tag to create a box.


```
        Boxed
        <table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
```


Now, let’s see how it looks on GitHub.




<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")



        Boxed text style

We can achieve subscript and superscript styles using HTML tag `&lt;sub>` and `&lt;sup>`. It is useful when you’re writing a mathematical formula.


```
        Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
        Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
```


Now, let’s see how it looks on GitHub.




<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")



        Subscript and Superscript text styles


## **Syntax Highlighting**

We can use a single backtick ``` before and after the code block to create the following view.


```
        A class method is an instance method of the class object. When a new class is created, an object of type `Class` is initialized and assigned to a global constant (Mobile in this case).
```


As you can see the word **Class** is highlighted.




<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")



        Code Highlighting

We can also use triple backticks ````` before and after the code block to create the following view.


```
        ```
        public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
        ```
```





<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")



        Code Highlighting

We can add an optional language identifier to enable syntax highlighting. Refer to [this](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml) and [this](https://github.com/github/linguist/tree/master/vendor) GitHub documents to find all the valid keywords.


```
        ```java
        public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
        ```
```


Now, let’s see how it looks on GitHub.




<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")



        Syntax Highlighting


## **Alignments**

By using HTML tags, we can align README contents.


```
        <p align="left">
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
        </p>
```





<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")



        Left align


```
        <p align="center">
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
        </p>
```





<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")



        Center align


```
        <p align="right">
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
        </p>
```





<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image16.png "image_tooltip")



        Right align

Now, let’s align a text.


```
        <h3 align="center"> My latest Medium posts </h3>
```





<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image17.png "image_tooltip")



        Center align


## **Tables**

Let’s create a table without headers.


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
```





<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image18.png "image_tooltip")



        Table without header

To create a table with headers we need to use dashes to separate each header cell and use pipes to separate columns. The outer pipes are optional. We can use any number of dashes and spaces to increase readability. We can use colons to align columns. For left-align text, use a colon to the left of dashes. For center-align text, use a colon on both sides of dashes. For right-align text, use a colon to the right of dashes. By default Left align is used.


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
```





<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image19.png "image_tooltip")



        Table with different alignments

Now display two tables side by side.


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
```





<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image20.png "image_tooltip")



        Display two tables side by side

Let’s create a table with multiple lines using the HTML `&lt;br/>` tag.


```
        | A | B | C |
        |---|---|---|
        | 1 | 2 | 3 <br/> 4 <br/> 5 |
```





<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image21.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image21.png "image_tooltip")



        A table with multiple lines


## **Links**

We can create a link in four ways. The first one is by using an inline style. The second one uses reference style, the third one using relative links, and finally auto links.


```
        [The-Ultimate-Markdown-Cheat-Sheet (https://github.com/lifeparticle/Markdown-Cheatsheet)
```





<p id="gdcalert22" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image22.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert23">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image22.png "image_tooltip")



        Inline-style

If you’re using the same link more the once, then using the reference style would be beneficial since you don’t have to write the link every time, and also, it’s easy to update the link. Moreover, you can use numbers for the reference text. Also, you can use the reference text as the link text.


```
        [The-Ultimate-Markdown-Cheat-Sheet][reference text]
        [The-Ultimate-Markdown-Cheat-Sheet][1]
        [Markdown-Cheat-Sheet]
        [reference text]: https://github.com/lifeparticle/Markdown-Cheatsheet
        [1]: https://github.com/lifeparticle/Markdown-Cheatsheet
        [Markdown-Cheat-Sheet]: https://github.com/lifeparticle/Markdown-Cheatsheet
```





<p id="gdcalert23" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image23.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert24">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image23.png "image_tooltip")



        Three variations of reference-style

We can also create relative links with all relative link operands, such as `./` and `../`.


```
        [Example of a relative link](rl.md)
```





<p id="gdcalert24" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image24.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert25">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image24.png "image_tooltip")



        Example of a relative link

GitHub can automatically create links from standard URLs.


```
        Visit https://github.com/
```





<p id="gdcalert25" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image25.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert26">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image25.png "image_tooltip")



        Auto link


## **Images**

We can add images using the similar techniques we used for links.


```
        ![alt text](https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80)
```





<p id="gdcalert26" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image26.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert27">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image26.png "image_tooltip")



        Inline-style


```
        ![alt text][image]
        [image]: https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=100&q=80
```





<p id="gdcalert27" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image27.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert28">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image27.png "image_tooltip")



        Reference-style

Also, we can use the HTML `img` tag to add an image.


```
        <img src="https://images.unsplash.com/photo-1415604934674-561df9abf539?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2772&q=80" width="100" height="100" border="10"/>
```





<p id="gdcalert28" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image28.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert29">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image28.png "image_tooltip")



        img tag

We can also embed GIF and SVG.


```
        <img src="https://media.giphy.com/media/qLHzYjlA2FW8g/giphy.gif" />
```





<p id="gdcalert29" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image29.gif). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert30">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image29.gif "image_tooltip")



        GIF


```
        <img src="https://img.shields.io/badge/theultimatemarkdowncheatsheet-brightgreen.svg" />
```





<p id="gdcalert30" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image30.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert31">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image30.png "image_tooltip")



        SVG


## **Lists**

For lists, we can have ordered and unordered lists.


```
        1. One
        2. Two
        3. Three
```





<p id="gdcalert31" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image31.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert32">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image31.png "image_tooltip")



        An ordered list

Now let’s create an ordered list with sub-items.


```
        1. First level
           1. Second level
               - Third level
                   - Fourth level
        2. First level
           1. Second level
        3. First level
           1. Second level
```





<p id="gdcalert32" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image32.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert33">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image32.png "image_tooltip")



        An ordered list with sub-items

To create an unordered list, we can asterisk, plus, or minus sign.


```
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





<p id="gdcalert33" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image33.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert34">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image33.png "image_tooltip")



        Unordered lists

Now let’s create an unordered list with sub-items.


```
        - First level
           - Second level
               - Third level
                   - Fourth level
        - First level
           - Second level
        - First level
           - Second level
```





<p id="gdcalert34" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image34.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert35">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image34.png "image_tooltip")



        An unordered list with sub-items

We can also use HTML to create a list.


```
        <ul>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
        <li>Fourth item</li>
        </ul>
```





<p id="gdcalert35" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image35.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert36">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image35.png "image_tooltip")



        A list using HTML

Now let’s create a task list. We can create a task list using a hyphen followed by `[ ]`, and to mark a task complete, put an `x` inside the brackets.


```
        - [x] Fix Bug 223
        - [ ] Add Feature 33
        - [ ] Add unit tests
```





<p id="gdcalert36" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image36.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert37">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image36.png "image_tooltip")



        Tasklist


## **Horizontal Rule**

We can use three hyphens, asterisks, or underscores to create a horizontal line.


```
        ---
        ***
        ___
```





<p id="gdcalert37" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image37.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert38">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image37.png "image_tooltip")



        Horizontal Rule


## **Miscellaneous**

We can include comments inside a `.md` file.


```
        <!--
        Lorem ipsum dolor sit amet
        -->
```


We can use a backslash to escape literal characters. Before escaping.


```
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





<p id="gdcalert38" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image38.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert39">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image38.png "image_tooltip")



        Before escaping

After escaping.


```
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





<p id="gdcalert39" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image39.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert40">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image39.png "image_tooltip")



        After escaping

We can also include [emojis](https://gist.github.com/rxaviers/7360908) in our `.md` file.


```
        :octocat:
```





<p id="gdcalert40" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image40.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert41">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image40.png "image_tooltip")



        An octocat emoji

We can mention a person or team by typing `@` with their username or team name.


```
        @lifeparticle
```





<p id="gdcalert41" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image41.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert42">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image41.png "image_tooltip")



        Mention a person

We can also bring up a list of suggested issues and pull requests within the repository by typing `#`.


```
        #
```




<p id="gdcalert42" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image42.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert43">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image42.png "image_tooltip")





<p id="gdcalert43" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image43.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert44">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image43.png "image_tooltip")
Referencing issues and pull requests


## **Bitbucket**

Bitbucket Supported Markdown for [READMEs](https://bitbucket.org/tutorials/markdowndemo/src/master/). Also, [create a table of contents](https://support.atlassian.com/bitbucket-cloud/docs/add-a-table-of-contents-to-a-wiki/).


## **Tools**

There are various tools for Markdown, which will help you to build a beautiful GitHub README faster.



1. Create a Markdown table of content — [GitHub](https://github.com/ekalinin/github-markdown-toc)
2. Create an empty Markdown table — [Tablesgenerator](https://www.tablesgenerator.com/markdown_tables)
3. Convert Excel to Markdown table —[ Tableconvert](https://tableconvert.com/)
4. Markdown preview for Sublime Text 3 — [Packagecontrol](https://packagecontrol.io/packages/MarkdownPreview)
5. Markdown preview Visual Studio Code — [Marketplace](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
