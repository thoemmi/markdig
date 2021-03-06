# Extensions

The following additional list items are supported:

## Ordered list with alpha letter
 
Allows to use a list using an alpha letter instead of a number

```````````````````````````````` example
a. First item
b. Second item
c. Last item
.
<ol type="a">
<li>First item</li>
<li>Second item</li>
<li>Last item</li>
</ol>
````````````````````````````````

It works also for uppercase alpha: 

```````````````````````````````` example
A. First item
B. Second item
C. Last item
.
<ol type="A">
<li>First item</li>
<li>Second item</li>
<li>Last item</li>
</ol>
````````````````````````````````

Like for numbered list, a list can start with a different letter

```````````````````````````````` example
b. First item
c. Second item
.
<ol type="a" start="b">
<li>First item</li>
<li>Second item</li>
</ol>
````````````````````````````````

A different type of list will break the existing list:

```````````````````````````````` example
a. First item1
b. Second item
A. First item2
.
<ol type="a">
<li>First item1</li>
<li>Second item</li>
</ol>
<ol type="A">
<li>First item2</li>
</ol>
````````````````````````````````

## Ordered list with roman letter

Allows to use a list using a roman number instead of a number.
 
```````````````````````````````` example
i. First item
ii. Second item
iii. Third item
iv. Last item
.
<ol type="i">
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Last item</li>
</ol>
````````````````````````````````

It works also for uppercase alpha: 
 
```````````````````````````````` example
I. First item
II. Second item
III. Third item
IV. Last item
.
<ol type="I">
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Last item</li>
</ol>
````````````````````````````````

Like for numbered list, a list can start with a different letter

```````````````````````````````` example
ii. First item
iii. Second item
.
<ol type="i" start="ii">
<li>First item</li>
<li>Second item</li>
</ol>
````````````````````````````````
