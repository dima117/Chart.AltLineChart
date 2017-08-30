# Chart.Scatter

*Scatter chart plugin for Chart.js* [chartjs.org](http://www.chartjs.org)

[Documentation & live demo](http://dima117.github.io/Chart.Scatter/)


## Changes in this fork

This fork has option to set line (stroke) width as zero to disable them per dataset.
E.g.

```javascript
var datasets = [
	{
		label: "dataset 1",
		strokeWidth: 5,
		data: data
	},
	{
		label: "dataset 2",
		strokeWidth: 0, // here we have zero width and only points are drawn
		data: data2 }
];
```

## License

Chart.Scatter.js is available under the [MIT license](http://opensource.org/licenses/MIT).

## Bugs & issues

When reporting bugs or issues, if you could include a link to a simple [jsbin](http://jsbin.com) or similar demonstrating the issue, that'd be really helpful.
