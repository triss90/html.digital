

## Layout

Simple semantic HTML:



## Typography

# Header 1

`<h1>Header</h1>`  

## Header 2

`<h2>Header</h2>`  

### Header 3

`<h3>Header</h3>`  

#### Header 4

`<h4>Header</h4>`  

##### Header 5

`<h5>Header</h5>`  

###### Header 6

`<h6>Header</h6>`  

**Horizontal line**

* * *


Regular body text

`<p>Regular body text</p>`  

<small>Small text</small>  
`<small>Small text</small>`  

<sup>Superscript Text</sup>  
`<sup>Superscript text</sup>`  

<mark>Marked Text</mark>  
`<mark>Marked text</mark>`  

_Italic text_, _emphasized text_  
`<i>Italic text</i>`, `<em>emphasized text</em>`  

**Bold text**, **strong text**  
`<b>Bold text</b>`, `<strong>strong text</strong>`  

*   Unordered list

`<ul><li>Unordered list</li></ul>`  

1.  Ordered list

`<ul><li>Ordered list</li></ul>`  


* * *


## Code and Quotes

### Inline Code

`<code>Inline code</code>`  

### Codeblocks

<samp><samp>Code block</samp></samp>

### blockquote

> "this is an awesome quoteblock"
> 
> <footer>_- [Tristan White](https://triss.dev), Author of html.digital_</footer>


* * *

<article>

## Forms

### Inputs

#### Text

<input type="text" placeholder="Type some text"> <samp><input type="text" placeholder="Type some text"></samp>

#### Date

<input type="date" min="2000-01-01" max="2030-12-31"> <samp><input type="date" min="2000-01-01" max="2030-12-31"></samp>

#### Colour

<input type="color" value="#dd0a35"> <samp><input type="color" value="#dd0a35"></samp>

#### Select

<select name="" id=""><option value="">Option 1</option> <option value="">Option 2</option> <option value="">Option 3</option></select> <samp><select> <option>Option 1</option> <option>Option 2</option> <option>Option 3</option> </select></samp>

#### Checkbox

<input type="checkbox" id="checkbox1"> <label for="checkbox1">Normal</label>  
<input type="checkbox" id="checkbox2" checked=""> <label for="checkbox2">Checked</label>  
<input type="checkbox" id="checkbox3" disabled=""> <label for="checkbox3">Disabled</label>  
<samp><input type="checkbox" id="checkbox1"> <input type="checkbox" id="checkbox2" checked> <input type="checkbox" id="checkbox3" disabled></samp>

#### Radio

<input type="radio" id="radio1" name="radio"> <label for="radio1">Normal</label>  
<input type="radio" id="radio2" name="radio" checked=""> <label for="radio2">Checked</label>  
<input type="radio" id="radio3" name="radio" disabled=""> <label for="radio3">Disabled</label>  
<samp><input type="radio" name="radio" id="radio1"> <input type="radio" name="radio" id="radio2" checked> <input type="radio" name="radio" id="radio3" disabled></samp>

#### button

<input type="submit" value="Click me"> <samp><input type="submit" value="Click me"></samp>

#### Textarea

<textarea cols="30" rows="10" placeholder="Type some text"></textarea><samp><textarea cols="30" rows="10" placeholder="Type some text"></textarea></samp>

### Output

<form id="calc" oninput="calculation.value = parseInt(number_one.value)+parseInt(number_two.value)+parseInt(number_three.value); number_one_output.value = parseInt(number_one.value); number_one_output.style.left = parseInt(number_one.value)-2 + '%';">

<output name="number_one_output" id="number_one_output" for="number_one" form="calc">65</output>

<input type="range" name="number_one" id="number_one" value="65">  
<input type="number" name="number_two" id="number_two" value="30">  

<select name="number_three" id="number_three"><option value="10">10</option> <option value="20">20</option> <option value="30">30</option> <option value="40">40</option> <option value="50">50</option> <option value="60">60</option> <option value="70">70</option> <option value="80">80</option> <option value="90">90</option> <option value="100">100</option></select>  

Output =

<output name="calculation" id="calculation" for="number_one number_two number_three" form="calc">105</output>

</form>

<samp><form id="calc" oninput="calculation.value = parseInt(number_one.value)+parseInt(number_two.value)+parseInt(number_three.value); number_one_output.value = parseInt(number_one.value); number_one_output.style.left = parseInt(number_one.value)-2 + '%';"> <output name="number_one_output" id="number_one_output" for="number_one" form="calc">65</output> <input type="range" name="number_one" id="number_one" value="65"> <input type="number" name="number_two" id="number_two" value="30"> <select name="number_three" id="number_three"> <option value="10">10</option> <option value="20">20</option> <option value="30">30</option> <option value="40">40</option> <option value="50">50</option> <option value="60">60</option> <option value="70">70</option> <option value="80">80</option> <option value="90">90</option> <option value="100">100</option> </select> Output = <output name="calculation" id="calculation" for="number_one number_two number_three" form="calc">105</output> </form></samp>  

### Progress

<samp><progress max="100" value="65""</progress"</samp>

### Meter

<meter min="0" low="5" optimum="0" high="8" max="10" value="7.5" title="GB">7.5 out of 10</meter> <samp><meter min="0" low="5" optimum="0" high="8" max="10" value="7.5" title="GB""7.5 out of 10</meter"</samp></article>

* * *

<article>

## Tables

<table>

<thead>

<tr>

<th></th>

<th>HTML.digital</th>

<th>Bootstrap</th>

<th>Skeleton CSS</th>

<th>Foundation</th>

</tr>

</thead>

<tbody>

<tr>

<td>Responsive Design</td>

<td>✓</td>

<td>✓</td>

<td>✓</td>

<td>✓</td>

</tr>

<tr>

<td>Progressive Enhancement</td>

<td>✓</td>

<td>✕</td>

<td>✕</td>

<td>✕</td>

</tr>

<tr>

<td>No Learning Curve</td>

<td>✓</td>

<td>✕</td>

<td>✕</td>

<td>✕</td>

</tr>

<tr>

<td>Native Darkmode</td>

<td>✓</td>

<td>✕</td>

<td>✕</td>

<td>✕</td>

</tr>

<tr>

<td>Easy Expandability</td>

<td>✓</td>

<td>✓</td>

<td>✓</td>

<td>✓</td>

</tr>

<tr>

<td>Easy Prototyping</td>

<td>✓</td>

<td>✕</td>

<td>✕</td>

<td>✕</td>

</tr>

</tbody>

</table>

<samp><table> <thead> <tr> <th></th> <th>HTML.digital</th> <th>Bootstrap</th> <th>Skeleton CSS</th> <th>Foundation</th> </tr> </thead> <tbody> <tr> <td>Responsive Design</td> <td>✓</td> <td>✓</td> [...]</samp></article>

* * *

<article>

## Aside

### `section > aside`

<section>

<aside>![](../assets/img/test.svg)

### Test card

This is a mega awesome test card

<button>Click me!</button></aside>

</section>

<samp><section> <aside> <img src="path/to/my.svg" height="150px;"> <h3>Test card</h3> <p>This is a mega awesome test card</p> <button>Click me!</button> </aside> </section></samp>  

### `article > aside`

<aside>

This is a mega awesome test card. [Click me!](#0)

</aside>

<samp><article> <aside> <p>This is a mega awesome test card. <a href="#0">Click me!</a></p> </aside> <article></samp></article>

* * *

<article>

## Navigation

</article>

</main>

<header>

<nav>[html.digital](/)

*   [Documentation](/docs/)
*   [GitHub](https://github.com/triss90/html.digital)

</nav>

</header>

<main>

<article><samp><nav> <a href="/"> <img src="path/to/logo.svg"> html.digital </a> <ul> <li> <a href="/docs/">Documentation</a> </li> <li> <a href="https://github.com/triss90/html.digital" target="_blank">GitHub</a> </li> </ul> </nav></samp></article>

* * *

<article>

## Images

All images now has a max width of `100%`

![](../assets/img/placeholder.svg) <samp><img src="path/to/image.svg" alt="My alternate image text"></samp></article>

* * *

<article>

## Colour Scheme

### Variables

You can edit the colour variables in the css file to add your own flair

<samp>/* Base color scheme */ :root { --color-primary: #dd0a35; --color-accent: #118bee0b; --color-bg: #fff; --color-bg-secondary: #e9e9e9; --color-secondary: #1687a7; --color-secondary-accent: #920de90b; --color-shadow: #f4f4f4; --color-text: #334252; --color-text-secondary: #999; }</samp>

### Darkmode

Should you wish to **enable** or alter the darkmode styles, you simply need to uncomment and change the following variables in the css

<samp>/* darkmode */ @media (prefers-color-scheme: dark) { :root { --color-primary: #dd0a35; --color-accent: #118bee0b; --color-bg: #121212; --color-bg-secondary: #000; --color-secondary: #20d0ff; --color-secondary-accent: #920de90b; --color-shadow: #000; --color-text: #f4f4f4; --color-text-secondary: #999; } }</samp></article>

* * *

<footer>

<section>Made by [Tristan White](https://triss.dev)</section>

</footer>

</main>