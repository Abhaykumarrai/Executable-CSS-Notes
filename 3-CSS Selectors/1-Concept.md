CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

We can divide CSS selectors into five categories:

1-Simple selectors (select elements based on name, id, class)
2-Combinator selectors (select elements based on a specific relationship between them)
3-Pseudo-class selectors (select elements based on a certain state)
4-Pseudo-elements selectors (select and style a part of an element)
5-Attribute selectors (select elements based on an attribute or attribute value)

FOR NOW WE ONLY DO SIMPLE SELECTOR REST SELECT WE'LL DO IN LATER CLASSES...

In simple selector we select element through following ways.

1-Element Selector ->> The element selector selects HTML elements based on the element name. 

2-Id Selector ->> The id selector uses the id attribute of an HTML element to select a specific element. 
              ->> To select an element with a specific id, write a hash (#) character, followed by the id of the element.

3-Class Selector ->> The class selector selects HTML elements with a specific class attribute.
                 ->> To select elements with a specific class, write a period (.) character, followed by the class name.


4-group Selector ->> The grouping selector selects all the HTML elements with the same style definitions.
                 ->>


5-Universal Selector ->> The universal selector (*) selects all HTML elements on the page.
• Matches All: Targets and styles all elements on a webpage.
• Syntax: Utilized as an asterisk (*).
• Resets Styles: Commonly used to reset margins and paddings globally.
• Broad Styling: Useful for setting universal attributes like font or color.
• Usage Caution: Can cause style conflicts due to its wide-reaching effects.


------------------------------------------------
Most Important Point Which Makes You Pro In CSS
------------------------------------------------

1-Keep try always use .class selector to style your html document as it avoide confusion and easily understandable by other developer.
2-Avoide to use id selector because we use id attributes in other task suchas in form and javascript which makes confusion.
3-Always Keep in mind about the Specificity of the selectors (inline>Id>Class>Elements)
4-If we define css property inside body and html element aother element of the html page inherit that property.
5-But we can override the for diffrent element
6-form element are not inherit the properties fro parent element , to use property from parent we have to use inherit value.
7-Universal selector does not works on inheritance principal it all about selecting all the elements of webpage.

---------------------------------------------------------------------------------------------------------------------------------------