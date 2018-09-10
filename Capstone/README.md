# Capstone Project—— Predicting sales of Rossman stores

### 数据集在此处下载即可 https://www.kaggle.com/c/rossmann-store-sales/data
### 数据的内容大致为

* Id - 表示测试集中（存储，日期）副本的Id
* Store - 每个商店的独特Id
* Sales  - 任何一天的营业额（这是你预测的）
* Customers - 某一天的客户数量
* Open - 商店是否打开的指示器：0 =关闭，1 =打开
* StateHoliday - 表示一个国家假期。通常所有商店，除了少数例外，在国营假期关闭。请注意，所有学校在公众假期和周末关闭。 a =公众假期，b =复活节假期，c =圣诞节，0 =无
* SchoolHoliday - 表示（商店，日期）是否受到公立学校关闭的影响
* StoreType - 区分4种不同的商店模式：a，b，c，d
* Assortment - 描述分类级别：a = basic，b = extra，c = extended
* CompetitionDistance - 距离最接近的竞争对手商店的距离
* CompetitionOpenSince[Month/Year] ] - 给出最近的竞争对手开放时间的大约年和月
* Promo - 指示商店是否在当天运行促销
* Promo2 - Promo2是一些持续和连续推广的一些商店：0 =商店不参与，1 =商店正在参与
* Promo2自[年/周] - 描述商店开始参与Promo2的年份和日历周
* PromoInterval - 描述了Promo2的连续间隔开始，命名新的促销活动的月份。例如。 “二月，五月，八月，十一月”是指每一轮在该店的任何一年的二月，五月，八月，十一月份开始


## 文件说明

包含全部代码的notebook文件以及报告文件,其它csv文件为在测试集上的预测结果

## 用到的一些库以及其他说明

Python 2.7

用到了 [XGBoost](https://github.com/dmlc/xgboost), [Pandas](https://github.com/pydata/pandas) 和 [Scikit-learn](https://github.com/scikit-learn/scikit-learn)其它numpy，pandas ， matplotlib，seaborn，time


机器使用使用大约32G的RAM，处理器Intel(R) Xeon(R) CPU E5-2620 v2 @ 2.10GHz
