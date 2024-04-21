# 📄项目简介

![](images/Banner_Image1.jpg)

分享最好用、最实用的ComfyUI工作流，最新、最前沿的研究成果和相应的自定义节点（custom nodes），实用的视频、文字教程和知识等。

---

# 📊工作流分享

我把最实用的工作流（workflow）都给毫无保留地免费分享给所有需要的人：[点击此处查看pysssss-workflows文件夹](./pysssss-workflows)

| 序号  | 工作流名称                                                                                                                                                                                                                                                                                | 工作流功能                                                                                                                                                                                                                                                                                                                                                                                                         | 视频教程                                                                                                                                                                              |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [1.0Cascade_Standard](pysssss-workflows/1.0Cascade_Standard.json)                                                                                                                                                                                                                    | 基本的``stable cascade``工作流，什么是cascade：[introducing-stable-cascade](https://stability.ai/news/introducing-stable-cascade)                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                   |
| 2   | [1.1cascade-inpainting](pysssss-workflows/1.1cascade-inpainting.json)                                                                                                                                                                                                                | cascade的inpainting（局部重绘）功能                                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                   |
| 3   | [2.0放大supir](pysssss-workflows/2.0放大supir.json)                                                                                                                                                                                                                                      | 个人认为目前为止最好的放大模型                                                                                                                                                                                                                                                                                                                                                                                               | [SUPIR](https://www.bilibili.com/video/BV1nr42187dq/?share_source=copy_web&vd_source=22e73f717510e88027a60aa9c288021d)                                                            |
| 4   | [3.0检测（简单）YoloWorld-EfficientSAM](pysssss-workflows/3.0检测（简单）YoloWorld-EfficientSAM.json)                                                                                                                                                                                            | 自动检测任何物体，真的很神奇！                                                                                                                                                                                                                                                                                                                                                                                               |                                                                                                                                                                                   |
| 5   | [3.1检测+重绘YoloWorld-EfficientSAM](pysssss-workflows/3.1检测+重绘YoloWorld-EfficientSAM.json)                                                                                                                                                                                              | 检测图片里面的猫，全部换成狗。                                                                                                                                                                                                                                                                                                                                                                                               |                                                                                                                                                                                   |
| 6   | [4.0修复手部](pysssss-workflows/4.0修复手部.json)                                                                                                                                                                                                                                            | 修复手部很好用                                                                                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                                                                   |
| 7   | [5.0扩图](pysssss-workflows/5.0扩图.json)                                                                                                                                                                                                                                                | 用的[Fooocus](https://github.com/lllyasviel/Fooocus)的模型，所以效果很不错，功能也很像。                                                                                                                                                                                                                                                                                                                                          |                                                                                                                                                                                   |
| 8   | 1️⃣-[6.0移除背景BRIA](pysssss-workflows/6.0移除背景BRIA.json)<br>2️⃣-[6.0移除背景BiRefNet-ZHO](pysssss-workflows/6.0移除背景BiRefNet-ZHO.json)<br>3️⃣-[6.0移除背景3件套](pysssss-workflows/6.0移除背景3件套.json)<br>                                                                                            | 1.高效移除背景。**huggingface demo**：[BRIA-RMBG-1.4 demo](https://huggingface.co/spaces/briaai/BRIA-RMBG-1.4)<br>2.对 [BiRefNet](https://github.com/zhengpeng7/birefnet) 的非官方实现 ，可输出透明背景PNG ，可抠视频。<br>3.[ComfyUI_LayerStyle](https://github.com/chflame163/ComfyUI_LayerStyle)推荐的[MaskEdgeUltraDetailV2](https://github.com/chflame163/ComfyUI_LayerStyle#maskedgeultradetailv2)让扣出的边缘超精细，甚至适用于处理半透明区域，同时出3个方案供选。<br> | 2.[ComfyUI一键抠图-顶级大佬手笔！](https://www.bilibili.com/video/BV1Gj421R7DM/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                                                                  |
| 9   | [9.0InstantID-换脸到任何风格图上](pysssss-workflows/9.0InstantID-换脸到任何风格图上.json)                                                                                                                                                                                                              | 换脸到任何风格图上，这个换脸是真好玩。                                                                                                                                                                                                                                                                                                                                                                                           | [ComfyUI-InstantID-换脸到任何风格图上](https://www.bilibili.com/video/BV1Mq421P77H/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                                                            |
| 10  | [9.1IPAdapter-V2.0风格转换](pysssss-workflows/9.1IPAdapter-V2.0风格转换.json)<br>[9.2IPAdapter-V2.0构图转换](pysssss-workflows/9.2IPAdapter-V2.0构图转换.json)<br>[9.3IPAdapter-V2.0构图+风格转换](pysssss-workflows/9.3IPAdapter-V2.0构图+风格转换.json)<br>[线稿上色系列工作流](./resources/ComfyUI+IPAdapter线稿上色系列工作流) | 新功能:风格迁移和构图迁移                                                                                                                                                                                                                                                                                                                                                                                                 | [IPAdapter v2.0又添新功能：一键风格迁移+构图迁移](https://www.bilibili.com/video/BV1CA4m1A7Y9/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                                                        |
| 11  | [10局部重绘-进阶版](pysssss-workflows/10局部重绘-进阶版.json)                                                                                                                                                                                                                                      | 重绘出细节与灵魂-[differential-diffusion](https://github.com/exx8/differential-diffusion)-最新重绘inpainting工作流。<br>[huggingface在线演示](https://huggingface.co/spaces/exx8/differential-diffusion)                                                                                                                                                                                                                          | [Differential Diffusion](https://www.bilibili.com/video/BV1zp421C7pm/?spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=7351bb1ce0a307c41b60b64ca036a240) |
| 12  | [1.2cosXL编辑版](pysssss-workflows/1.2cosXL编辑版.json)                                                                                                                                                                                                                                    | [cosxl模型下载](https://huggingface.co/stabilityai/cosxl)注意ComfyUI更新到最新！                                                                                                                                                                                                                                                                                                                                          | [cosxl视频介绍](https://www.bilibili.com/video/BV19C41157h1/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                                                                              |
| 13  | [11ELLA-复杂提示词理解](pysssss-workflows/11ELLA-复杂提示词理解.json)                                                                                                                                                                                                                              | [ELLA模型下载地址、YouTube视频等](docs/ELLA模型下载地址、YouTube视频等.md)                                                                                                                                                                                                                                                                                                                                                        | [ELLA视频解说](https://www.bilibili.com/video/BV1Sp421Q7n5/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                                                                               |

# 👍custom nodes排行榜
## 📈排行榜网站[nodecafe](https://www.nodecafe.org/)
看最新的custom nodes的⭐排行榜，请看这个网站📈[nodecafe](https://www.nodecafe.org/)，由[comfyui-workspace-manager](https://github.com/11cafe/comfyui-workspace-manager)构建，根据开源`custom nodes`获得的stars⭐排名！
## 🔍 亲测！强力推荐！
我自己亲测后，觉得是必装的，且在用的`custom nodes`。排名是我认为的，⭐的多少（实时）只是参考。

| Custom Nodes（实时⭐）                                                                                                                                                                       | 简介（最有用的功能）                                                                                                                               | 视频教程                                                                                                                                                |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI)<br>![GitHub Repo stars](https://img.shields.io/github/stars/comfyanonymous/ComfyUI)                                                | ComfyUI本体，神一样的存在！<br>[ComfyUI快捷键](https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file#shortcuts)<br>                            |                                                                                                                                                     |
| [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager)<br>![GitHub Repo stars](https://img.shields.io/github/stars/ltdrdata/ComfyUI-Manager)                                    | 安装、删除、禁用和启用 ComfyUI 各种自定义节点等等功能。                                                                                                         |                                                                                                                                                     |
| [ComfyUI-Custom-Scripts](https://github.com/pythongosssss/ComfyUI-Custom-Scripts)<br>![GitHub Repo stars](https://img.shields.io/github/stars/pythongosssss/ComfyUI-Custom-Scripts)<br> | 图像源：[Image Feed](https://github.com/pythongosssss/ComfyUI-Custom-Scripts?tab=readme-ov-file#image-feed)<br>添加一个面板，显示当前会话中生成的图像，保存自己的工作流。 |                                                                                                                                                     |
| [ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)<br>![](https://img.shields.io/github/stars/cubiq/ComfyUI_IPAdapter_plus)                                      | 遵循ComfyUI方式的IPAdapter实现。该代码内存高效、快速，且不应因Comfy更新而出错。                                                                                       | [ComfyUI-IPAdapter v2版本-官方大佬中文直译版讲解](https://www.bilibili.com/video/BV1jA4m1A7nR/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                       |
| [ComfyUI-layerdiffuse](https://github.com/huchenlei/ComfyUI-layerdiffuse)<br>![](https://img.shields.io/github/stars/huchenlei/ComfyUI-layerdiffuse)                                    | 生成带透明度的图像，无需抠图了，可以直接用于创作素材。                                                                                                              |                                                                                                                                                     |
| [ComfyUI-SUPIR](https://github.com/kijai/ComfyUI-SUPIR)<br>![](https://img.shields.io/github/stars/kijai/ComfyUI-SUPIR)                                                                 | 我愿意称之为免费里面最强的放大方法，但是注意极其占用显存、内存，请看我的视频分享。                                                                                                | [ComfyUI当前最强！一键放大工作流！SUPIR](https://www.bilibili.com/video/BV1nr42187dq/?share_source=copy_web&vd_source=22e73f717510e88027a60aa9c288021d)          |
| [ComfyUI_LayerStyle](https://github.com/chflame163/ComfyUI_LayerStyle)<br>![](https://img.shields.io/github/stars/chflame163/ComfyUI_LayerStyle)                                        | 将一些基本的Photoshop功能迁移到ComfyUI中，还有一键移除背景、AI抠图之类的神奇功能。                                                                                       | [集成PS功能的高级作图工具集](https://www.bilibili.com/video/BV1dH4y1W73g/?spm_id_from=333.337.search-card.all.click&vd_source=7351bb1ce0a307c41b60b64ca036a240) |
| [ComfyUI-N-Sidebar](https://github.com/Nuked88/ComfyUI-N-Sidebar)<br>![](https://img.shields.io/github/stars/Nuked88/ComfyUI-N-Sidebar)<br>                                             | 侧边栏，支持节点的拖放、收藏、搜索，以及类别的展开/收起等功能，极大增强了界面交互体验。                                                                                             | [ComfyUI-N-Sidebar支持节点收藏以及中英文节点搜索](https://www.bilibili.com/video/BV1km411R7iJ/?spm_id_from=333.337.search-card.all.click)<br>                      |
| [comfy-image-saver](https://github.com/giriss/comfy-image-saver)<br>![GitHub Repo stars](https://img.shields.io/github/stars/giriss/comfy-image-saver)                                  | 想要的保存图片的功能都有。                                                                                                                            |                                                                                                                                                     |
## 🗺️安装指南

如果ComfyUI安装了过多组件,可能会出现环境冲突等问题。我推荐使用Anaconda创建虚拟环境来运行ComfyUI,避免潜在的冲突。就算你的虚拟环境也装的太多了，引起了冲突，你还可以再创建一个虚拟环境来专门运行起你现在很需要运行起来的工作流。具体我写了份详细的文档，请批评指正：[Windows环境下ComfyUI自定义节点安装指南](docs/Windows环境下ComfyUI自定义节点安装指南.md)，视频解释：[ComfyUI报错的终极解决方案！](https://www.bilibili.com/video/BV1Up421Q7YA/?vd_source=7351bb1ce0a307c41b60b64ca036a240)

# 💡AIGC前沿技术
（图像、视频、音频、数字人、3D等生成）

| 项目名称及网址                                                                                                                                                                                            | 介绍                                                                                                                                    | huggingface demo（在线生成）                                                                              | ComfyUI实现/视频介绍                                                                                                                                                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [InstantID](https://github.com/InstantID/InstantID)<br>![GitHub Repo stars](https://img.shields.io/github/stars/InstantID/InstantID)<br>                                                           | 【风格、样貌迁移】可实现使用单张图片进行ID保持生成的最先进方法，支持各种下游任务。                                                                                            | [InstantID demo](https://huggingface.co/spaces/InstantX/InstantID)                                  | [ComfyUI InstantID](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID):<br>[ComfyUI_InstantID-（原生支持版）](https://github.com/cubiq/ComfyUI_InstantID)                                                                                                             |
| [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter)<br>![GitHub Repo stars](https://img.shields.io/github/stars/tencent-ailab/IP-Adapter)<br>                                                | 【风格、样貌迁移】                                                                                                                             | [IP-Adapter demo](https://huggingface.co/h94/IP-Adapter)                                            |                                                                                                                                                                                                                                                               |
| [InstantStyle](https://github.com/InstantStyle/InstantStyle)<br>![GitHub Repo stars](https://img.shields.io/github/stars/InstantStyle/InstantStyle)<br>                                            | 【风格迁移】长处是风格参考                                                                                                                         | [InstantStyle demo](https://huggingface.co/spaces/InstantX/InstantStyle)                            |                                                                                                                                                                                                                                                               |
| [AnyText](https://github.com/tyxsspa/AnyText)<br>![GitHub Repo stars](https://img.shields.io/github/stars/tyxsspa/AnyText)<br>                                                                     | 【生成文字】多语言（包括汉字！）视觉文本生成与编辑                                                                                                             | [AnyText demo](https://huggingface.co/spaces/modelscope/AnyText)                                    | [AnyText安装指南](docs/AnyText安装指南.md)<br>[AnyText视频指南](https://www.bilibili.com/video/BV1Kr421G7Xi/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                                                                                                                  |
| [SUPIR](https://github.com/Fanghua-Yu/SUPIR)<br>![GitHub Repo stars](https://img.shields.io/github/stars/Fanghua-Yu/SUPIR)<br>                                                                     | 【图片放大】极致卓越的放大方案，模糊照片还原出照片级别质感                                                                                                         | 暂无                                                                                                  | [ComfyUI-SUPIR](https://github.com/kijai/ComfyUI-SUPIR)                                                                                                                                                                                                       |
| <br>[APISR](https://github.com/Kiteretsu77/APISR)<br>![GitHub Repo stars](https://img.shields.io/github/stars/Kiteretsu77/APISR)<br>                                                               | 【图片放大】- 对 [APISR](https://github.com/Kiteretsu77/APISR) 的非官方实现。专门用于**动漫**的超分模型，包含 2x 和 4x 双模型，速度飞快，效果很好                               | [APISR demo](https://huggingface.co/spaces/HikariDawn/APISR)                                        | [ComfyUI-APISR](https://github.com/ZHO-ZHO-ZHO/ComfyUI-APISR)                                                                                                                                                                                                 |
| [AniPortrait](https://github.com/Zejun-Yang/AniPortrait)<br>![GitHub Repo stars](https://img.shields.io/github/stars/Zejun-Yang/AniPortrait)<br>                                                   | 腾讯团队，对标[EMO](https://github.com/HumanAIGC/EMO)，但是已经开放代码了！利用音频或者视频驱动动画。                                                                | 在线演示：[AniPortrait demo](https://huggingface.co/spaces/ZJYang/AniPortrait_official)                  | [ComfyUI-AniPortrait](https://github.com/chaojie/ComfyUI-AniPortrait)<br>[AniPortrait实测](https://www.bilibili.com/video/BV11D421578H/?vd_source=7351bb1ce0a307c41b60b64ca036a240)                                                                             |
| [champ](https://github.com/fudan-generative-vision/champ)<br>![GitHub Repo stars](https://img.shields.io/github/stars/fudan-generative-vision/champ)<br>                                           | 通过3D参数引导的可控且一致的人像动画，这项目用到了Blender！                                                                                                    |                                                                                                     | [ComfyUI-champWrapper](https://github.com/kijai/ComfyUI-champWrapper)<br>![GitHub Repo stars](https://img.shields.io/github/stars/kijai/ComfyUI-champWrapper)<br>                                                                                             |
| [InvokeAI](https://github.com/invoke-ai/InvokeAI)<br>![GitHub Repo stars](https://img.shields.io/github/stars/invoke-ai/InvokeAI)<br>                                                              | 有画布功能，可以边画边生成，对专业一些的人来说非常适合的。                                                                                                         |                                                                                                     | [Invoke AI 4.0震撼发布!](https://www.bilibili.com/video/BV1Rr42147Rx)                                                                                                                                                                                             |
| [facefusion](https://github.com/facefusion/facefusion)<br>![GitHub Repo stars](https://img.shields.io/github/stars/facefusion/facefusion)<br>                                                      | 作者自认为是“下一代换脸工具”                                                                                                                       |                                                                                                     |                                                                                                                                                                                                                                                               |
| [ELLA](https://github.com/TencentQQGYLab/ELLA)<br>![GitHub Repo stars](https://img.shields.io/github/stars/TencentQQGYLab/ELLA)<br>                                                                | 让大语言模型LLM赋能AI绘画                                                                                                                       |                                                                                                     | [ComfyUI_ELLA](https://github.com/ExponentialML/ComfyUI_ELLA)<br>![GitHub Repo stars](https://img.shields.io/github/stars/ExponentialML/ComfyUI_ELLA)<br>                                                                                                     |
| [BrushNet](https://github.com/TencentARC/BrushNet)<br>![GitHub Repo stars](https://img.shields.io/github/stars/TencentARC/BrushNet)<br>                                                            | 原版局部重绘效果不错，但是comfyui移植的2个版本效果不是很好。                                                                                                    |                                                                                                     | 版本1[ComfyUI-BrushNet-Wrapper](https://github.com/kijai/ComfyUI-BrushNet-Wrapper)<br>版本2[ComfyUI-BrushNet](https://github.com/nullquant/ComfyUI-BrushNet)<br>                                                                                                  |
| [RVC变声](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)<br>![GitHub Repo stars](https://img.shields.io/github/stars/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)<br> | RVC，我视频用的变声器，(#^.^#)。                                                                                                                 | [下载地址](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI/releases)贴心的百度网盘，解压即用！ |                                                                                                                                                                                                                                                               |
| [Stable Diffusion 3](https://stability.ai/news/stable-diffusion-3-api?utm_source=twitter&utm_medium=website&utm_campaign=blog)                                                                     | 申请 API ：[Stability API key](https://platform.stability.ai/account/keys)<br>在线生成：[每日免费3张的在线网址](https://sdxlturbo.ai/stable-diffusion3) | [SD3 demo](https://huggingface.co/spaces/latentcat/sd3-api)                                         | [ComfyUI-StableDiffusion3-API](https://github.com/ZHO-ZHO-ZHO/ComfyUI-StableDiffusion3-API)                                                                                                                                                                   |
| [PixArt-sigma](https://github.com/PixArt-alpha/PixArt-sigma)<br>![GitHub Repo stars](https://img.shields.io/github/stars/PixArt-alpha/PixArt-sigma)<br>                                            | 华为诺亚方舟实验室、大连理工大学、香港大学合作开发的项目。<br>[亲测可用的简化安装教程](docs/PIXART-Σ基于扩散Transformer的弱到强训练方法,用于4K文本到图像生成.md)                                   | [PixArt-Sigma demo](https://huggingface.co/spaces/PixArt-alpha/PixArt-Sigma)                        | [ComfyUI_ExtraModels](https://github.com/city96/ComfyUI_ExtraModels)<br>📖[官方-如何在ComfyUI中使用PixArt](https://github.com/PixArt-alpha/PixArt-alpha/blob/master/asset/docs/pixart_comfyui.md)<br>工作流[12-PixArt-sigma](pysssss-workflows/12-PixArt-sigma.json)<br> |


# 🏆顶级开发者（他们贡献了最棒的custom nodes）

| 开发者                                                           | 简介（主要贡献）                                                                                                                                                                                                                                                                                                        |
| ------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ZHO-ZHO-ZHO](https://github.com/ZHO-ZHO-ZHO)                 | [BRIA_RMBG 1.4 in ComfyUI](https://github.com/ZHO-ZHO-ZHO/ComfyUI-BRIA_AI-RMBG)：BRIA 开发的目前最好的背景去除模型，已支持批量处理（可去除视频背景）<br>[ComfyUI InstantID](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID): 仅需一张图就可实现高质量的角色保持！多种风格随心变！<br>[ComfyUI-BiRefNet-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-BiRefNet-ZHO)背景扣除神奇！ |
| [kijai](https://github.com/kijai)                             | [ComfyUI-SUPIR](https://github.com/kijai/ComfyUI-SUPIR)<br>[ComfyUI-BrushNet-Wrapper](https://github.com/kijai/ComfyUI-BrushNet-Wrapper)<br>                                                                                                                                                                    |
| [ltdrdata](https://github.com/ltdrdata)<br>                   | [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager)<br> [ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)                                                                                                                                                                       |
| [lllyasviel](https://github.com/lllyasviel)                   | [Fooocus](https://github.com/lllyasviel/Fooocus)<br>[stable-diffusion-webui-forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)<br>[ControlNet](https://github.com/lllyasviel/ControlNet)<br>                                                                                                    |
| [HumanAIGC](https://github.com/HumanAIGC)<br>阿里               | 阿里的开源项目<br>[EMO](https://github.com/HumanAIGC/EMO)：情感肖像活灵活现<br>[AnimateAnyone](https://github.com/HumanAIGC/AnimateAnyone)：有了这个谁都可以跳科目三<br>[OutfitAnyone](https://github.com/HumanAIGC/OutfitAnyone)：换装，在线演示：[OutfitAnyone demo](https://huggingface.co/spaces/HumanAIGC/OutfitAnyone)<br>                      |
| [TencentARC](https://github.com/TencentARC)<br>腾讯             | [PhotoMaker](https://github.com/TencentARC/PhotoMaker)<br>[T2I-Adapter](https://github.com/TencentARC/T2I-Adapter)<br>[BrushNet](https://github.com/TencentARC/BrushNet)局部重绘很顶！                                                                                                                                 |
| [PKU-YUAN-Lab (袁粒课题组-北大信工)](https://github.com/PKU-YuanGroup) | [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan)北大出手还是牛。<br>[MagicTime](https://github.com/PKU-YuanGroup/MagicTime)<br>comfyui：[ComfyUI-MagicTimeWrapper](https://github.com/kijai/ComfyUI-MagicTimeWrapper)                                                                                   |

# ⬇️工作流、模型下载，社区交流、Youtube大佬

| 网址                                                              | 说明                                                                                      |     |
| --------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --- |
| [OpenArt](https://openart.ai/workflows)                         | 【工作流分享】很多大佬分享了海量的高质量工作流。                                                                |     |
| [civitai](https://civitai.com/)                                 | 【模型、工作流等】搜索、下载和分享各种 AI 绘画模型，最齐全的网站，好像没有之一？                                              |     |
| [Nerdy Rodent](https://www.youtube.com/@NerdyRodent/videos)     | 【Youtube大佬】手把手教你用命令行安装最新的AI项目                                                           |     |
| [Latent Vision](https://www.youtube.com/@latentvision/videos)   | 【Youtube大佬】[ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)的作者 |     |
| [Olivio Sarikas](https://www.youtube.com/@OlivioSarikas/videos) | 【Youtube大佬】做个SD和ComfyUI都能有20万粉丝！                                                        |     |

# 🌐图片、视频、音乐、3D模型、数字人…生成网站

| [ideogram](https://ideogram.ai/)                             | 这个网站生成的图片质量不错，可以生成文字。他们的模型也在不断迭代中。                                                       |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| [haiper](https://app.haiper.ai/explore)                      | 【生成视频】个人觉得生成的效果比什么[runway](https://runwayml.com/)、[pika](https://pika.art/)要好啊！就是2秒时间太短。 |
| [suno](https://app.suno.ai)<br>[udio](https://www.udio.com/) | 【生成音乐】音乐生成界的chatgpt？                                                                     |
|                                                              | 【生成音乐】                                                                                   |
| [heygen主页](https://app.heygen.com/home)<br>                  | 【数字人】一个云端视频创作平台，提供了视频编辑（**视频翻译**）、AI生成内容（**数字人**）、个性化定制、模板场景库等功能，适合各种背景和技能水平的用户使用。       |
| [Tripo3D](https://www.tripo3d.ai/)                           | 【生成3D模型】生成的3D模型效果挺不错的，在不断迭代中。                                                            |

# 💡小技巧

| 技巧                                                                      | 📺视频解说                                                                                                                |
| ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **1️⃣**[ComfyUI如何共享模型文件](docs/🔗ComfyUI如何共享模型文件.md)                     | [懒人必学!ComfyUI模型共享设置,省空间又省心!](https://www.bilibili.com/video/BV1Xt42177m8/?vd_source=7351bb1ce0a307c41b60b64ca036a240) |
| **2️⃣**[Windows环境下ComfyUI自定义节点安装指南](docs/Windows环境下ComfyUI自定义节点安装指南.md) | [ComfyUI报错的终极解决方案！](https://www.bilibili.com/video/BV1Up421Q7YA/?vd_source=7351bb1ce0a307c41b60b64ca036a240)          |

