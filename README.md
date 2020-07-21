# 使用说明

#### 如何集成？

```shell
yarn add jb
```



#### 开启无坚不摧模式：

```javascript
import JB from 'jb';

const wujian = JB['无坚不摧模式']['无坚'];
const buchui = JB['无坚不摧模式']['不摧'];

function App() {
	const [ name, setName ] = wujian.useState('jb')
	return <div onClick={() => setName('djb')}>{name}</div>
}

buchui.render(document.getElementById('root'), )
```

- 续航模式
- 战神模式
- 低调模式