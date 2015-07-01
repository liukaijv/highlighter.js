###Default

if no next elements to select restart selecting the first element in the dom

if no prev elements to select restart selecting the first element in the dom

###Select next element
_Select next element starting from the current selected element (by default is the first DOM element)_
```
window.Selez.selectNext()
```

###Select prev element
_Select previous element starting from the current selected element ( by default is the first DOM element)_
```
window.Selez.selectPrev()
```

###Highlight selected element
_Scroll to and highlight current selected element in view_
```
window.Selez.highlight();
```

###De-highlight selected element
_De-highlight current selected element in view_
```
window.Selez.dehighlight();
```

###Select Next by ID
_Select next element (by ID) starting from the current selected element (by default is the first DOM element)_
```
window.selectNext('#test');
```

###Select Next by class/es
_Select next element (by class/classes) starting from the current selected element (by default is the first DOM element)_
```
window.selectNext('.class .class-2');
```

###Select Prev by ID
_Select previous element (by ID) starting from the current selected element (by default is the first DOM element)_
```
window.selectPrev('#test');
```

###Select Prev by class/es
_Select previous element (by class/classes) starting from the current selected element (by default is the first DOM element)_
```
window.selectPrev('.class .class-2');
```

###TO-DO

1 - events on selection and errors

2 - select by tag name (next and prev)

3 - option to specify if to select or not invisible/hidden elements

4 - linter, bower, npm and tasks
