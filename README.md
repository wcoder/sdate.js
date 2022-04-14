# sdate.js
Controls for selection date.

![Example](https://raw.githubusercontent.com/wcoder/sdate.js/master/sdate.png)

[Demo](https://wcoder.github.io/life-calendar/)

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

## Who uses?

- [Life-Calendar](https://github.com/wcoder/life-calendar)


---
&copy; 2016 Yauheni Pakala | MIT

