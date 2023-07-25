# INTRODUCTION TO MARKDOWN

<!--HEADING-->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

<!--Italics-->

_This is going to be a paragraph that is using italic styling_

*This is going to be a paragraph that is using italic styling*

---

<!--Strong-->
This is an example of **strong text**, anything between the two opening asterisk and two closing asterisk will be displayed as strong text

This is another example way to have a __strong text__ in our document. Anything between the two double opening underscore and two double closing underscore will be displayed as __strong text__

<!--Strike Through-->
This is an example of a ~~strike through~~ text, anything in between the double tilde opening characters and closing double tilde characters will be displayed as ~~strike through~~ text

<!--Horizontal Rule-->

We can add triple hyphens to be able to create a horizontal rule for separating content.

Another way to add __HORIZONTAL RULES__ in our document is by using three underscores.

___

<!--ESCAPE Character Rule using Backslash-->

This is an example of a *text with an asterisk*. When we don't want it to be italicized. We want to use the backslash to escape the rule of using an opening \*asterisk* and closing \*astersik* to enclose the text contents.

___

<!--Blockquote Rule-->

> We use the greater than symbol to display a block of text as a quote with a background and line on the left side.

> *"You don't have to be great to start, but you need to start to be great."* -Unknown Author


---

<!Link Rule-->

**NOTE** We would want to put the link description inside of square brackets and the link to resource inside of an open and close parenthesis. 
[Cute Dog](https://images.pexels.com/photos/5122188/pexels-photo-5122188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

__NOTE__! We can add a balloon tip description to our link by using double quotes after the link to the resource.

[Cute Dog](https://images.pexels.com/photos/5122188/pexels-photo-5122188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1/ "This is a Pexel Photo")

___

<!--List Item Rules-->

<!--UNORDERED LISTS-->

* Item 1 - This is going to be our list item 1
  * This is our list item 1 child item 1
  * This is our list item 1 child item 2
* Item 2 - This is going to be our list item 2
  * This is our list item 2 child item 2
  * This is our list item 2 child item 2
* Item 3 - This is going to be our list item 3
  * This is our list item 3 child item 3
* Item 4 - This is going to be our list item 4
  * This is our list item 4 child item 4
 
<!--ORDERED LISTS-->

1. Item 1 - This is going to be our list item 1
   
    1.1 This is our list item 1 child item 1
   
    1.2 This is our list item 1 child item 2
   
2. Item 2 - This is going to be our list item 2
   
    2.1 This is our list item 2 child item 1

    2.2 This is our list item 2 child item 2
  
3. Item 3 - This is going to be our list item 3
   
    3.1 This is our list item 3 child item 1

    3.2 This is our list item 3 child item 2
    
4. Item 4 - This is going to be our list item 4
   
    4.1 This is our list item 4 child item 1

    4.2 This is our list item 4 child item 2


<!--Code Block Inline Example Rule-->

**NOTE**: *__Backtics__ will allow us to show the block or paragraph tags in this example. It is located below the tilde character and on top of the tab key*

`<p>This is a paragraph tag with an inline code block example opening and closing tags</p> `

---

<!--IMAGE rule-->


![This is an image](https://images.pexels.com/photos/911806/pexels-photo-911806.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1 "Link to a dog image")

---

<!--GITHUB FLAVOR SET OF CODE BLOCK-->

<!--CODE BLOCKS FOR GITHUB DOCUMENTATION-->

```install npm
npm install

npm start
```

---

**NOTE**: You can specify some syntax code blocks for differente languages

```javascript
function tesAdd(num1, num2){
  return numq + num2;
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
 total = num2 + num2;
 return total;
}
```
 
<!Table Rules-->

| Name | Nickname | Email          |
|------|----------|----------------|
| John | Jo       |john@gmail.com  |
| Rod  | Elicid   |testCi@gmail.com|


---
<!--Tasks Lists-->

* [x] Task 1
* [x] Task 2
* [ ] Task 3
* [ ] Task 4
