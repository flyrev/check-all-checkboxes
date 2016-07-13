# check-all-checkboxes

Use this to check all checkboxes on pages that do not provide this functionality.

```javascript
var inputs = document.getElementsByTagName('input');

for (var i=0; i < inputs.length; i++) {
    if (inputs[i].type === 'checkbox') {
	inputs[i].checked = true;
    }
}
```
