# unraid
MT Photos unraid 模板库

### 使用方法

#### 添加模板库

打开 unraid 的 docker 页面：

1. 将本仓库地址 https://github.com/MT-Photos/unraid 填入 **Template repositories**
2. 点击 SAVE 保存，等待 unraid 自动拉取模板库并刷新页面 （如果添加失败，请检查网络是否能打开github.com）

![添加模板库](img/add-template.png)


#### 添加容器

在 Unraid 自动刷新页面之后，点击 **ADD CONTAINER** 添加容器

![添加容器](img/add-container.png)

点击 **select a template** 展开下拉菜单，并选中 **MT Photos** 

![选择模板](img/select-template.png)

#### 配置容器

选中之后会自动跳转到预设的配置页面，按照对应的要求填写配置参数：

1. 修改数据存储、App备份文件目录地址
2. 如果还有其他的照片目录，点击 【+ Add another Path, Port, Variable, Label or Device】添加目录；

填完参数后，点击 **APPLY** 

![添加容器](img/edit-path.png)

等待unraid拉取镜像，并启动运行
