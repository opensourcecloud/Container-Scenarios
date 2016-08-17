Container典型场景
=======
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">opensourcecloud-specification</span> 由 <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/organizations/opensourcecloud/" property="cc:attributionName" rel="cc:attributionURL">OSCAR</a> 创作，采用 <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享 署名-非商业性使用-相同方式共享 4.0 国际 许可协议</a>进行许可。<br />基于<a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/organizations/opensourcecloud/" rel="dct:source">https://github.com/organizations/opensourcecloud/</a>上的作品创作。

### 修改说明

- 1. 保留license协议
- 2. 依次增加需求，或对已有需求进行修改
- 3. 修改请在summary或description中说明公司和作者或者匿名，admin（Leader）或write（core）将把作者补充到文档最前面


--------------------------------
## 前言：本文档要讨论的内容：

- Container典型使用场景
- Container案例
- Container特点和需要改进的地方

## Container典型使用场景：

### 开发测试环境交付
#### 选择应用开发需要的基于容器的服务组件
开发人员可以从服务目录选择应用开发需要的各类软件，从编程语言、数据库、消息中间件、其它各种需要的软件。

#### 组合服务组件，形成应用
将多个服务组合成应用后，开始自动部署，并形成一个应用。

#### 开发数据库交付
应用开发需要的数据库在部署阶段能够自动提供，方便开发。

##### 数据库帐号、实例、库或表空间的自动化交付
应用创建完成，应自动交付开发所需要的账号密码，以及库或者表空间。

##### 数据导入或者录入
应支持数据导入或录入的手段，方便开发过程的调试。比如:

- 从浏览器上传导入
- 从数据库管理面板导入或录入

#### 代码发布和调试
应能过支持将单个文件或多个文件批量发布到容器里，方便开发人员的调试。

#### 打包用于测试环境的发布
完成到某一里程碑时，将应用代码打成容器镜像包，用于测试人员的功能测试

#### 分享环境给测试人员
将基于容器的环境整体保存起来并分享给测试人员。

#### 一键部署测试环境
测试人员利用开发交付的环境，一键在测试服务器上部署起测试环境。

#### 测试环境销毁
测试完成后，将环境一键彻底销毁，包括容器、数据。

### 持续集成持续交付
为了提升开发测试的自动化水平，以及流水线的交付，持续集成持续交付深入人心。容器的出现，使得过去的持续交付技术，能够有一个更加有效的方式进行。所以目前在持续集成持续交付方面的使用已经非常流行。

#### 支持代码仓库的签出
能够支持标准的SVN、Git协议，支持将对应的应用代码自动签出，并能够支持tag、分支等选择。

#### 支持通过容器的方式构建容器镜像包
需要能够将应用代码自动构建成镜像，用于发布。

#### 支持自动的应用发布升级
需要能够支持将原有版本的应用环境自动升级到当前版本。

## 运维自动化场景

## 微服务


##二、Container案例

###1.公司、场景、部署、效果

## 三、Container特点和需要改进的地方

###1. xxxxx
