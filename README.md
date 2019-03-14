# whack
Improve the germane cognitive load of using Webflow designer by re-styling the Style panel UI.

The 2019 version of the Style panel in Webflow designer is decreasing the contrast of the UI. It's also polishing it
to the point a lot of functions look the same, which is increasing the germane cognitive load.

To help your brain use less power when working with the Style panel, this re-styling code will make unecessary labels
disappear, enlarge some items, give some items some colors to differenciate them, and reinstate a better constrast on
some parts of the UI.

There is also a set of styles to improve the workflow of importing large CSVs into CMS collections with a lot of fields,
increasing the height of the fields dropdown menus in order not to have to scroll inside of them, making the switches
red in order to never miss one (because the binding of Yes and No on the switches fields is erractic and unperdictable)
and adds a significant padding on the bottom of the UI to cope with the taller dropdown menu. You shouldn't use those
styles by default, althought they break nothing.
