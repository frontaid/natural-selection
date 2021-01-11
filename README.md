# Natural Selection

Natural Selection is a CSS framework without any styling at all.
It is just a collection of *selectors* that can be used to define *global* styles.
Natural Selection aims to provide a best-practice **CSS boilerplate** that can be used to start projects.
It tries to encourage semantic HTML and the handling of accessibility concerns.

Natural Selection almost exclusively uses generic element, attribute, and pseudo-class selectors.
But there are also very few *opinionated* selectors that rely on classes.
See the comments in the CSS file for more information.
The selector grouping is loosely based on MDN's
[HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).
Ordering is roughly based on how common certain elements or element groups are.


## Instructions

1. Download the [raw CSS](https://raw.githubusercontent.com/frontaid/natural-selection/main/boilerplate.css)
1. Move it into your code base
1. Evolve it according to your needs


## Browser Compatibility

All modern browsers and almost all browsers still in use today should be more than capable of handling Natural Selection.

Natural Selection is mostly based on element, attribute, and pseudo-class selectors.
All of them have been in the CSS specifications for ages.
Though, there are some selectors that might not yet be widely supported.
In that case, Natural Selection provides ways to detect and/or overcome lacking browser support.


## Contribute

Please create an issue when you have a suggestion.
Note that the goal of this project is to provide a useful and minimal boilerplate for global CSS styling.
It is *not* the goal to add every single element or every possible element/attribute/pseudo-class combination.


## Questions and Answers

**Why is this called "Natural Selection"?**  
This is a collection of CSS *selectors*.
And given the limited number of HTML elements and attributes, the list came about quite *naturally*.

**Why are there no selectors for `div` and `span`?**  
Both `div` and `span` are very generic. It does not really make sense to apply any *global* styling
to them. If it does make sense in your specific use case, just add them yourself.

**What is element `X` used for?**  
Please read MDN's
[HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

**What element(s) are matched by the selector `X`?**  
Please read MDN's
[CSS selectors reference](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors).
