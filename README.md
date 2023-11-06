## {What is the problem}  

The machine learning algorithms and statistical models have evolved tremendously along with the exponential advancement in the capacity of the computation power. Many models have been build developed and widely used. But because of the previous available research, which established the modus oparandi of the future direction, there are many serious lacks in the developed models.

Around AD 1700, when the regression was in primary stage, the scholars mostly focused on the developing and estimating the model w, revolve around the mean value. The later subsequent development led in deriving least square method and the conditional mean phenomenon was well established since then, which exhibits profound efficiency for predicting and analysing the pattern focused on mean, resulting in widespread use.

But while dealing with financial data, or natural calamities like flood, earthquake, disease prediction, crime rate etc, its not the mean behaviour which of our interest, but the extreme behaviour of such event. To model such pattern we need to execute the different methodology than the one base on the mean, called as parametric models. Using non-parametric models was never been a easy task given the tedious nature and the confusing interpretation. But it promised a good deal while addressing such extreme pattern.

##  Why you

I was always fascinated by the predictive models in statistics, and have intensively studied it. It was quite apparent in my bachelor and master thesis, which both deal with predictive methodology, the later especially focused on computer vision. . Also, in my freelancing work I have assisted on several such project, which has enriched my exposure to wide range of data and the execution.



## What is the impact

Such methodology promises a great deal of application in field which generates skewed data, including stock prediction, disease outbreak, natural disaster, meteriological data etc. Also, proposing a new models in non-parametric domain will give a foundation for developing the new statistical validation, like inference , hypothesis testing and evaluation metrics. Given the many facet application , dire need alternative methodody and to use avaialable computational capability, such models are the need of hour.






