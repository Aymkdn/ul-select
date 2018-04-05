# ul-select
Make an unordered list behave like a select element

Original idea from [https://github.com/zgreen/ul-select](https://github.com/zgreen/ul-select), with some changes to enable multiple *ul-select* in the page and trigger a callback when selected.

## Usage

1. You need:
      - [jQuery](https://jquery.com)
      - [ul-select.js](https://github.com/Aymkdn/ul-select/blob/master/ul-select.js)
      - [ul-select.css](https://github.com/Aymkdn/ul-select/blob/master/ul-select.css)
      - [chevron.svg](https://github.com/Aymkdn/ul-select/blob/master/chevron.svg)  
2. Apply `ulSelect()` on the element you want to convert from `ul` to a `select-like`:   
```javascript
$('#my-list').ulSelect(function(selectedLI) {
  console.log("The selected option is: ",selectedLI)
})
```

## Example

See https://aymkdn.github.io/ul-select/ for examples
