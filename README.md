# YMA Classnames

将多种数据类型的 classname 进行合并，并转为字符串

## 安装

```sh
npm install yma-classnames
```

## 使用

```js
import classnames from 'yma-classnames';

const clazzname = classnames('a', ['x', 'y'], {
    z: true,
});
```
