# omg-console

---

## 使用

```bash
npm install omg-console -save
```

```javascript
import Console from 'omg-console'
const console = new Console('my namespace')
console.log('hello world')
```

## 特性

* 全功能的 console 替代方案，支持所有原生 console 方法
* 常用方法颜色高亮
* 错误会走到 stderr 流
* 支持回溯到源码对应行
* 支持 sourcemap
