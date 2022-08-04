# tk_helper
Helper functions for TTK Widgets

**CtreeView** - Supports even/odd row colors, and easier item setting  
**CLabel** -  standardized get and set text  
**CEntry** -  standardized get and set text.  Support for Undo/Redo   
**ProgressBar** - Progress Bar wrapper - easier color selection and updating  
**Buttons** - routines to enable/disable list of buttons and set a button as 'preferred'  
**Exit** - Helper routine to display message and exit  

_Set/Get Text Example:_

    label = CLabel(parent, **kwargs)
    label.text = 'hello'
    text = label.text
    
    entry = CEntry(parent, *args, **kwargs)
    entry.text = 'hello'
    text = entry.text
