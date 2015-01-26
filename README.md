## Drag-Select Link Text 
Firefox browser extension.

![](/icon64.png)

**Select link text with easy drag gestures.**

Selecting link text can be difficult, requiring careful cursor placement on the outside edges of the link or holding the alt key. The latter is cumbersome and can cause unwanted actions. Releasing the alt key too early results in the link being clicked and often the menu bar is toggled as it shares the same key-mapping. Drag gestures offer a better balance of functionality, making text selection easier while still allowing link dragging.

Three different types of selection gestures are available:

* **Horizontal** - Select text by leaving the drag threshold horizontally. Similar to Opera 12.
* **Hold** - Select text by holding and waiting for the hold time to elapse before leaving the drag threshold.
* **Immediate** - Select text by immediately leaving the drag threshold before the hold time elapses.


If selection is not initiated when leaving the drag threshold then the link will be dragged instead.

The size of the drag threshold in each direction and the length of the hold time are adjustable. In the case of the horizontal drag gesture, making the thresholds asymmetric can make one action easier to perform than the other. For the other gestures, when the hold time elapses the cursor icon changes to indicate the action to be performed when the threshold is exceeded.

Holding a modifier key (eg ctrl, shift) always initiates selection when leaving the drag threshold.

Selection is initiated using simulated mouse events at the browser level for maximum compatibility.

Official Firefox support tracked by [Bug 378775](https://bugzilla.mozilla.org/show_bug.cgi?id=378775).