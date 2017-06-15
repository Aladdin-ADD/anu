##注意点

### 目前没有支持的方法与对象

1. PropTypes
2. childContextTypes(不需要定义它，就能使用context)
3. mixin机制
4. createClass
5. createFactory

### 低版本浏览器可能需要以下 语言补丁, 详见IE栏目的处理

1. [Array.isArray](https://github.com/juliangruber/isarray/)
2. [Object.assign](https://github.com/ryanhefner/Object.assign)
3. [JSON.stringify](https://github.com/flowersinthesand/stringifyJSON)
4. [console-polyfill](https://github.com/paulmillr/console-polyfill) 
5. [Object.keys](https://github.com/ljharb/object-keys)
6. [Object.is](https://github.com/ljharb/object-is)
7. [Array.prototype.forEach](polyfill/Array.prototype.forEach)
8. [Function.prototype.bind](https://github.com/leahciMic/polyfill-function-prototype-bind)

或者直接使用**polyfill.js** https://github.com/RubyLouvre/anu/tree/master/dist/polyfill.js