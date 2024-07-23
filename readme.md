# Live2D_API


## 使用 How to use

你可以使用`jsdelivr`与`npm`镜像节点来为你的网站引入相关文件，根据引入文件的不同决定你的看板娘的位置与模型材质切换方式。

1. 使用`zzko-jsdelivr`引入。

   ```html
   <!-- 顺序切换模型材质 -->
   <script src="https://jsd.cdn.zzko.cn/gh/nova1751/live2d-api@latest/jsdelivr/sequential/autoload.min.js"></script>
   <!-- 随机切换模型材质 -->
   <script src="https://jsd.cdn.zzko.cn/gh/nova1751/live2d-api@latest/jsdelivr/random/autoload.min.js"></script>

   <!-- 看板娘位置靠左 -->
   <link
     rel="stylesheet"
     href="https://jsd.cdn.zzko.cn/gh/nova1751/live2d-api@latest/css/left.min.css"
   />
   <!-- 看板娘位置靠右 -->
   <link
     rel="stylesheet"
     href="https://jsd.cdn.zzko.cn/gh/nova1751/live2d-api@latest/css/right.min.css"
   />
   ```

2. 使用国内`npm`镜像节点引入。

   ```html
   <!-- 顺序切换模型材质 -->
   <script src="https://unpkg.com/live2dapi-noa@latest/npm/sequential/autoload.js"></script>
   <!-- 随机切换模型材质 -->
   <script src="https://unpkg.com/live2dapi-noa@latest/npm/random/autoload.js"></script>

   <!-- 看板娘位置靠左 -->
   <link
     rel="stylesheet"
     href="https://unpkg.com/live2dapi-noa@latest/css/left.css"
   />
   <!-- 看板娘位置靠右 -->
   <link
     rel="stylesheet"
     href="https://unpkg.com/live2dapi-noa@latest/css/right.css"
   />
   ```


2. 修正了部分模型语音与互动动作配置错误。
3. 将左右的`css`文件分别配置，添加顺序切换模型材质的`js`文件，并将随机切换与顺序切换的`js`文件分别配置。
