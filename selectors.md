## CSS Selectors

In CSS, selectors are patterns used to select the element(s) you want to style.

Use our [CSS Selector Tester](https://devcom.w3schools.com/cssref/trysel.asp) to demonstrate the different selectors.

| Selector | Example | Example description |
| --- | --- | --- |
| [.*class*](https://devcom.w3schools.com/cssref/sel_class.asp) | .intro | Selects all elements with class="intro" |
| *.class1.class2* | .name1.name2 | Selects all elements with both *name1* and *name2* set within its class attribute |
| *.class1 .class2* | .name1 .name2 | Selects all elements with *name2* that is a descendant of an element with *name1* |
| [#*id*](https://devcom.w3schools.com/cssref/sel_id.asp) | #firstname | Selects the element with id="firstname" |
| [\*](https://devcom.w3schools.com/cssref/sel_all.asp) | \* | Selects all elements |
| *[element](https://devcom.w3schools.com/cssref/sel_element.asp)* | p | Selects all <p> elements |
| *[element.class](https://devcom.w3schools.com/cssref/sel_element_class.asp)* | p.intro | Selects all <p> elements with class="intro" |
| *[element,element](https://devcom.w3schools.com/cssref/sel_element_comma.asp)* | div, p | Selects all <div> elements and all <p> elements |
| [*element* *element*](https://devcom.w3schools.com/cssref/sel_element_element.asp) | div p | Selects all <p> elements inside <div> elements |
| [*element*\>*element*](https://devcom.w3schools.com/cssref/sel_element_gt.asp) | div > p | Selects all <p> elements where the parent is a <div> element |
| [*element*+*element*](https://devcom.w3schools.com/cssref/sel_element_pluss.asp) | div + p | Selects the first <p> element that is placed immediately after <div> elements |
| [*element1*~*element2*](https://devcom.w3schools.com/cssref/sel_gen_sibling.asp) | p ~ ul | Selects every <ul> element that is preceded by a <p> element |
| [\[*attribute*\]](https://devcom.w3schools.com/cssref/sel_attribute.asp) | \[target\] | Selects all elements with a target attribute |
| [\[*attribute*\=*value*\]](https://devcom.w3schools.com/cssref/sel_attribute_value.asp) | \[target=\_blank\] | Selects all elements with target="\_blank" |
| [\[*attribute*~=*value*\]](https://devcom.w3schools.com/cssref/sel_attribute_value_contains.asp) | \[title~=flower\] | Selects all elements with a title attribute containing the word "flower" |
| [\[*attribute*|=*value*\]](https://devcom.w3schools.com/cssref/sel_attribute_value_lang.asp) | \[lang|=en\] | Selects all elements with a lang attribute value equal to "en" or starting with "en-" |
| [\[*attribute*^=*value*\]](https://devcom.w3schools.com/cssref/sel_attr_begin.asp) | a\[href^="https"\] | Selects every <a> element whose href attribute value begins with "https" |
| [\[*attribute*$=*value*\]](https://devcom.w3schools.com/cssref/sel_attr_end.asp) | a\[href$=".pdf"\] | Selects every <a> element whose href attribute value ends with ".pdf" |
| [\[*attribute*\*=*value*\]](https://devcom.w3schools.com/cssref/sel_attr_contain.asp) | a\[href\*="w3schools"\] | Selects every <a> element whose href attribute value contains the substring "w3schools" |
| [:active](https://devcom.w3schools.com/cssref/sel_active.asp) | a:active | Selects the active link |
| [::after](https://devcom.w3schools.com/cssref/sel_after.asp) | p::after | Insert something after the content of each <p> element |
| [::before](https://devcom.w3schools.com/cssref/sel_before.asp) | p::before | Insert something before the content of each <p> element |
| [:checked](https://devcom.w3schools.com/cssref/sel_checked.asp) | input:checked | Selects every checked <input> element |
| [:default](https://devcom.w3schools.com/cssref/sel_default.asp) | input:default | Selects the default <input> element |
| [:disabled](https://devcom.w3schools.com/cssref/sel_disabled.asp) | input:disabled | Selects every disabled <input> element |
| [:empty](https://devcom.w3schools.com/cssref/sel_empty.asp) | p:empty | Selects every <p> element that has no children (including text nodes) |
| [:enabled](https://devcom.w3schools.com/cssref/sel_enabled.asp) | input:enabled | Selects every enabled <input> element |
| [:first-child](https://devcom.w3schools.com/cssref/sel_firstchild.asp) | p:first-child | Selects every <p> element that is the first child of its parent |
| [::first-letter](https://devcom.w3schools.com/cssref/sel_firstletter.asp) | p::first-letter | Selects the first letter of every <p> element |
| [::first-line](https://devcom.w3schools.com/cssref/sel_firstline.asp) | p::first-line | Selects the first line of every <p> element |
| [:first-of-type](https://devcom.w3schools.com/cssref/sel_first-of-type.asp) | p:first-of-type | Selects every <p> element that is the first <p> element of its parent |
| [:focus](https://devcom.w3schools.com/cssref/sel_focus.asp) | input:focus | Selects the input element which has focus |
| [:fullscreen](https://devcom.w3schools.com/cssref/sel_fullscreen.asp) | :fullscreen | Selects the element that is in full-screen mode |
| [:hover](https://devcom.w3schools.com/cssref/sel_hover.asp) | a:hover | Selects links on mouse over |
| [:in-range](https://devcom.w3schools.com/cssref/sel_in-range.asp) | input:in-range | Selects input elements with a value within a specified range |
| [:indeterminate](https://devcom.w3schools.com/cssref/sel_indeterminate.asp) | input:indeterminate | Selects input elements that are in an indeterminate state |
| [:invalid](https://devcom.w3schools.com/cssref/sel_invalid.asp) | input:invalid | Selects all input elements with an invalid value |
| [:lang(*language*)](https://devcom.w3schools.com/cssref/sel_lang.asp) | p:lang(it) | Selects every <p> element with a lang attribute equal to "it" (Italian) |
| [:last-child](https://devcom.w3schools.com/cssref/sel_last-child.asp) | p:last-child | Selects every <p> element that is the last child of its parent |
| [:last-of-type](https://devcom.w3schools.com/cssref/sel_last-of-type.asp) | p:last-of-type | Selects every <p> element that is the last <p> element of its parent |
| [:link](https://devcom.w3schools.com/cssref/sel_link.asp) | a:link | Selects all unvisited links |
| [::marker](https://devcom.w3schools.com/cssref/sel_marker.asp) | ::marker | Selects the markers of list items |
| [:not(*selector*)](https://devcom.w3schools.com/cssref/sel_not.asp) | :not(p) | Selects every element that is not a <p> element |
| [:nth-child(*n*)](https://devcom.w3schools.com/cssref/sel_nth-child.asp) | p:nth-child(2) | Selects every <p> element that is the second child of its parent |
| [:nth-last-child(*n*)](https://devcom.w3schools.com/cssref/sel_nth-last-child.asp) | p:nth-last-child(2) | Selects every <p> element that is the second child of its parent, counting from the last child |
| [:nth-last-of-type(*n*)](https://devcom.w3schools.com/cssref/sel_nth-last-of-type.asp) | p:nth-last-of-type(2) | Selects every <p> element that is the second <p> element of its parent, counting from the last child |
| [:nth-of-type(*n*)](https://devcom.w3schools.com/cssref/sel_nth-of-type.asp) | p:nth-of-type(2) | Selects every <p> element that is the second <p> element of its parent |
| [:only-of-type](https://devcom.w3schools.com/cssref/sel_only-of-type.asp) | p:only-of-type | Selects every <p> element that is the only <p> element of its parent |
| [:only-child](https://devcom.w3schools.com/cssref/sel_only-child.asp) | p:only-child | Selects every <p> element that is the only child of its parent |
| [:optional](https://devcom.w3schools.com/cssref/sel_optional.asp) | input:optional | Selects input elements with no "required" attribute |
| [:out-of-range](https://devcom.w3schools.com/cssref/sel_out-of-range.asp) | input:out-of-range | Selects input elements with a value outside a specified range |
| [::placeholder](https://devcom.w3schools.com/cssref/sel_placeholder.asp) | input::placeholder | Selects input elements with the "placeholder" attribute specified |
| [:read-only](https://devcom.w3schools.com/cssref/sel_read-only.asp) | input:read-only | Selects input elements with the "readonly" attribute specified |
| [:read-write](https://devcom.w3schools.com/cssref/sel_read-write.asp) | input:read-write | Selects input elements with the "readonly" attribute NOT specified |
| [:required](https://devcom.w3schools.com/cssref/sel_required.asp) | input:required | Selects input elements with the "required" attribute specified |
| [:root](https://devcom.w3schools.com/cssref/sel_root.asp) | :root | Selects the document's root element |
| [::selection](https://devcom.w3schools.com/cssref/sel_selection.asp) | ::selection | Selects the portion of an element that is selected by a user |
| [:target](https://devcom.w3schools.com/cssref/sel_target.asp) | #news:target | Selects the current active #news element (clicked on a URL containing that anchor name) |
| [:valid](https://devcom.w3schools.com/cssref/sel_valid.asp) | input:valid | Selects all input elements with a valid value |
| [:visited](https://devcom.w3schools.com/cssref/sel_visited.asp) | a:visited | Selects all visited links |

[❮ Previous](https://devcom.w3schools.com/cssref/css3_browsersupport.asp) [Next ❯](https://devcom.w3schools.com/cssref/css_functions.asp)
