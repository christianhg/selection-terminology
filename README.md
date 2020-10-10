# Selection Terminology

When working with and talking about text selections the terminologies are, unfortunately, often used interchangeably. An imprecise language leads to imprecise specifications which in turn leads to imprecise implementations. This document aims to help clear up the terms.

## Essential Terms

To begin with, the essential terms are:

* **Selection**: the highlighted identification of a range of content.
* **Start**: The beginning of a given selection.
* **End**: The end of a given selection.
* **Anchor**: The place where a selection originated.
* **Focus**: The place where selection ended.
* **Caret**: The insertion point inside a text editor.

## Selection

> a list of items on which user operations will take place

## Anchor/Focus Vs. Start/End

At first glance, anchor/focus might just look like a slightly more fancy way of talking about start/end. However, these two sets of terms are not to be confused. Depending on the direction of the selection, the anchor may be situated at the start or at the end of a selection (with the focus on the opposite end).

```
   ∨
1A 1B 1C 1D
2A 2B 2C 2D
3A 3B 3C 3D
       ∧
```

Misc. characters:

←
↑
→
↓

References:

* https://en.wikipedia.org/wiki/Selection_(user_interface)
* https://developer.mozilla.org/en-US/docs/Glossary/caret
* https://en.wikipedia.org/wiki/Cursor_(user_interface)
* https://www.w3.org/WAI/UA/UAAG10/glossary.html#def-selection
* https://developer.mozilla.org/en-US/docs/Web/API/Selection
