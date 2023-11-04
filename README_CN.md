# 投影在线预览

用于预览投影文件(.litematic)的（静态？）网页

预期使用的开源库：

https://github.com/misode/deepslate

https://github.com/EndingCredits/litematic-viewer

预期实现的功能：

- 静态网页，实现投影文件的上传、校验、nbt分析
- 使用原版材质渲染投影文件模型，实现各种预览功能

未来想要实现的功能：

- 与nonebot2框架进行联动，用户输入上传指令，协议端(onebot11, kook等)检测到上传文件时，将文件作为输入，导入到网页中进行相应处理操作后，向用户返回相应的预览地址
- 支持用户上传自定义资源包，对渲染模型的材质进行替换