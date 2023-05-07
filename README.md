<p align="center"><h1>🖼️ 🖌️awesome-ai-draw-prompts 最全AI画图魔法技巧集合贴</h1></p>


**[View on GitHub](https://github.com/Nolookpassit/awesome-ai-draw-prompts)**



---
## AI绘画风格关键词

|  风格类型   | 魔法词  |
|  ----     | ----  |
| 经典      | classic |
| 现代      | modern |
|复古       | vintage |
| 工匠风格  | artisan |
| 当代      | contemporary |
| 极简主义 | minimalist |
| 异国风情 | exotic |
| 部落风格 | tribal |
| 装饰艺术风格 | art deco |
| 文艺复兴风格  | renaissance |
| 巴洛克    | baroque |
| 哥特式    | gothic |
| 浪漫      | romantic |
| 新艺术风格 | art nouverau |
| 维多利亚式 | victorian |
| 爱德华式  | edwardian |

---
## Midjourney⁢ 万能prompt架构

架构1:
【画面主体】+【画面环境】+【镜头视角】+【风格参考】+【渲染方式】




架构2:
【主题】 + 【媒介】 + 【背景】 + 【灯光】 + 【颜色】 + 【色彩】 + 【气氛】 + 【视角】 + 【镜头】 + 【构图】 + 【艺术风格】


|  架构   | 具体描述  |
|  ----     | ----  |
| 主题     | 人（girl）/ 动物（cat) / 人物（guy）/ 物体（box）|
| 媒介     | 照片（photo）/ 绘画（paint) / 雕塑（sculpture）/ 涂鸦（doodle）/ 插图（illustration）|
| 背景     | 森林（forest）/ 街景（ street) / 宇宙（universal cosmos）/ 水下（underwater）|
| 镜头    | 全景（panorama）/ 单反（ ) / 宇宙（universal cosmos）/ 水下（underwater）|



例子： prompt：a girl，illustration，forest，bright，gold color，happy，full lenghth shot，miyazaki hayao style --q 2 --s 250 --v 5


---
## Midjourney⁢ 指令说明

"/imagine" 以文生图

以文生图就是直接使用 “/imagine” 命令制作图片，

首先我来认识一下prompt的组成，一般由 一个或多个图像的URL + 一个或多个文本短语 + 一个或多个后缀参数组成；

URL一般是我们上传参考图片的链接，文本短语就是对想要生成的图像的文本描述，后缀参数是控制图像生成的模型版本、宽高比、风格化参数等，其中文本短语和后缀参数是必要条件。

(图片)

U 的命令是对指定一张图片进行品质提高、V 的命令是对指定一张图片进行延展；




"setting" 设置项

"subscribe" 订阅


"info" 
查看有关当前排队和正在进行的作业，订阅类型，续订日期等信息

"prefer suffix"
设置默认添加到每个提示末尾的后缀。设置后，每次都会自动再提示内容后加上对应后缀，方便后续使用，如--v5。 （主义只支持参数，不支持提示词）


"prefer option set"
后缀集合，可以把一系列后缀命名为一个集合，快速来使用
如：--hd --ar 1:1

"blend" 图片融合
以图生图，支持上传2-5张图片作为提示内容，然后融合为新的图片







