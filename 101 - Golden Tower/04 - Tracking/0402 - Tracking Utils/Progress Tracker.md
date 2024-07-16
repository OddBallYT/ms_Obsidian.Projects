```dataviewjs
dv.span("**Progress Log**")

const pages = dv.pages('#daily_note and -"00 - Content"').sort(p => p.file.name)
const dates = pages.map(p => p.file.name)
const words = pages.map(p => p.words_written).values
const hours_worked = pages.map(p => p.hours_worked).values

const chartData = {
	type: 'line',
	data: {
		labels: dates,
		datasets: [{
			label: 'Words',
			data: words,
			backgroundColor: [
				'rgba(53, 252, 167, 1)'
			],
			borderColor: [
				'rgba(138, 102, 204, 0.8)'
			],
			borderWidth: 1.5,
			spanGaps: true,
		},
		{
			label: 'Hours Worked',
			data: hours_worked,
			backgroundColor: [
				'rgba(252, 167, 53, 1)'
			],
			borderColor: [
				'rgba(102, 204, 138, 0.8)'
			],
			borderWidth: 1.5,
			spanGaps: true,
		}
		],
	},
};

window.renderChart(chartData, this.container)
```

### Description
The above chart is to track daily writing progress against the number of hours worked that day. Intended to keep track of what days are the most productive, and which days lack. As well as being a guide to density of productivity, rather than just volume of work done.