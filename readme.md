## 分析世界孕产妇死亡率变换情况与原因

### 项目目的：
* 通过数据挖掘分析世界孕产妇死亡率变换情况与原因，给相关慈善关怀机构及有关部门提供相应的目标引导建议。
### 背景和意义：
* 孕妇作为社会的弱势群体，同时承担着人类传承的重任，需要得到全社会的关爱。改善孕产妇健康是国际社会于2000年通过的八个千年发展目标中的一个，孕产妇死亡率作为人群医疗健康水平的敏感指标, 其变化状况不仅反映了全民医疗健康水平, 更在一定程度上反映当地妇女儿童权益的保障情况。
* 每年约有100万儿童因为妊娠或分娩有关的并发症而失去母亲。这些儿童在其母亲死亡之后一两年内死亡的可能性更高。
* 此项研究工作有助于解决孕产妇卫生保健服务获取和质量方面的不平等问题，降低孕产妇死亡率。

### 数据来源：
* World bank
* API获取
### 项目分析
* 收集世界各国有关项目数据
* 挖掘数据故事、优化数据交互
* 利用flask实现PYTHON的数据传输
### 项目目标
* 成最小可行的交互式数据可视化产品设计，做出PRD及至少有2份成功交互且交互意义相关连（以超连结或交互达成）的交互式界面（其中至少1份含地图）的产品原型或完整产品，包括使用相关Pyecharts及/或Plotly模块等等的整合外观样式及数据科学代码实践，以及外观样式的前端CSS及Javascript库调用实践（如Bootstrap）
### 项目数据
- [在熟练医护人员护理下的分娩（占总数的百分比）](https://data.worldbank.org.cn/indicator/SH.STA.BRTC.ZS)
- [孕妇贫血患病率(%)](https://data.worldbank.org.cn/indicator/SH.PRG.ANEM)
- [接受产前护理的孕妇（百分比）](https://data.worldbank.org.cn/indicator/SH.STA.ANVC.ZS)
    - 接受产前护理的孕妇是在妊娠期因妊娠相关原因而至少经熟练的医务人员护理过一次的孕妇的百分比。
- [避孕普及率（占 15–49 岁女性的百分比）](https://data.worldbank.org.cn/indicator/SP.DYN.CONU.ZS)
  
[孕产妇死亡率（模型估计值，每10万例活产中所占比例）](https://data.worldbank.org.cn/indicator/SH.STA.MMRT)
