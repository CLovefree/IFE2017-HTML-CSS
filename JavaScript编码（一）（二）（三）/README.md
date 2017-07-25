function getDate(){...};----------------提取数组函数

- push到空数组var data[]里
- 提取方法可以用slice
- 返回data

function sortAqiData(data){...};--------排序函数

- sort减法升序
- 返回data

function render(data){...};--------------表达函数

- rank大写数组
- for循环为数组的每一组值建立一个新<li></li>
- 新ul的innerHTML就等于新li

function btnHandle(){...};---------------最终触发时函数

- 声明新变量aqiData
- 三个函数

```javascript
function btnHandle(){
	var aqiData = getData();
	aqiData = sortAqiData(aqiData);
	render(aqiData);
};
```

点击事件触发btnHandl函数

