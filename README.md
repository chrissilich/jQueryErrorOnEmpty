jQueryErrorOnEmpty
==================

jQuery doesn't tell you if your selection came up empty. Sometimes you need that.

To use:
```javascript
$("#myDiv").emptyError().fadeIn();
```

If there's no #myDiv in your document, you get an error.

On the other hand if you just want a warning in your console:
```javascript
$("#myDiv").emptyWarn().fadeIn();
```
