# vue-print-nb

This is a directive wrapper for printed, Simple, fast, convenient, light.
这个项目是从vue-print-nb复制下来的一个项目，只是修改了里面关于checkebox和radio的checked属性添加

## Install

#### NPM
```bash
npm install vue-print-yangyang --save
```

```javascript
import Print from 'vue-print-yangyang'

Vue.use(Print);
```


## Description

#### Print the entire page:

```
<button v-print>Print the entire page</button>
```


#### Print local range:

HTML:
```
    <div id="printMe" style="background:red;">
        <p>葫芦娃，葫芦娃</p>
        <p>一根藤上七朵花 </p>
        <p>小小树藤是我家 啦啦啦啦 </p>
        <p>叮当当咚咚当当　浇不大</p>
        <p> 叮当当咚咚当当 是我家</p>
        <p> 啦啦啦啦</p>
        <p>...</p>
    </div>

    <button v-print="'#printMe'">Print local range</button>
```


## License

[MIT](http://opensource.org/licenses/MIT)