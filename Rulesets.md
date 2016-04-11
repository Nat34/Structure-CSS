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
* To apply style to elements that are second, third, etc child of their parents use "nth-child(#)" in the Selecto
