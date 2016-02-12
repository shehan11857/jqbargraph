data: arrayOfData // array of data for your graph

title: false // title of your graph, accept HTML

barSpace: 10 // this is default space between bars in pixels

width: 400 // default width of your graph

height: 200 //default height of your graph

color: '#000000' // if you don't send colors for your data this will be default bars color

colors: false // array of colors that will be used for your bars and legends

lbl: '' // if there is no label in your array

sort: false // sort your data before displaying graph, you can sort as 'asc' or 'desc'

position: 'bottom' // position of your bars, can be 'bottom' or 'top'. 'top' doesn't work for multi type

prefix: '' // text that will be shown before every label

postfix: '' // text that will be shown after every label

animate: true // if you don't need animated appereance change to false

speed: 2 // speed of animation in seconds

legendWidth: 100 // width of your legend box

legend: false // if you want legend change to true

legends: false // array for legend. for simple graph type legend will be extracted from labels if you don't set this

type: false // for multi array data default graph type is stacked, you can change to 'multi' for multi bar type

showValues: true // you can use this for multi and stacked type and it will show values of every bar part

showValuesColor: '#fff' // color of font for values



example:
> $('#divForGraph').jqBarGraph({ data: arrayOfData });