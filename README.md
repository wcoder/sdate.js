# sdate.js
Controls for selection date.

## Usage

Add HTML:
```html
<div>
	<select id="sdate-day"></select>
	<select id="sdate-month"></select>
	<select id="sdate-year"></select>
</div>
```

```html
<script src="src/sdate.js"></script>
```

Init:
```js
var picker = selectionDate(/* onChagen callback */, /* array of month names */);
```

Set date:
```js
var date = new Date();

picker.setDate(date);
```


---
&copy; 2016 Yauheni Pakala | MIT

