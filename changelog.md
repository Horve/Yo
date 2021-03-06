# Yo Changelog

History Version and release time.

<a name="v1-5-0"></a>
## v1.5.0 (2015.4.30)

[Tagged on Github.](https://github.com/doyoe/Yo/releases/tag/v1.5.0)

* update: `yo-tab`
    - 删除tab子项的:active状态
    - 选中状态只保留 `item-on` 类名，删除 `on`
* update: `yo-loading`
    - loading换成webfonts
    - `size` 参数改成 `ico-size`
    - `color` 参数改成 `ico-color`
    - 新增 `font-size` 参数用以控制文本大小
    - 新增 `color` 参数用以控制文本颜色
    - 新增 `content` 参数用以控制loading的形态，可传入webfonts编码
* update:
    - 删除元素 `yo-checkbox` 和 `yo-radio`，如已使用可以直接改用 `yo-checked`

<a name="v1-4-0"></a>
## v1.4.0 (2015.4.16)

[Tagged on Github.](https://github.com/doyoe/Yo/releases/tag/v1.4.0)

* update:
    - 删除了 `layout.scss`，如果当前页面需要设置root是否允许滚动，使用 `root-scroll()` 方法
    - 新增 `yo-flex` 弹性布局方法
* update: `flex` 方法
    - 删除 `flex` 方法的 `display: block` 设置，如果参与flex布局，请自行使用非inline元素
* update: `yo-badge`
    - 新增 `padding` 参数用于设置内补白
    - 新增 `border-width` 参数用于设置边框厚度
* update: `yo-btn`
    - 新增 `border-width` 参数用于设置边框厚度
* update: `yo-checked`
    - 删除 `type` 参数，不再使用该参数设置来判定使用哪个标记
    - 新增 `content` 参数用于设置标记，可以直接传字符或者iconfont
    - 新增 `font-size` 参数用于标记大小
    - 新增 `border-width` 参数用于设置边框厚度
    - 新增 `color` 参数用于未选中状态时的标记颜色
* add `background-size` 方法
* update: `yo-header`
    - 增加 `item-ico-size` 参数，用于设置两侧ico的大小
* update: `yo-list`
    - 删除 `is-outline` 参数，新增 `border-width` 参数用于设置外边框厚度
    - 增加 `on-color` 参数，用于设置列表项选中时文本色
    - 删除列表项的 `min-height` 定义
* update: `yo-search`
    - 增加 `cancel-width` 参数，用于设置取消按钮区域的宽度

<a name="v1-3-1"></a>
## v1.3.1 (2015.3.27)

[Tagged on Github.](https://github.com/doyoe/Yo/releases/tag/v1.3.1)

* update: `yo-switchable` 参数配置
* update: `yo-btn`
    - 增加 `active-bordercolor`, `active-bgcolor`, `active-color` 参数，用于设置按钮按下时的边框、背景、文本颜色；
* update: `yo-tab`
    - 删除 `is-border`, `is-item-border`, `on-bordercolor` 参数；
    - 新增 `border-width` 参数，用于设置tab的外边框厚度；
    - 新增 `radius` 参数，用于设置tab的圆角大小；
    - 新增 `item-border-height` 参数，用于设置tab子项间隔线的高度；
    - 新增 `item-bordercolor` 参数，用于设置tab子项间隔线的颜色；
* add: 新增分值元素 `yo-score`；
* add: 新增双list `yo-dblist`；
* update: 建议单选和多选都使用 `yo-checked`，后续考虑将 `yo-checkbox` 及 `yo-radio` 删除，尽量不要使用，之前使用过最好及时替换；
* update: `yo-checked`
    - 删除 `is-border` 参数，不再使用该参数来设定是否有边框，利用原有 `bordercolor` 参数，当值为 `transparent` 时，则无边框；
    - 删除 `disabled-color` 参数，Yo所有元素的禁用色都改为继承 `$base` map；
    - 增加 `radius` 参数用于设置圆角；
    - 增加 `on-bordercolor` 参数用于设置激活边框色；
    - 增加 `on-bgcolor` 参数用于设置激活背景色；
* update: yo-rating 外观
    - 增加 `url` 参数用于改变 yo-rating 的外观；

<a name="v1-2-0"></a>
## v1.2.0 (2015.3.20)

[Tagged on Github.](https://github.com/doyoe/Yo/releases/tag/v1.2.0)

* update: yo-checkbox 增加圆角参数；
* update: yo-list 增加label和item的颜色参数，字号参数；为item设定最小高度；
* update: yo-header 两侧文本色参数；
* update: yo-group 无数据状态；
* update: yo-tab 增加对ico大小，文本大小的参数配置，并删除默认的横向文本大小设定；
* update: yo-ico 删除 .eot 及 .svg 字体；
* update: yo-loadtip 增加加载失败和成功，同时增加下拉/释放图标动画；
* fixed: yo-group 滚动时顶部溢出；
* fixed: yo-switchable 在小米4上，当使用translatez/translate3d偏移时，会覆盖在其它层级比自身高的元素之上；
* add yo-rating；
* add yo-panel；
* fixed: fixed yo-switch handle bug on samsung s4；

<a name="v1-1-0"></a>
## v1.1.0 (2015.3.12)

[Tagged on Github.](https://github.com/doyoe/Yo/releases/tag/v1.1.0)

* add yo-loadtip
* update: add disabled status for yo-select
* add demo index page
* update: add border for yo-badge
* update: add width 100% for yo-switchable wrap

<a name="v1-0-0"></a>
## v1.0.0 (2015.3.9)

[Tagged on Github.](https://github.com/doyoe/Yo/releases/tag/v1.0.0)

* 新增 widget yo-switch，并移除 element yo-switch；
* 新增 widget yo-switchable
* 修订 widget yo-select背景色问题