# INTRODUCTION TO MARKDOWN

<!--HEADING-->
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

##### Heading 6

---

<!--Italics-->

_This is going to be a paragraph that is using italic styling_
*This is going to be a paragraph that is using italic styling*


***

<!--Strong-->

This is an example of **strong text** , anything between the two opening asterisk and closing asterisk will be display as **strong text**

Tis is another example of a way to have __strong text in our document. Anything between the two double opening underscore and closng underscore will be displayed as __strong text__

<!--strike Through-->

Ths is an example of a ~~striketrough~~ text, anythng in between the double tilde opening characters and closing double tilde characters will be displayed as ~~strike through~~ text

---
<!--Horizontal rule-->

We can add triple hypens to be able to create a horizontal rule for separating content.

Another way to add __HORIZONTAL RULES__ in our documents markdown is by using three underscores
___

<!--Escape Characr Rule Using Backslash-->

This is an example of a *text with an asterisk* When we don't want it to be italicized. We want to  the backlash \ to escape the rule of using an opening \*asterisk* and closing \*asterisk*
 to inclose the text without contents.

---

<!--Blockquote Rule-->

> We use the greater than symbol to display a block of texas a quiate with a background and line on the left side.

> "You don't have to be great to start, but you need to start to be great." - __Unknown Author__

---
<!--Link Rule-->

**NOTE**: We would want to put the link desciption inside of square bracketand the ink to the resource inside of two open and close parenthesis.
[RBSLOPEZ_pexels_collection_profile](https://www.pexels.com/@rodrigo-bonzerr-s-lopez-462356/)

__NOTE__: We can add a baloon tip description to our link by using double quotes after the link to the resource
[RBSLOPEZ_pexels_collection_profile](https://www.pexels.com/@rodrigo-bonzerr-s-lopez-462356/ "This is RBSLOPEX pexel photo collection")

---

<!--list item rules-->

<!--UNORDERED LIST-->

* Item 1 - This is going to be our list item 1
  *  this is our list item 1 child item 1
  *  this is our list item 2 child item 2
* Item 2 - This is going to be our list item 2
  *  this is our list item 1 child item 1
  *  this is our list item 2 child item 2
* Item 3 - This is going to be our list item 3
  *  this is our list item 1 child item 1
  *  this is our list item 2 child item 2
* Item 4 - This is going to be our list item 4
  *  this is our list item 1 child item 1
  *  this is our list item 2 child item 2
* Item 5 - This is going to be our list item 5
  *  this is our list item 1 child item 1
  *  this is our list item 2 child item 2

<!--ordered list-->

1. Item 1 - This is going to be our list item 1
  
     1.1 this is our list item 1 child item 1
  
     1.2  this is our list item 2 child item 2
  
2. Item 2 - This is going to be our list item 2

     2.1  this is our list item 1 child item 1
  
     2.2  this is our list item 2 child item 2
  
3. Item 3 - This is going to be our list item 3

     3.1  this is our list item 1 child item 1
  
     3.2  this is our list item 2 child item 2
  
4. Item 4 - This is going to be our list item 4

     4.1  this is our list item 1 child item 1
  
     4.2  this is our list item 2 child item 2
  
5. Item 5 - This is going to be our list item 5

     5.1  this is our list item 1 child item 1
   
     5.2  this is our list item 2 child item 2

---

**NOTE**: *__Backtics__ will allow us to show the code block or the paragraph tags in this example. It is located below the tlide character and on topof the tab key.*
<!--code ock inline example rule-->

`<p> This is a paragram tag with an inline code block example and cosing tag </p>`

---

<!--GITHUB FLAVOR SET OF CODE BLOCK-->
<!--CODE BLOCKS FOR GITHUB DOCUMENTATION-->

```bash
npm install

npm start
```

**NOT**: You can specify some syntax code blocks for different languages 

```javascript
function testAdd(num1,num2){ 
  return num1 + num2;
}
```

```python
def pythonAdd(num1,num2):
  return num1 + num2;
```
```C#
   public static int Sum(int num1, int num2)
   {
   int total;
   total = num1 + num2;
   return total;
   }

```

<!--Table rules-->

| Name | Nickname | Email |
|------|----------|---------------------|
|Emilio| Tubao    |emiliotubao@gmail.com|
|Eyong | Tubao    |eyongtubao@gmail.com |
|Yawnskii|Perdon  |yawnskiiperdon@gmail.com|


