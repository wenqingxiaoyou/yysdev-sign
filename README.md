# yysdev-sign
  签到前台页面
# 首先：
  写页面的模板，引入文件libyys-flexible.js和reset.css和common.css.
  psd图是720px的，就应该在libyys-flexible.js中的自执行函数中穿入的参数为720
# rem值计算
  适配方案采用rem，按照psd的大小设置具体的rem值，比如,写具体的模块时，比如一个banner的高度为300px，写css时只需写上3rem，即实际的宽高值除以100，得到相应的rem值。
