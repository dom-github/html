# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>`

a fixed:  `<div><span>hello</span></div>`

b) [False]

```html
<ul>
<li>one</li>
</ol>
```
b fixed:

```html
<ul>
    <li>one</li>
</ul>
```


c) [False] `<ul></ul><img/><ol><li>one</li></ol>`

c fixed:
<img 
src=""
alt="No src"
/>
<ol>
    <li>one</li>
</ol>



## Q2 - What is a screenreader and why should we care about them?
A screenreader is software that interprets web pages into audio for the visually impaired. We should care about screenreaders since they use the page's HTML code to prioritise or order the information when it is presented to the user. 

Source: Today's HTML presentation!

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img></img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ul></ul>
<li></li>
<a href="www.artgallerywebsitesinmycity.com">Galleries</a>

c) You want to sell designer hats. You need to receive orders from the user.
<form></form>
<input></input>


## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No, 'button' is a clickable element, it's descendants cannot also be clickable elements.

## Q5 - What is the most generic tag you can use?
<div></div>

## Q6 - What do the following achronyms stand for?

a) `a`
anchor

b) `ol`
ordered list

c) `ul`
unordered list

d) `li`
list item

e) `tr`
table row

f) `th`
table head  

g) `td`
table data

## Q7 - Usually, `td` elements are children of what kind of elements?
`td` elements are usually children of `table` elements.

## Q8 - What is the difference between td and th?
`th` is the table head and indicates the header of the column. `td` is table data, which can be anywhere in the table and is always a child of `tr` row elements.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
`h1` and `h3` are used to mark the Title and sub-sub-sections respectively, but are not intrinsically related to text size. 

## Q10 - In which situation can you use self closing tags?
If the element has no children, you can use a self closing tag.

## Q11 - What is autofilling and why is it important?
Autofilling is when the browser completes input fields for the user, for convenience. It is important to keep in mind since input elements can only be autofilled inside forms.

## Q12 - Which attributes are always present in an img element?
`scr=`
`alt=`
## Q13 - Which attribute is always present for an anchor tag?
`href=`