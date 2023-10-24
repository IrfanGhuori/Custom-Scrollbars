# Custom-Scrollbars
Chrome, Edge, Safari, and Opera support the non-standard::-webkit-scrollbar pseudo-element, which allows us to modify the look of the browser's scrollbar.

![alt text](https://i.ibb.co/NxDkhtm/css-tricks.png)

# The Different Pieces
These are the pseudo-elements themselves. The actual parts of the scrollbars.

```sh
::-webkit-scrollbar              { /* 1 */ }
::-webkit-scrollbar-button       { /* 2 */ }
::-webkit-scrollbar-track        { /* 3 */ }
::-webkit-scrollbar-track-piece  { /* 4 */ }
::-webkit-scrollbar-thumb        { /* 5 */ }
::-webkit-scrollbar-corner       { /* 6 */ }
::-webkit-resizer                { /* 7 */ }
```


