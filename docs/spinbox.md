
# Spinbox

> An entry widget for numerical values.

```js

var libui = require('libui');

libui.Ui.init();
var win = new libui.UiWindow('UiSpinbox example', 320, 60, true);
win.margined = true;

var widget = new libui.UiSpinbox();
widget.text = 'sample text';
win.setChild(widget);

win.onClosing(function () {
	win.close();
	libui.Ui.quit();
});

win.show();

libui.Ui.main();


```

---

# Constructor

> new libui.UiSpinbox()

Create a new UiSpinbox object.

