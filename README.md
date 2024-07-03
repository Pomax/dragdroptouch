This is a fork of https://github.com/Bernardo-Castilho/dragdroptouch with
some fixes to make it easier to work with, some minor code cleanup, and
a build process that compiles the code as ESM that can be imported using:

```js
import { setupDragDropTouch } from "somewhere/drag-drop-touch.esm.js";
setupDragDropTouch(...)
```

using the same arguments that the original `DragDropTouch` class takes, or:

```js
import "somewhere/drag-drop-touch.esm.js?autoload";
```

With the `autoload` argument ensuring that things "just work(tm)".

The updated demo URL is https://pomax.github.io/dragdroptouch/demo/index.html
