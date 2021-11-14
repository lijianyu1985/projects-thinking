## 技术栈
选什么技术栈不重要，只要能实现功能的话，使用任何技术都是可行的，但是考虑到人才和技术社区的情况还是要根据技术市场做最后的决定，建议选择一个成长型的技术社区和技术体系

### 后端
* Asp.net Core
* NestJs
* MongoDB
* Docker
* 阿里云
* 基于微服务架构思维可以不用太考虑具体的后端语言，但是考虑到团队的协同统一建议使用同一种语言，首选NestJS

### 前端
* uni-app
* taroJS
* Angular
* VueJs
* React
* Ionic Framwork
* 必须实现微信、字节、快手小程序，APP可以不考虑但是小程序必须要做，H5优先级居中，建议使用uni-app+某响应式布局库

## 项目列表（商品）
每类型项目具有通用的业务结构但是又具有差异化的自有强业务，建议将项目分为几个大类，每个大类共享一套代码，各个大类之间只共享通用代码类库（例如支付模块，用户模块），大类中不同小类项目使用不同的分支做差异化，另外有一个主分支维护主体通用代码。（Note: 另外同一个小类的项目又要做UI差异化，建议前期考虑如何以最小代价做UI差异化，实现一个方便替换资源和主题的前端架构）

### 商品类
* 花店
* 超市便利店
* 水果店
* 蔬菜店
* 药店
* 等等

### 预约服务类
* 房地产
* 旅游
* 酒店
* 住宿
* 等等

### 到店服务类
* 瑜伽店
* 修车店
* 按摩店
* 美容店
* 等等

## 架构
不同阶段可以采取不同的架构，根据团队的情况，资金的情况，市场的情况综合考量，选用最合适最低廉成本的架构才是正确的选择，不建议前期投入太多做技术积累，也要切记后期要有足够的决心和毅力做架构重构。前期可以用单实例部署的方式快速成长，在成长到某个阶段（资金积累、技术积累、业务积累达到某个程度）考虑系统SAAS化

### SAAS
* +部署成本低
* +统一升级方便
* -开发成本高
* -差异化困难
* : 前期成本很高，但是后期优点明显，统一的代码会让统一管理非常方便，非常方便长期发展，越到后期优点越多

### 单实例部署
* +开发简单
* +方便做差异化开发
* -综合部署成本略高
* -统一升级成本高且困难
* : 前期成本低且响应快速，后期维护成本剧增，几乎难以统一维护，不适合长期发展，越到后面越是困难
