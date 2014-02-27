# Theme/Css Test file
## Normal text
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nec justo vulputate, volutpat orci id, facilisis erat. Morbi sed auctor metus. Curabitur ut aliquet nulla, sit amet congue nisi. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Sed euismod, mi non iaculis ultrices, mi metus varius nisi, vel porttitor urna arcu at est. Vestibulum lobortis blandit tellus, sit amet dictum sem lobortis nec. Aliquam nec lacinia ligula, a hendrerit diam. Nunc blandit lacus vitae velit elementum viverra.

Suspendisse potenti. Proin eu ante non turpis aliquam faucibus. Cras vestibulum magna sit amet metus vehicula semper. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Suspendisse blandit mattis tempus. Mauris vitae nunc venenatis, pharetra dui volutpat, dignissim eros. Aenean ac libero nec orci bibendum imperdiet. Aliquam laoreet augue at interdum pharetra. Nunc dolor purus, accumsan quis porttitor eu, viverra et mauris.

## Headers

    # Header 1
    ## Header 2
    ### Header 3
    #### Header 4
    ##### Header 5
    ###### Header 6    
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Strong
    **strong**
    __strong__
**strong**  
__strong__

## Emphasize
    *emphasize*
    _emphasize_
*emphasize*  
_emphasize_

## Links and Email
    [http://example.com](http://example.com)
    <example@example.com>
    
    [example][id]
    [id]: http://example.com/ "Title"
    
[http://example.com](http://example.com)

<example@example.com>

[example][id]

[id]: http://example.com/ "Title"
    
## Images
    ![alt text](/path/img.jpg "Title")
    
    ![alt text][id]
    [id]: /url/to/img.jpg "Title"

![alt text](/path/img.jpg "Title")
    
![alt text][id]

[id]: /url/to/img.jpg "Title"

## Lists
**Ordered**

    1. Foo
    2. Bar

1. Foo
2. Bar

**Unordered**
 
    *   A list item.
    
        With multiple paragraphs.
    
    *   Bar

* A list item.

    With multiple paragraphs.
* Bar

## Blockquotes
    > Email-style angle brackets
    > are used for blockquotes.
    
    > > And, they can be nested.
    
    > #### Headers in blockquotes
    > 
    > * You can quote a list.
    > * Etc.

> Email-style angle brackets
> are used for blockquotes.

> > And, they can be nested.

> #### Headers in blockquotes
> 
> * You can quote a list.
> * Etc.

## Inline Code
    `Code`
`Code`
## Block Code
        Code block
        with multilines
-

    Code block
    with multilines
    
**Fenced**

    ```
    Code
    with multiple lines
    ```

```
Code
with multiple lines
```
## Horizontal rules
    ---
    * * *
    - - - -
    
---
* * *
- - - -

## Hard link breaks
    line  
    line
line  
line

## Footnotes
    footnote.[^1]
    
    [^1]: This is a note

footnote.[^1]

[^1]: This is a note

## Strikethrought
    ~~text~~

~~text~~

## Tables
    H1 | H2 | H3
    -- | -- | --
    C1 | C2 | C3

H1 | H2 | H3
-- | -- | --
C1 | C2 | C3

    Header Left    | Header Centered    | Header Right 
    :------------- | :----------------: | --------------:
    Left    | Center    | Right   

Header Left    | Header Centered    | Header Right 
:-- | :--: | --:
Left    | Center    | Right   

## Anchor
    **[Title](id:anchor1)**
**[Title](id:anchor1)**

    Click this [link](#anchor1) to go to title.
Click this [link](#anchor1) to go to title.