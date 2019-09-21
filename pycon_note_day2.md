## Pycon -1080921 -Day2
## 1. [Keynote Programming Language Tourism: Leave Python and see the world! Paul Ivanov ]  R0
* New language:
	* idris
##
## 2. [Practicing Statistics in Python: Hypothesis Testing Mosky Liu] R2
* Noisy?
	* P-vaule是什麼？[P-value原理](https://medium.com/@chih.sheng.huang821/統計學-大家都喜歡問的系列-p值是什麼-2c03dbe8fddf)
	* 平均值解釋 -> 使用p-value -> 看是否在誤差範圍？
* Resources:
	* [視覺化機率](https://seeing-theory.brown.edu/bayesian-inference/index.html#section1)
	* [T-test Python 套件](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html)
	* [Flow Chart for Selecting Commonly Used Statistical Tests](http://abacus.bates.edu/~ganderso/biology/resources/stats_flow_chart_v2014.pdf)
##
## 3. [Getting started with sparse modeling using spm-image Takashi Someda] R1 
* Agenda
	* Sparse Modeling
	* image and time series data anaylsis
	* Guide to Python examples using spm-image
* Introduction of Sparse Modeling
	* Blackbox Problem -- AI cannot answer these qustions:
		* Why do it get the result?
		* Why this result?
		* How can it correct wrong result?
	* Approach to explainable AI
		* Post-hoc explain a given AI model
			* Individual prediction explainations
			* Global prediciton explainations
		* Build an interpretable model
			* Logisitic regression, Decision Trees
		* [Explainable AI](https://www.slideshare.net/KrishnaramKenthapadi/explainable-ai-in-industry-kdd-2019-tutorial)
* Lacking of missing data
	* Tiny dataset e.g. critical diseases
		* Data augmentation
		* Transfer Learning in Deep Learning
	* Missing values
		* Imputation of mean values, using regression
		* Use missing value friendly model
* History of Sparse Modeling
	* 1996 - start
* L0 and L1 norm optimization
* spm-image
* Compressed Sensing:
	* MRI pictures are blurred
##
## [Develop Numerical Software Yung-Yu Chen] R1
* Research code
	*Useful codes are usally in clear-code
* Niche
	* Merchandize, but the user base is tiny
	* Usually too expensive for personal to use
	* Long lifecyce, measured by decade, if surviving in the first place

