DragMe
======

Drag me is a cross-browser ultra lightweight plugin to make "elements" draggable

Other alternatives like jQuery require jQuery and jQuery.UI (or jQuery.UI.widget + jQuery.UI.Draggable + jQuery.UI.mouse)

Dependencies
========

No dependencies

Usage
========

Default usage:

<pre>
  HFDragMe.setup("draggable", "handle");
</pre>

or 

<pre>
  HFDragMe.setup(document.getElementById("draggable"), document.getElementById("handle"));
</pre>


Change the default options:

<pre>
  HFDragMe.setup("draggable", "handle", { cursor: "pointer"});
</pre>

Options
=======

Various options may be passed along to DragMe:

<pre>
HFDragMe.setup(..., ..., {
    // options
    option1: 'value',
    option2: 'value',
    option3: 'value'
    // etc...
});
</pre>

List of options and description:

<pre>
    cursor
</pre>
The cursor to apply on the handle.

<pre>
    changeZIndex
</pre>
Whether to change or not the original "draggable" element zIndex.

<pre>
    zIndex
</pre>
If changeZIndex is true, then apply this zIndex.

<pre>
    opacity
</pre>
The opacity to apply to the "draggable" element when dragging.
        
License
========

DragMe is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
