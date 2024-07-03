This is a fork of https://github.com/Bernardo-Castilho/dragdroptouch with
some fixes to make it easier to work with, some minor code cleanup, and
a build process that compiles the code as ESM that can be imported using:

```js
import { setupDragDropTouch } from "somewhere/drag-drop-touch.esm.js";
setupDragDropTouch(...)
```

using the same arguments that the original `DragDropTouch` class takes.

However, it also supports a dedicated autoload:

```html
<script src="somewhere/drag-drop-touch.esm.js?autoload" type="module"></script>
```

This will load the module and immediately activate it due to the `?autoload` argument.

The updated demo URL is https://pomax.github.io/dragdroptouch/demo/index.html
