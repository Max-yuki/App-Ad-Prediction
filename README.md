# App-Ad-Prediction
App端广告转化率预估

此项目是基于帮助广告主跟踪在腾讯社交广告上投放广告后的转化效果的一个场景。以App为研究对象，预测App广告点击后被激活的概率。也就是给定广告、用户、和上下文的情况下，App广告被点后发生激活的概率。

---

### 数据说明

项目数据来源于社交广告系统，每个样本的 label 取值是 0 或 1, 0 表示点击后没转化，1 表示点击后有转化。
由于项目中的数据太大，就没有上传。数据可以点击[这里](http://pan.baidu.com/s/1gflA8T1)获取。


### 用到的模型

逻辑回归（LR）、随机森林（RF）、Xgboost


### 用到的库

pandas、numpy、scipy、sklearn、matplotlib、xgboost、blagging

