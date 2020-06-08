# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false] `<div><span>hello</div></span>`

b) [false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?
A screenreader is a software that 'reads' the code of a website and outputs a format of the code that is accessible to folks who are unable to interact with websites without readers, due to special needs. Output is usually in braile or voice. 
https://www.smashingmagazine.com/2018/12/voiceover-screen-reader-web-apps/
_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img></img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ol> and <a>
c) You want to sell designer hats. You need to receive orders from the user.
<input>
## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No. THe best answer I could find is from here:
    https://html.spec.whatwg.org/multipage/form-elements.html#the-button-element
        "Most elements that are categorized as phrasing content can only contain elements that are themselves categorized as phrasing content, not any flow content."

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a` 
anchor tag, for links to another website
b) `ol`
ordered list
c) `ul`
unordered list
d) `li`
an item in a list
e) `tr`
table row
f) `th`
table head
g) `td`
table data
## Q7 - Usually, `td` elements are children of what kind of elements?
table
## Q8 - What is the difference between td and th?
td contains data in a table, th is the descriptive head of the table
## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1
## Q10 - In which situation can you use self closing tags?
If your element does not have any children
## Q11 - What is autofilling and why is it important?
Your computer autofills information in a form that is similar to one you have already filled out. This saves a lot of time.
## Q12 - Which attributes are always present in an img element?
src and alt
## Q13 - Which attribute is always present for an anchor tag?
href