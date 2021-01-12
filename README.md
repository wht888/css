# 你好，我是王海涛，本项目为 css 精华，分为 3 块内容

```
1、我经常用的base.css，超实用
2、经常用到的非常常见的css的demo，都是必会的
3、我总结的css所有属性
```

# css 属性

## 以下 css 你有可能不知道，但很有用

- 1、重置样式 all: initial;
- 2、去除 button 轮廓 outline:none
- 3、自定义文字选择 ::selection
- 4、禁用文字选择 user-select: none;
- 5、自定义滚动条 ::-webkit-scrollbar ::-webkit-scrollbar-track ::-webkit-scrollbar-thumb
- 6、css 最完美的过渡时间是 0.3s
- 7、控制全屏模式的样式 :fullscreen

## 内容

- content
- counter-increment（递增递减计数器）
- counter-reset（创建重置计数器）
- quotes（引号类型）

## 字体属性

- font
- font-family（字体系列）
- font-size
- font-style normal italic（斜体） oblique（倾斜） inherit
- font-weight bold bolder lighter
- @font-face 自定义字体

## 文本属性（Text）

- color
- direction ltr rtl
- letter-spacing（字符间距）
- line-height
- text-align
- text-decoration（装饰效果） underline overline line-through
- text-indent（缩进）
- text-shadow（阴影）
- text-transform（大小写） capitalize uppercase lowercase
- white-space（处理空白） pre nowrap pre-wrap pre-line
- word-spacing（单词间距）
- text-overflow（文本溢出） clip（裁剪） ellipsis（省略号）
- text-shadow
- word-break（换行规则） break-all（单词内换行） keep-all（半角空格或连字符处换行）
- word-wrap（长单词换行） break-word

## 背景

- background（背景） linear-gradient()（渐变）
- background-attachment（背景依附滚动）: scroll（滚动） fixed（固定） inherit（继承）
- background-color（背景颜色）
- background-image（背景图片）
- background-position（背景位置）
- background-repeat（背景重复）
- background-clip（背景裁剪）: border-box padding-box content-box
- background-origin（背景原点）: border-box padding-box content-box
- background-size（背景大小）: cover（覆盖） contain（包含）

## 尺寸属性

height
max-height
min-height
width
max-width
min-width

## 内边距属性（Padding）

- padding
- padding-bottom
- padding-left
- padding-right
- padding-top

## 边框

- border
- border-color
- border-style
- border-width
- border-top right bottom left
- border-top-color
- border-top-style
- border-top-width
- outline（轮廓）
- outline-color
- outline-style
- outline-width
- border-radius(边框圆角)
- border-top-left-radius
- border-top-right-radius
- border-bottom-left-radius
- border-bottom-right-radius
- border-image
- border-image-outset（边框图片超出边框的量）
- border-image-repeat stretch（拉伸） repeat（重复） round
- border-image-slice（内向便宜）
- border-image-source
- border-image-width
- box-shadow（阴影）h-shadow（水平位移） v-shadow（垂直位移） blur（模糊距离） spread（尺寸） color inset（内阴影）

## 外边距属性（Margin）

- margin
- margin-bottom
- margin-left
- margin-right
- margin-top

## Box 属性

- overflow-x（x 轴溢出） visible hidden scroll auto no-display no-content
- overflow-y（y 轴溢出）
- opacity （透明度）

## 列表属性（List）

- list-style
- list-style-image
- list-style-position outside inside
- list-style-type

## CSS 定位属性（Positioning）

- position absolute fixed relative static
- top
- right
- bottom
- left
- z-index
- clip

## 内容相关

- float
- clear
- cursor
- display
- overflow
- vertical-align
- visibility

## CSS 表格属性（Table）

- border-collapse(边框合并) separate（分离） collapse（合并）
- border-spacing（边框距离）
- caption-side （标题位置）
- empty-cells（空单元格）
- table-layout（布局方式） automatic（内容来定） fixed（固定）

## 2D/3D 转换属性（Transform）

- transform translate(x,y)（移动） scale(x,y)（缩放） rotate(90deg)（旋转） skew(x,y)（倾斜）
- transform translate3d(x,yz) scale3d(x,y,z) rotate3d(x,y,z,angle)
- transform-origin
- transform-style
- backface-visibility（背面显示）

## 过渡属性（Transition）

- transition
- transition-property
- transition-duration
- transition-timing-function
- transition-delay

## 动画

- @keyframes（动画规则）
- animation
- animation-name
- animation-duration（持续时间）
- animation-timing-function（速度） linear（匀速） ease（先快后慢） ease-in（加速） ease-out（减速） ease-in-out cubic-bezier(n,n,n,n)
- animation-delay（延迟时间）
- animation-iteration-count（播放次数）
- animation-direction（方向）normal alternate
- animation-play-state（状态）paused running
- animation-fill-mode forwards backwards both

## 用户界面属性

- box-sizing content-box border-box

## 浮动布局方式

- <div class='clearfix'><div class='fl'></div><div class='fr'></div></div>
- .clearfix::after{content:'';display:block;clear:both;}
- .fl{float:left;}
- .fr{float:right;}

## flex 布局方式

- display: flex display: inline-flex
- flex-direction（方向） row（前到后） row-reverse（后到前） column（上到下） column-reverse（下到上）
- flex-wrap（换行） nowrap（不换行） wrap（换行） wrap-reverse（换行后，每一个行倒序）
- flex-flow 等于 flex-direction 加上 flex-wrap
- justify-content（横轴对齐方式） flex-start flex-end center space-around space-between
- align-items（交叉轴对齐方式） flex-start flex-end center baseline stretch
- align-content（纵轴对齐方式） flex-start flex-end start end center space-around space-between space-evenly stretch
- flex-grow（分配剩余空间）
- flex-shrink（剩余空间不足，缩小每一项） 默认 1 缩小 0 不缩小
- flex-basis（占用的固定空间）
- flex 等于 flex-grow 加上 flex-shrink 加上 flex-basis
- align-self（单个项目对齐方式）
- order（排序）

## grid 布局方式

- display: grid display: inline-grid
- grid-template-columns（列） repeat(3, 100px) auto-fill（自动填充列数） 1fr 和 auto（自动填充宽度） minmax()（范围之内）
  grid-template-columns: [c1] 100px [c2] 100px [c3] auto [c4]; 网格线的名称
- grid-template-rows（行）
- grid-row-gap grid-column-gap grid-gap 间距
- grid-template-areas 区域名称
- grid-auto-flow 顺序 row column
- justify-items align-items place-items
- justify-content align-content place-content
- grid-auto-columns grid-auto-rows
- grid-template
- grid
- grid-column-start grid-column-end grid-row-start grid-row-end
- grid-column grid-row
- grid-area
- justify-self align-self place-self
