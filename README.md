# canvas-time
### 用到的canvas，api：
- save()	保存当前环境的状态
- restore()	返回之前保存过的路径状态和属性
- translate()	重新映射画布上的 (0,0) 位置
- fillStyle	设置或返回用于填充绘画的颜色、渐变或模式
- lineCap	设置或返回线条的结束端点样式
- lineWidth	设置或返回当前的线条宽度
- fill()	填充当前绘图（路径）
- stroke()	绘制已定义的路径
- beginPath()	起始一条路径，或重置当前路径
- moveTo()	把路径移动到画布中的指定点，不创建线条
- lineTo()	添加一个新点，然后在画布中创建从该点到最后指定点的线条
- arc()	创建弧/曲线（用于创建圆形或部分圆）
- rotate()	旋转当前绘图
- font	设置或返回文本内容的当前字体属性
- textAlign	设置或返回文本内容的当前对齐方式
- textBaseline	设置或返回在绘制文本时使用的当前文本基线
- fillText()	在画布上绘制“被填充的”文本
