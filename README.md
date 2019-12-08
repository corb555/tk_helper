# tk_helper
Helper functions for TTK Widgets

**CtreeView** - Support even/odd row colors, and easier item setting  
**CLabel** -  standardized get and set text  
**CEntry** -  standardized get and set text.  Support for Undo/Redo in Entry widget  
**ProgressBar** - Progress Bar wrapper - easier color selection and updating  
**Buttons** - routines to enable/disable list of buttons and set a button as 'preferred'  
**Exit routines** - Helper routines to display message and exit  

_Example:_

    label = CLabel(parent, **kwargs)
    label.text = 'hello'
    text = label.text