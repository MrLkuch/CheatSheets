# Markdown
<br>

- ## Emphasis

    ### _Italic_  
        - \_Italic_
        - \*Italic*



    ### **Bold**

        - \**Bold**
        - \__Bold__



    ### **_Combined_**
        - \**\_Combined_**



    ### ~~Scratch~~
        - \~~scratch~~

<br>

## Lists


### Unordered list:  
   
     * item1  
     * item2  
     * item3  
   
  Result:  
   
   » item1                                                                       
   » item2                                                                       
   » item3                                                                       

   Or: 
   
     - first item with dash  
     - second item with dash

  Goes to:  
   
    » first item with dash                                                        
    » second item with dash 

### Ordered lists  
   
    
   
     1. item1  
     2. item2  
     3. item3  
   
  Which will be transformed into:  
   
   1. item1  
   2. item2  
   3. item3  
   
  As you may see, this notation is very intuitive and readable.  
   
 ### Nested lists  
   
  nested list. Just add a tab, or  
  spaces for nested elements:  
   
     - element 1  
       - element 1.1  
       - element 1.2  
     - element 2  
       - element 2.1  
     - element 3  
   
  For lists with * and ordered lists it works as well.

  <br>

  ## Links

  [NodeSchool Site][ref]  
     [GitHub][1]  
     [Remark parser]  
       
     Some text to show that the reference links can follow later:  
       
     [ref]: http://www.nodeschool.io  
     [1]: https://github.com/  
     [Remark parser]: http://remark.js.org/  

<br>

## Images

    ![alt text](url)

Or :

   The reference style also works for images. You can do something like this:  
   
     ![reference style][logo]  
       
     [logo]: ./logo.png 

<br>

## Blockquotes

The syntax of blockquotes is simple:  
   
     > This is my blockquote.  
     > This line is part of the same quote.  
   
  This will look like this:  
   
   > This is my blockquote. This line is part of the same quote.

You are able to put Markdown into a blockquote, therefore this will work  
  as well:  
   
     > **Markdown** is a _lightweight markup language_ with plain text formatting syntax designed so that it can be converted to **HTML** and many other formats.  
     > - from [Wikipedia](https://en.wikipedia.org/wiki/Markdown) 


> **Markdown** is a _lightweight markup language_ with plain text formatting syntax designed so that it can be converted to **HTML** and many other formats.  
     > - from [Wikipedia](https://en.wikipedia.org/wiki/Markdown) 

<br>

## Code

     ```js  
     console.log('This is JavaScript syntax highlighting!');  
     ```  
       
     ```  
     No language indicated, so no syntax highlighting.  
     ```    

```js  
     console.log('This is JavaScript syntax highlighting!');  
```    
```
No language indicated, so no syntax highlighting.  
```  
<br>

## Tables

The creation of tables in Markdown looks exactly like drawing using dashes  
  (-) and pipes (|). Also, you may use colons to align columns. For example:  
   
     | Head         | of       | Table         |  
     | ------------ |:--------:| ------------ :|  
     | left-aligned | centered | right-aligned |  
     | left-aligned | centered | right-aligned |  
   
  The table above will be rendered like this:

| Head         | of       | Table         |  
| ------------ |:--------:| ------------ :|  
| left-aligned | centered | right-aligned |  
| left-aligned | centered | right-aligned |  

<br>

There are a few important things here:  
   
   - There must be at least 3 dashes separating each header cell. Colons to                                                                            
     align columns count as dashes.                                              
   - The outer pipes (|) are optional.                                           
   - You can use inline Markdown in cells.                                       
   
  That means you can do something like this:

       Markdown | Less | Pretty  
     --- | --- | ---  
     *Still* | `renders` | **nicely** 


Markdown | Less | Pretty  
--- | --- | ---  
*Still* | `renders` | **nicely** 

<br>

## Horizontal Rules

There's nothing hard to make a horizontal rule in Markdown. Just type  
  three or more dashes (-), asterisks (*) or underscores (_):  
   
     Dashes  
       
     ---  
       
     Asterisks  
       
     ***  
       
     Underscores  
       
     ___  
   
  And it will turn into:

Dashes  
       
---  
       
Asterisks  
       
***  
       
Underscores  
       
___  


<br>

## HTML

 If you want to style something more than is allowed in Markdown, you can  
  use raw HTML in your Markdown and it'll work pretty well.  
   
     <p align="center">Centered text works well!</p>  
   
  And you will get a centered paragraph. 

<p align="center">Centered text works well!</p>

<br>

## GFM


### SHA references  
   
  Any reference to a commit’s SHA-1 hash will be automatically converted  
  into a link to that commit on GitHub:  
   
     4ad0c921206dec4d1518f4aeead932e7617f934f  
     denysdovhan/how-to-markdowkn@4ad0c921206dec4d1518f4aeead932e7617f934f  
   
 ### Issue and Pull request references  
   
  Any number that refers to an Issue or Pull Request will be automatically  
  converted into a link:  
   
     #1  
     denysdovhan/how-to-markdowkn#1  
     
   
 ### Username @mentions  
   
  Typing an @ symbol, followed by a username, will notify that person to  
  come and view the comment. This is called a @mention, because you’re  
  mentioning the individual. You can also mention @teams within an  
  organization.  
   
 ### Emoji  
   
  It's a funny part, but it's still important. GFM also supports emoji!  
   
  ✨ 🐫 💥  
   
  To see a list of every emoji that is supported, check out the [Emoji Cheat  
  Sheet](http://www.emoji-cheat-sheet.com/). 