unquote() //处理无法操作的属性值

transition: background 0.5s ease-in,color 0.3s ease-out;
第一个transition-duration
第二个为transition-delay


## 动画曲线
1、ease：（逐渐变慢）默认值，
2、linear：（匀速
3、ease-in：(加速)
4、ease-out：（减速）
5、ease-in-out：（加速然后减速）
6、cubic-bezier：（该值允许你去自定义一个时间曲线）

## linear-gradient
/* Firefox 3.6+ */
background: -moz-linear-gradient(top, #ace, #f96);
/* Safari 4-5, Chrome 1-9 */
/* -webkit-gradient(,  [, ]?,  [, ]? [, ]*) */
background: -webkit-gradient(linear,top,from(#ace),to(#f96));
/* Safari 5.1+, Chrome 10+ */
background: -webkit-linear-gradient(top, #ace, #f96);
/* Opera 11.10+ */
background: -o-linear-gradient(top, #ace, #f96);
