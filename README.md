
![示例](https://raw.githubusercontent.com/Orz-3/mini/none/头部.png)

## mini项目

本项目诞生之初是为了适配Quantumult X 1.07版本新增的机场订阅img-url特性，经过不断发展，包含了机场订阅图标，Task图标，节点地区图标，策略组图标等

本项目可用于QuantumultX 1.07及以上版本，和Pharos Pro 1.3.3及以上版本中

**注意：** 本项目图标可用于订阅，Task，策略组等位置的远程引用

##### Telegram频道： [mini计划-图标聚合](https://t.me/Orzmini)

### Quantumult X使用方法：

####  1、订阅链接中引用
  
  打开QuanX 配置文件-编辑，找到［server_remote］字段，在想要增加图标的相应订阅中修改，在enable＝true之前加上
  `img-url=https://raw.githubusercontent.com/Orz-3/mini/master/name.png`
  注意此句和前后句都要用英文逗号隔开，并且逗号后先要空一格
  

  **完整示例：**`https://raw.githubusercontent.com/crossutility/Quantumult-X/master/server-complete.txt, tag=Sample-02, as-policy=static, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/name.png, enabled=false`

####  2、策略组引用
  
  **2.1** 如果通过as-policy生成策略组，会直接引用和订阅链接字段同样的图标，且无法更改
  
  **2.2** 如果通过UI生成策略组，或者想直接在策略组中使用本项目图标，请打开QuanX 配置文件-编辑，找到［policy］字段，并在相应策略组中末尾，加上`img-url=https://raw.githubusercontent.com/Orz-3/mini/master/name.png`  注意同样要用英文逗号与前面句子隔开，并在逗号后面空一格

  **完整示例：**`static=policy-name-1, Sample-A, Sample-B, Sample-C, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/name.png`
  
### Pharos Pro使用方法：

  在Pharos Pro主页对应订阅上左滑，点击编辑，在弹出界面的图标一栏中填入 `https://raw.githubusercontent.com/Orz-3/mini/master/name.png`
  
### task图标使用方法：

####  1、文本编辑中使用
打开QuanX 配置文件-编辑，找到［task_local］字段，在想要增加图标的相应签到脚本段落中修改，在enable＝true之前加上 `img-url=https://raw.githubusercontent.com/Orz-3/mini/master/name.png` 注意此句和前后句都要用英文逗号隔开，并且逗号后先要空一格

####  2、UI中使用
主界面右下角点击风车开启菜单，然后找到调试一栏下的构造请求，点击进入构造请求界面，左滑相应task，点击编辑，在图标一栏填写 `https://raw.githubusercontent.com/Orz-3/mini/master/name.png`

🔘彩色版本 `https://raw.githubusercontent.com/Orz-3/task/master/name.png`

🔘透明版本 `https://raw.githubusercontent.com/Orz-3/mini/master/name.png`

  **注：** task图标的透明和彩色版本文件名完全一致，仅所在库不同

##### 图标索引，最上方为图标展示，下面第一行为对应机场的名称，第二行为文件名，请将使用方法中的name.png替换成相应文件的文件名

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/机场.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/2.5-1.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/2.5-2.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/2.5-3.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/2.5-4.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/2.5-5.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/彩蛋.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/2.5-彩蛋.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/策略.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/策略1.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/策略2.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/策略3.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/策略4.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/地区.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/地区1.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/地区2.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/地区3.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/Task.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/-1.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/-2.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/-3.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/-4.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/-5.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/-6.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/-7.png)

![示例](https://raw.githubusercontent.com/Orz-3/mini/none/yaofan.png)
