# react-native-easing
[![Platform](https://img.shields.io/badge/platform-react--native-lightgrey.svg)](http://facebook.github.io/react-native/)
[![npm version](http://img.shields.io/npm/v/react-native-easing.svg)](https://www.npmjs.com/package/react-native-easing)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/thisXY/react-native-easing/master/LICENSE)

react native easing的一些别名封装和自定义封装,让你可以更好地使用easing

### 安装

```bash
npm install react-native-easing --save
```

### 方法
| name                    | description                                                                                                                                                                                                                        
| :---------------------- | :--------------------------------------                                                            
| easeIn                  | 别名
| easeOut                 | 别名
| easeInOut               | 别名
| easeInCubic             | 别名
| easeOutCubic            | 别名
| easeInOutCubic          | 别名
| easeInCirc              | 别名
| easeOutCirc             | 别名
| easeInOutCirc           | 别名
| easeInExpo              | 别名
| easeOutExpo             | 别名
| easeInOutExpo           | 别名
| easeInQuad              | 别名
| easeOutQuad             | 别名
| easeInOutQuad           | 别名
| easeInQuart             | 别名
| easeOutQuart            | 别名
| easeInOutQuart          | 别名
| easeInQuint             | 别名
| easeOutQuint            | 别名
| easeInOutQuint          | 别名
| easeInSine              | 别名
| easeOutSine             | 别名
| easeInOutSine           | 别名
| easeInBack              | 别名
| easeOutBack             | 别名
| easeInOutBack           | 别名
| easeInElastic           | 别名
| easeInElasticCustom     | easeInElastic自定义(param: bounciness)
| easeOutElastic          | 别名
| easeOutElasticCustom    | easeOutElastic自定义(param: bounciness)
| easeInOutElastic        | 别名
| easeInOutElasticCustom  | easeInOutElastic自定义(param: bounciness)
| easeInBounce            | 别名
| easeOutBounce           | 别名
| easeInOutBounce         | 别名
| linear                  | 别名、react native方法
| step0                   | react native方法
| step1                   | react native方法
| ease                    | react native方法
| quad                    | react native方法
| cubic                   | react native方法
| poly                    | react native方法
| sin                     | react native方法
| circle                  | react native方法
| exp                     | react native方法
| elastic                 | react native方法
| back                    | react native方法
| bounce                  | react native方法
| bezier                  | react native方法
| in                      | react native方法
| out                     | react native方法
| inOut                   | react native方法

* 别名效果如下图(详见: https://easings.net):

![screenshot](https://raw.github.com/thisXY/react-native-easing/master/easings.png)

* react native方法详见: https://reactnative.cn/docs/easing/

### 源码

> https://github.com/thisXY/react-native-easing

### react native动画组件推荐
* https://github.com/thisXY/react-native-animated-view 
  > 你可以像jQuery那样只给结果样式就能操作各种动画,你可以控制每一个样式的动画时间、动画函数甚至每一帧等。总之,你可以随意搭配轻松如意地操纵react-native动画
* https://github.com/thisXY/react-native-touchable-view 
  > 你可以依赖这个TouchableView的长按,滑动,X轴滑动,Y轴滑动,长按后滑动等手势响应得到回调和一系列参数(如相对父组件x、y坐标,相对页面x、y坐标,x轴位移、y轴位移)处理你的业务(如手势动画)