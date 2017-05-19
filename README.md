# talk-cross-origin
An app using HTML5 posMessage API for cross origin communication.


**NOTE** 

* If we are opening iframe in parent, then we can call postMessage on parent using `parent` but if we are opening a new tab/window then reference to orginal parent can only be got by `event.source` where event is object recievedd in `message` event handler of child window/tab.