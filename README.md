# python-handbook
记录一些python的使用小tips

---
# 目录
* 函数
  * [`apply()`, `applymap()`, `map()`](https://blog.csdn.net/qq_42665335/article/details/81213175)
  * [`itertools`操作迭代对象如排列组合等等](https://docs.python.org/3/library/itertools.html#itertools.combinations)
* pandas
  * `.sub()`
  * `.clip()`
  * [`.reset_index()`, `.set_index()`](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.reset_index.html?highlight=reset_index#pandas.DataFrame.reset_index)
  * [`.sort_index()`](https://blog.csdn.net/qq_30638831/article/details/79835523)
  * [`pd.get_dummies()`生成哑变量](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.get_dummies.html?highlight=get_dummies#pandas.get_dummies)
  * [[]]索引得到的是dataframe，而[]索引得到的是series
  * [`.drop_duplicates()`去掉重复的行](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.drop_duplicates.html?highlight=drop_dupli#pandas.DataFrame.drop_duplicates)
  * [根据各种数据类型构造df](https://pandas.pydata.org/pandas-docs/stable/getting_started/dsintro.html#from-dict-of-series-or-dicts)
* numpy
  * [`numpy.linalg`线性代数包](https://numpy.org/devdocs/reference/routines.linalg.html)
  * [`np.identity()`单位阵](https://numpy.org/devdocs/reference/generated/numpy.identity.html?highlight=identity#numpy.identity)
* seaborn
  * [`sns.heatmap()`热力图](https://seaborn.pydata.org/generated/seaborn.heatmap.html?highlight=heatmap#seaborn.heatmap)
* datetime
  * [`strftime()`, `strptime()`](https://docs.python.org/3/library/datetime.html#strftime-and-strptime-behavior)
* statsmodels
  * [`sm.add_constant()`添加常数项](http://www.statsmodels.org/stable/generated/statsmodels.tools.tools.add_constant.html?highlight=add_constant#statsmodels.tools.tools.add_constant)
