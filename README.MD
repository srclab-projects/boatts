# boatts
Boat for typescript

# 快速上手
## 安装
```shell
npm install boatts
```
## 全局注册（在main.js文件里注册）
```javascript
import boatts from 'boatts';
global.boatts = boatts;
```
## 局部注册（在你所使用的vue里注册）
```javascript
import boatts from 'boatts';
```
## 例子
姓名脱敏
```javascript
let str = boatts.$aboutBoatTs();
```


#目录
* [1.About](#aboutBoatTs)

```
<h6 id="aboutBoatTs">1.About</h6>
```javascript
//返回字符串
let str = boatts.$aboutBoatTs();
```