## DOM节点

### 创建插入和删除元素

- 创建DOM元素

  - createElement(标签名)		创建一个节点

    - appendChild(节点)		追加一个节点//告诉它插在哪里

    父.appendChild(子节点)

- 插入元素

  - insertBefore(节点, 原有节点)	在已有元素前插入

  - 例子：倒序插入li

    oUl.insertBefore(oLi, aLi[0]);


- 删除DOM元素
  - removeChild(节点)删除一个节点
  - 例子：删除li

### 第一个li和最后一个li

- 首尾子节点
  - 有兼容性问题
  - firstChild、firstElementChild 
  - lastChild 、lastElementChild


- removeChild(aLi[aLi.length-1])
- removeChild(aLi[0])

### 验证输入的值为数字

```
if(!isNaN(oTxt.value)){
}
else{
};
```

### confirm确认

if(confirm(...)){

...}

### CSS样式

- 渐变

- 阴影

- 属性选择器

  ​

