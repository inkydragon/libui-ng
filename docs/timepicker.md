
# TimePicker

> A widgets to edit times.

```js

var libui = require('libui');

libui.Ui.init();
var win = new libui.UiWindow('UiTimePicker example', 320, 60, true);
win.margined = true;

var widget = new libui.UiTimePicker();
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

> new libui.UiTimePicker()

Create a new UiTimePicker object.

