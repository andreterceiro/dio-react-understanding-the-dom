# General

Example of DOM hierarchy, with some elements:

![example of DOM hierarchy](images/example-of-DOM-hierarchy.png)

We have the method `getElementsByTagName()` of the document or of an element and returns an array of matches. Example:

```
document.getElementsByTagName("td"); // The return depends on the rendered web page
```

Another cool method is `document.querySelector()`. It returns the first element that matches the specified selectors. `document.querySelectorAll()` returns an array with the matches.

Examples:

```
document.querySelector("#root")
document.querySelectorAll(".details")
```