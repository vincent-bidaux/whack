# whack

Experiment styling for the 2019 Style panel UI of the Webflow Designer app.

Makes some labels disappear, enlarge some items, give some items some colors to differenciate them, increase the contrast on some UI items. Text labels are styled in San Francisco, with a heavier weight and an alignment to their respective field.

—

Usage

Copy the CSS code from the whack.css into any code injection browser extension such as Stylebot for Chrome.

—

Warning

This code overrides the original code of Webflow's UI. It can easily break it due to changes on Webflow's side, other extensions running in your browser, and a lot of other reasons. At a certainty, it will break the UI one day.

This code is a demo of how you can change an online software's UI with CSS code injection. Use it as a demo rather than as a tool for production.

To fully understand the code, you need to understand how to target an element with the custom attributes selectors, as well as with the nth-child selector.

For example:

div[CustomAttributeName=CustomAttributeValue] div:nth-child(2) div:nth-child(6) { background-color: red }

is giving a red background color to the 6th child div of the 2nd child div of the div whose custom attribute is CustomAttributeName with the value CustomAttributeValue.
    
_

Extra

There is also a set of styles to secure the workflow of importing large CSVs into CMS collections with a lot of fields. It reduces the number of clicks and drags, potentially reducing the possibility of making errors when binding or creating fields, and when setting the values for switch fields (because the binding of Yes and No on the switches fields is not predictable).

Increases the height of the fields dropdown menus in order not to have to scroll inside of them, making the switches red in order to never miss one
Adds a significant padding on the bottom of the UI to cope with the taller dropdown menu.
Those styles are commented out. You shouldn't use those styles by default, althought they break nothing.
