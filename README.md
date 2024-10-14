# KevinZonda's Typora Theme

> Adapted from [Sophomoresty/typora-theme-Jinxiu](https://github.com/Sophomoresty/typora-theme-Jinxiu), which is licensed under MIT.

### 安装主题
1. 打开`Typora`->文件->偏好设置->外观->打开主题文件夹

2. 复制`KevinZonda.css`文件到主题文件夹下

3. 重启`Typora`

4. 打开`Typora`->主题->选择

### 安装字体

进入解压缩后的文件夹，打开`fonts`文件夹，双击字体文件，安装字体，建议全部安装。

**请务必确认您完成了下面的步骤：**
- 安装主题
- 下载并安装所需的字体

## 论文封面修改

封面`cover-templated.md`和示例论文`essay-template.md`在`template`文件夹中。

论文封面使用HTML实现，使用时，替换掉对应的内容即可。

> 如需更换为自己的学校，找到自己学校的校徽、校名的高清图，在[在线转换网站中](https://products.aspose.app/imaging/zh-hans/conversion)将图片转化为SVG，在`cover/essay-template`封面HTML中替换相应的链接即可
>
>![image-20240825031255756.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/template/assets/image-20240825031255756.png?raw=true)

## scu-essay格式总览

|         大纲级别          |        英，中字体         | 样式            | 中文字号  | 磅/pt |
| :-----------------------: | :-----------------------: | --------------- | :-------: | :---: |
|         封面标题          | Times New Roman，华文中宋 | 加粗            |   一号    |  26   |
|       封面表格内容        | Times New Roman，思源宋体 | 加粗            |   四号    |  14   |
|        论文总标题         | Times New Roman，华文中宋 | 加粗            | 二号 加粗 |  22   |
|       学校专业姓名        |   Times New Roman，楷体   | 无              |   四号    |  14   |
|        摘要/关键字        |   Times New Roman，楷体   | 加粗            |   小五    |   9   |
|     摘要/关键字的内容     |   Times New Roman，楷体   | 无              |   小五    |   9   |
|        一级标题/h1        | Times New Roman，华文中宋 | 加粗            |   小三    |  15   |
|        二级标题/h2        | Times New Roman，华文中宋 | 加粗            |   四号    |  14   |
|        三级标题/h3        | Times New Roman，华文中宋 | 加粗            |   小四    |  12   |
| 四、五、六级标题/h4,h5,h6 |   Times New Roman，楷体   | 加粗            |   小四    |  12   |
|           正文            | Times New Roman，思源宋体 | 无，行间距1.5倍 |   小四    |  12   |
|         表格标题          |   Times New Roman，楷体   | 加粗            |   小四    |  12   |
|         表格内容          |   Times New Roman，楷体   | 无              |   五号    | 10.5  |
|          引用块           |   Times New Roman，楷体   | 无              |   小四    |  12   |
|      行内代码/代码块      |    Cantarell，思源宋体    | 无              |   小四    |  12   |

### 页边距

上2.5cm，下2.5cm，左2.5cm，右2cm，装订线0

>经过测试，导出不用设置`Typora`的`PDF`页边距。
>
>如需修改页边距，请在主题`CSS`中修改图中的`margin`值，顺序是上、右、下、左，不要删除后面的`! important;`
>举例，如果需要修改页边距为上1cm、下1cm、左2cm、右1.5cm，则应填：`1cm 1.5cm 1cm 2cm`
>
>![image-20240825035038063.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/template/assets/image-20240825035038063.png?raw=true)
>

## Credit

- [Sophomoresty/typora-theme-Jinxiu](https://github.com/Sophomoresty/typora-theme-Jinxiu)
  - [Keldos-Li/typora-latex-theme](https://github.com/Keldos-Li/typora-latex-theme)
  - [YiNNx/typora-theme-lapis](https://github.com/YiNNx/typora-theme-lapis) 

