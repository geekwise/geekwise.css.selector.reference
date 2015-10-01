
<div align='center'>
<img src='images/geekwise_logo_owl_bw_small.png' alt='geekwise'>
<img src='images/geekwise_logo_txt_bw_small.png' alt='geekwise'>
</div>
--
<h1 align='center' style='
background-color:#dbdbdb;'>
CSS Selector Reference Dictionary
</h1>
***

MARKUP	        | Description
--------------- | ---------------
`.red_backround` 			|	Selects all elements with a class `<div class="red_backround"></div>` A `Class` can be used more than once in an `HTML` document.
`#photo_01` 				|	Selects the element with `<div id="photo_01"></div>` An `ID` can be used only once in an `HTML` document.
`*` 								|	Selects all `HTML` elements
`p` 								|	Selects all `<p>` elements
`element,element` |	Selects all `<div>` elements and all `<p>` elements
`element element` |	Selects all `<p>` elements inside `<div>` elements
`element > element` |	Selects all `<p>` elements where the parent is a `<div>` element
`element + element` |	Selects all `<p>` elements that are placed immediately after `<div>` elements
`element1 ~ element2` |	Selects every `<ul>` element that are preceded by a `<p>` element
`[attribute]` |	Selects all elements with a target attribute
`[attribute=value]` |	Selects all elements with target="_blank"
`[attribute~=value]` |	Selects all elements with a title attribute containing the word "flower"
`[attribute|=value]` |	Selects all elements with a lang attribute value starting with "en"
`[attribute^=value]` |	Selects every `<a>` element whose href attribute value begins with "https"
`[attribute$=value]` |	Selects every `<a>` element whose href attribute value ends with ".pdf"
`[attribute*=value]` |	Selects every `<a>` element whose href attribute value contains the substring "w3schools"
`:active` |	Selects the active link
`::after` |	Insert something after the content of each `<p>` element
`::before` |	Insert something before the content of each `<p>` element
`:checked` |	Selects every checked `<input>` element
`:disabled` |	Selects every disabled `<input>` element
`:empty` |	Selects every `<p>` element that has no children (including text nodes)
`:enabled` |	Selects every enabled `<input>` element
`:first-child` |	Selects every `<p>` element that is the first child of its parent
`::first-letter` |	Selects the first letter of every `<p>` element
`::first-line` |	Selects the first line of every `<p>` element
`:first-of-type` |	Selects every `<p>` element that is the first `<p>` element of its parent
`:focus` |	Selects the input element which has focus
`:hover` |	Selects links on mouse over
`:in-range` |	Selects input elements with a value within a specified range
`:invalid` |	Selects all input elements with an invalid value
`:lang(language)` |	Selects every `<p>` element with a lang attribute equal to "it" (Italian)
`:last-child` |	Selects every `<p>` element that is the last child of its parent
`:last-of-type` |	Selects every `<p>` element that is the last `<p>` element of its parent
`:link` |	Selects all unvisited links
`:not(selector)` |	Selects every element that is not a `<p>` element
`:nth-child(2)` |	Selects every `<p>` element that is the second child of its parent
`:nth-last-child(n)` |	Selects every `<p>` element that is the second child of its parent, counting from the last child
`:nth-last-of-type(2)` |	Selects every `<p>` element that is the second `<p>` element of its parent, counting from the last child
`:nth-of-type(2)` |	Selects every `<p>` element that is the second `<p>` element of its parent
`:only-of-type` |	Selects every `<p>` element that is the only `<p>` element of its parent
`:only-child` |	Selects every `<p>` element that is the only child of its parent
`:optional` |	Selects input elements with no "required" attribute
`:out-of-range` |	Selects input elements with a value outside a specified range
`:read-only` |	Selects input elements with the "readonly" attribute specified
`:read-write` |	Selects input elements with the "readonly" attribute NOT specified
`:required` |	Selects input elements with the "required" attribute specified
`:root` |	Selects the document's root element
`::selection` |	Selects the portion of an element that is selected.
`:target` |	Selects the current active #about element (clicked on a URL containing that anchor name) `<a href="#about">about</a> <div id="about">The About Section</div>`
``:valid` |	Selects all input elements with a valid value
`:visited` |	Selects all visited links
