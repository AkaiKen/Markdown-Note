# Markdown Gramma Note
## 1. Title

write has character `#` at the beginnig.
There are six level title

```
# level 1
## level 2
...
###### level 6
```


>notes: Don't forget space between hash characters and the text.


Using any number of `=` or `-` in the next line also works, which correspond to first-level headers and second-level-headers.

```
level 1
=======

level 2
-------
```

- # First-level headers
- ## Second-level headers
- ### Thrid-level headers
- #### Forth-level headers
- ##### Fifth-level headers
- ###### Sixth-level headers

---

## 2. Font

- *italic*
```
Italic with *asterisks* or _underscores_
```
- **Bold**
```
Bold with **asterisks** or __underscores__
```

- ***combined***
```
Combined emphasis with ***asterisks*** or ___underscores___
```

- ~~Scratch~~
```
~~Scratch me~~
```
---

## 3. Blockquotes
The syntax of blockquotes use character `>`:
```
> Blockquotes.
> At the same line of previous code.
```
> Blockquotes.
> At the same line of previous code.

---

## 4. Horizontal
Using three or more `-` or `_` or `*`:
```
Dashes

---

Asterisks

***

Underscores

___
```
They will run into:

Dashes

---
Asterisks
***
Underscores
___


note: Remember the space line between text and these characters, or it may become **second-level title**

---

## 5. Picture
Markdown also can insert images.
![markdown](./image/markdown.png)
By using 
```
![title](url)
```
url can use the link on the internel or the relative position in the native file.
```
![title](https://google.xxxxxxx.com)
![title](./markdown.png)
```

---

## 6. List
You can use asterisk `*` or dash `-` to create a list mark. Remember a `space` after the character.
```
- list 1
- list 2
- list 3
```
- list 1
- list 2
- list 3

Also, use `TAB` before character can set the level of lists. And there are 3 different marks while using the level list.
```
- list level 1
    - list level 2
        - list level 3
            - list level 4 (the mark is same as the third)
```
- list level 1
    - list level 2
        - list level 3
            - list level 4 (the mark is same as the third)


## 7. Table
Markdown also support table.

We use `|` to seperate column and `---` to seperate head and contents.

Notice that few important things:
- number of dash to seperate head must be at least 3
- the outer `|` are optional
- using markdown gramma inline is enabled

```
| head | of | table|
|---|---|---|
| *markdown* | `use` | **inline**
***line*** |  | ~~outer~~ 
```

| head | of | table|
|---|---|---|
| *markdown* | `use` | **inline**
***line*** |  | ~~outer~~ 

---
## 8. Checkbox  
use `- [ ]`to set checkbox
```
- [x] checkbox complete
- [ ] checkbox incomplete
```
- [x] checkbox complete
- [ ] checkbox incomplete

---

## 9. Links 
The easist way to make link is just paste the URL.
```
https://www.google.com
```
https://www.google.com

While it seems not pretty well than what we want. Because some times if URLs are too long it is hard to review other contents.

### **Inline style**
Just like images link but withou `!`.
```
[text](herf"alt")
```
For exampe:
```
[google](www.google.com)
```
[google](www.google.com)

### **Reference style**
When there are some website that using in many place, it is convenient to set with reference style:
```
[g]: www.google.com
[google][g]
```
[g]: www.google.com
[google][g]

---

## 10. HTML
We can also use HTML in markdown.
```
<p align="center"> <font color=red size=6> center text using HTML </font></p><br>
```
<p align="center"> <font color=red size=6> center text using HTML </font></p><br>

Other HTML grammar is acceptable.
> notice that by using `<br>` or `<br/>` markdown will create an empty line.

---

## 11. Latex
All math formula type in latex is enabled.
```
$\beta\alpha = \sum_{i=1}^n{\theta}$
```
$\beta\alpha = \sum_{i=1}^n{\theta}$