##proposal
shreyashs.deshmukh23
October 2023
## 1 Problem Statement
Time series data frequently exhibit unexpected and irregular spikes, impacting
a wide array of applications including finance, energy consumption, disease outbreaks, meteorological events, healthcare, and anomaly detection. These sudden
spikes can be triggered by various factors, such as unforeseen events, anomalies,
or underlying patterns. The ability to accurately forecast the timing of these
spikes is very importance for proactive decision-making and effective risk mitigation. However, there is a conspicuous gap in currently available methodologies
for the precise prediction of upper quantiles, essential for assessing extreme
events. Existing statistical and machine learning approaches often fall short in
addressing the nuances of such spikes, especially in dealing with outliers and
providing a comprehensive understanding of the conditional distribution’s tail
behaviour.
To address this critical need, we propose the application of a Quantile regressionbased approach, which leverages its intrinsic strengths. This method can help in
handling outliers and extreme values, demonstrating robustness against extreme
data points, and facilitating the characterization of conditional distributions.
Additionally, it offers a mechanism for quantifying uncertainty and exploring
the tail behaviour of time series data, making it an effective anomaly detection tool. To operationalize this approach, we will develop a predictive model
based on Quantile Autoregression (QAR) specifically tailored to forecast and
comprehend the occurrence of spikes in time series data. The application of
QAR promises a deeper understanding of extreme events and their underlying
dynamics and precise prediction, thereby enabling more effective strategies for
risk mitigation and response.
2 Literature Review
Identification and prediction of high values in time series is of paramount importance for economist, epidemiologist and other social scientist, caused by some
exogeneous factors. There is no single best method for detecting such spikes in
time series data, Goin and Ahern (2019) have compared different approaches
1(ARIMA modeling, Kalman filtering and smoothing, wavelet modeling, and outlier detection) in search of the most effective one, using simulated data. It is
found that the Kalman filtering and smoothing method demonstrates the best
overall performance, particularly in detecting large spikes. Various modelling
approaches have been explored to predict higher values in disease-related time
series data, particularly in the context of dengue incidence prediction. Lu et al.
(2009) employed Poisson regression with generalized estimating equations, using
monthly data from 2001 to 2006. They selected the best-fitting model based
on the Quasi-Likelihood Information Criterion (QICu), considering correlations
between dengue incidence and weather variables with lags of up to three months.
Husin et al. (2012)introduced hybrid models using a genetic algorithm, analyzing data from five districts in Malaysia over two years. Although the accuracy
assessment was limited, the hybrid model outperformed non-linear regression
and artificial neural network (ANN) approaches.Nishanthi et al. (2014) applied
an ANN approach with the Levenberg–Marquardt algorithm, using weekly data
from a single district over three years. Their evaluation revealed challenges in
pred icting higher dengue cases during peak periods. Long Short-Term Memory (LSTM) has gained popularity recently. Xu et al. (2020) used LSTM with
other models for a 13-year monthly dataset, demonstrating superior accuracy
with transfer learning.Edussuriya et al. (2021) applied LSTM to data from 19
districts over ten years, optimizing hyperparameters with the Grey Wolf algorithm and achieving low RMSE.Datoc et al. (2016) showed that neural networks
trained on average weather parameters outperformed individual monthly data
for disease prediction in Visayas Island (2010-2015). However, the model struggled to predict peak events accurately.
Quantile regression models have gained traction for assessing conditional relationships at various percentiles of response variable distributions, with applications in finance, epidemiology, and energy consumption modeling.
Quantile auto-regression (QAR) models have garnered attention for modeling conditional quantiles of time series data. Chevapatrakul and Mascia (2019)
studied Bitcoin return patterns using QAR(1) and found that investors overreact to sharp declines and push prices further during high returns. Zhao et al.
(2021) used the Quantile Partial Autocorrelation Function (QPACF) to generate superior out-of-sample volatility forecasts for financial assets compared to
traditional models. ) Lima et al. (2008) proposed a novel QAR-based methodology for investigating the long-term sustainability of public debt, while Pal and
Mitra (2017) applied quantile autoregressive distributed lag models to study
price relationships between diesel and soybean. Asymmetric price transmission
from diesel to soybean was observed, with soybean prices varying across quantiles in response to diesel price fluctuations. These studies collectively showcase
the potential of neural networks and quantile regression in enhancing predictive
accuracy for diverse disease-related scenarios and challenges in time series data
analysis.
2References
Thanaset Chevapatrakul and Danilo V Mascia. Detecting overreaction in the
bitcoin market: A quantile autoregression approach. Finance Research Letters, 30:371–377, 2019.
Hillary Ingrid Datoc, Romeo Caparas, and Jaime Caro. Forecasting and data
visualization of dengue spread in the philippine visayas island group. In
2016 7th International Conference on Information, Intelligence, Systems &
Applications (IISA), pages 1–4. IEEE, 2016.
Chathurangi Edussuriya, Sampath Deegalla, and Indika Gawarammana. An
accurate mathematical model predicting number of dengue cases in tropics.
PLoS Neglected Tropical Diseases, 15(11):e0009756, 2021.
Dana E Goin and Jennifer Ahern. Identification of spikes in time series. Epidemiologic Methods, 8(1):20180005, 2019.
Nor Azura Husin, Norwati Mustapha, Md Nasir Sulaiman, and Razali Yaakob.
A hybrid model using genetic algorithm and neural network for predicting
dengue outbreak. In 2012 4th Conference on data mining and optimization
(DMO), pages 23–27. IEEE, 2012.
Luiz Renato Lima, Wagner Piazza Gaglianone, and Raquel MB Sampaio. Debt
ceiling and fiscal sustainability in brazil: a quantile autoregression approach.
Journal of Development Economics, 86(2):313–335, 2008.
Liang Lu, Hualiang Lin, Linwei Tian, Weizhong Yang, Jimin Sun, and Qiyong
Liu. Time series analysis of dengue fever and weather in guangzhou, china.
BMC Public Health, 9:1–5, 2009.
PHM Nishanthi, AAI Perera, and HP Wijekoon. Prediction of dengue outbreaks
in sri lanka using artificial neural networks. International Journal of Computer
Applications, 101(15), 2014.
Debdatta Pal and Subrata K Mitra. Diesel and soybean price relationship in the
usa: evidence from a quantile autoregressive distributed lag model. Empirical
Economics, 52:1609–1626, 2017.
Jiucheng Xu, Keqiang Xu, Zhichao Li, Fengxia Meng, Taotian Tu, Lei Xu, and
Qiyong Liu. Forecast of dengue cases in 20 chinese cities based on the deep
learning method. International journal of environmental research and public
health, 17(2):453, 2020.
Yixiu Zhao, Vineet Upreti, and Yuzhi Cai. Stock returns, quantile autocorrelation, and volatility forecasting. International Review of Financial Analysis,
73:101599, 2021.
3
