### [[ << 回到主页 ]](../index.md)

# Graphic

> Graphic 模块提供图形相关API

## API列表：

+ [SetCursorShow(flag)](_SetCursorShow_.md)：设置鼠标是否显示

+ [LoadImage(path)](_LoadImage_.md)：加载图像文件

+ [SetImageColorKey(image, flag, color)](_SetImageColorKey_.md)：设置的图片文件是否启用指定的ColorKey，启用的Color将被透明化

+ [UnloadImage(image)](_UnloadImage_.md)：释放已加载的图像

+ [CreateTexture(image)](_CreateTexture_.md)：从图像数据创建属于窗口的可渲染纹理

+ [DestroyTexture(texture)](_DestroyTexture_.md)：销毁纹理数据

+ [SetTextureAlpha(texture, alpha)](_SetTextureAlpha_.md)：设置纹理透明度

+ [GetImageSize(image)](_GetImageSize_.md)：获取已加载图像尺寸

+ [CopyTexture(texture, rect)](_CopyTexture_.md)：将纹理拷贝至渲染缓冲区内

+ [CopyRotateTexture(texture, angle, center, mode, rect)](_CopyRotateTexture_.md)：将旋转后的纹理拷贝至渲染缓冲区内

+ [CopyReshapeTexture(texture, shape, rect)](_CopyReshapeTexture_.md)：将裁剪后的纹理拷贝至渲染缓冲区内

+ [CopyRotateReshapeTexture(texture, angle, center, mode, shape, rect)](_CopyRotateReshapeTexture_.md)：将旋转且裁剪后的纹理拷贝至渲染缓冲区内

+ [SetDrawColor(color)](_SetDrawColor_.md)：设置窗口绘图颜色

+ [GetDrawColor()](_GetDrawColor_.md)：获取窗口绘图颜色

+ [Point(point)](_Point_.md)：在指定位置绘制点

+ [Line(start, end)](_Line_.md)：在指定位置绘制直线

+ [ThickLine(start, end, width)](_ThickLine_.md)：在指定位置绘制粗直线

+ [Rectangle(rect)](_Rectangle_.md)：在指定位置绘制无填充矩形

+ [FillRectangle(rect)](_FillRectangle_.md)：在指定位置绘制填充矩形

+ [RoundRectangle(rect, radius)](_RoundRectangle_.md)：在指定位置绘制圆角无填充矩形

+ [FillRoundRectangle(rect, radius)](_FillRoundRectangle_.md)：在指定位置绘制圆角填充矩形

+ [Circle(center, radius)](_Circle_.md)：在指定位置绘制无填充圆形

+ [FillCircle(center, radius)](_FillCircle_.md)：在指定位置绘制填充圆形

+ [Ellipse(center, radiusX, radiusY)](_Ellipse_.md)：在指定位置绘制无填充椭圆

+ [FillEllipse(center, radiusX, radiusY)](_FillEllipse_.md)：在指定位置绘制填充椭圆

+ [Pie(center, radius, startAngle, endAngle)](_Pie_.md)：在指定位置绘制无填充扇形

+ [FillPie(center, radius, startAngle, endAngle)](_FillPie_.md)：在指定位置绘制填充扇形

+ [Triangle(point1, point2, point3)](_Triangle_.md)：在指定位置绘制无填充三角形

+ [FillTriangle(point1, point2, point3)](_FillTriangle_.md)：在指定位置绘制填充三角形

+ [LoadFont(path, size)](_LoadFont_.md)：加载字体文件

+ [UnloadFont(font)](_UnloadFont_.md)：释放已加载的字体

+ [GetFontStyle(font)](_GetFontStyle_.md)：获取已加载字体的样式

+ [SetFontStyle(font, style)](_SetFontStyle_.md)：设置已加载字体的样式

+ [GetFontOutlineWidth(font)](_GetFontOutlineWidth_.md)：获取已加载字体的轮廓线宽度

+ [SetFontOutlineWidth(font, width)](_SetFontOutlineWidth_.md)：设置已加载字体的轮廓线宽度

+ [GetFontKerning(font)](_GetFontKerning_.md)：获取字体间距

+ [SetFontKerning(font, kerning)](_SetFontKerning_.md)：设置字体间距

+ [GetFontHeight(font)](_GetFontHeight_.md)：获取字体高度

+ [GetTextSize(font, text)](_GetTextSize_.md)：获取文本尺寸

+ [GetUTF8TextSize(font, text)](_GetUTF8TextSize_.md)：获取UTF-8编码格式的文本尺寸

+ [CreateTextImageSolid(font, text, color)](_CreateTextImageSolid_.md)：使用Solid模式创建文本图像

+ [CreateUTF8TextImageSolid(font, text, color)](_CreateUTF8TextImageSolid_.md)：使用Solid模式创建UTF-8编码格式的文本图像

+ [CreateTextImageShaded(font, text, fgColor, bgColor)](_CreateTextImageShaded_.md)：使用Shaded模式创建文本图像

+ [CreateUTF8TextImageShaded(font, text, fgColor, bgColor)](_CreateUTF8TextImageShaded_.md)：使用Shaded模式创建UTF-8编码格式的文本图像

+ [CreateTextImageBlended(font, text, color)](_CreateTextImageBlended_.md)：使用Blended模式创建文本图像

+ [CreateUTF8TextImageBlended(font, text, color)](_CreateUTF8TextImageBlended_.md)：使用Blended模式创建UTF-8编码格式的文本图像