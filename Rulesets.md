# Rulesets

* A CSS file is a collection of rulesets
* A ruleset is a collection of style rules applied to some subset of elements in the DOM
* A ruleset consists of a selector; "body", an opening curly brace, a list of rules and closing curly brace
* Each rule consists of a specific property; "color", followed by a colon, followed by a value or list of values,
followed by a semicolon
* we can add a class to ANY DOM element

`p {
	color: gray;
	border: 1px solid gray;
	padding: 10px;
}`

**CSS Ruleset Workflow:**

1. Determine HTML element to which you want to apply the style
2. Create a Ruleset
	1. Create Selector
	2. Create Rule or Rules 
		* Determine types of properties that can be set for a particular element
		* Determine types of values that each property accepts

**Complex Selectors**
* To apply style to only ordered list items the Selector must be specific
* To appy style to list items (or li elements) that are descendants of div class, 
use the class name in the Selector
* To apply style to elements that are first child of their parents use "first-child" in the Selector
* To apply style to elements that are second, third, etc child of their parents use "nth-child(#)" in the Selector

**Cascading Rules**
* Set of rules browsers apply amid conflicting rules
* Specific Selectors take precedence
* The ruleset that appears later in the CSS list will be applied

**Inheritance**
* Descendants inherit properties of their ancestors
* Maintain a visualization of the DOM hierarchy is essential
* Not all properties are inherited by default
* Non-inherited: some Block-style elements

**Web Fonts**
* Add `<link>` tag to the head of your HTML
* `<link href='https://fonts.googleapis.com/css?family=Denk+One' rel='stylesheet' type='text/css'>`
* To style an element with the font add a font-family property to the ruleset
* `font-family: Denk One, sans-serif;` The first property specifies the font, the second defaults if first is not available.
* Set a base font size
* Use absolute size values: xx-large, x-large, x-small, xx-small (Relative to current context)
* Use em unit to specify length (i.e. scale all font sizes relative to base font size, more specific)

*Summary*
* add style to the structure of the user interface and content
* attach stylistic *rulesets* to elements in the DOM
* restrict CSS rulesets to a subset of DOM elements using CSS *Selectors*
* set up basic document layouts on a grid using CSS float properies
* ensure proper alignment and spacing of content using padding and margins


