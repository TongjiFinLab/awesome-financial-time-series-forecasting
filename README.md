[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/TongjiFinLab/awesome-financial-time-series-forecasting) 

# Awesome Financial Time Series Forecasting Papers and Codes


+ **Update**: This repository is actively updated.  `2024/9/5`
+ **Collection**: We've compiled a comprehensive list of awesome financial time series forecasting papers and codes.
+ **Collaborate**: If there’s anything missing or if you'd like to contribute, please don't hesitate to get in touch!

## Contents

+ [LLM-based Financial Time Series Forecasting Models](#LLM-based-Financial-Time-Series-Forecasting-Models)
+ [Graph Neural Network-based Models](#Graph-Neural-Network-based-Models)
+ [Transformer-based Models](#Transformer-based-Models)
+ [Generative Methods based Models](#Generative-Methods-based-Models)
+ [Classical Time Series Models](#Classical-Time-Series-Models)
+ [Quantitative Open Sourced Framework](#Quantitative-Open-Sourced-Framework)
+ [Survey](#Survey)


## LLM-based Financial Time Series Forecasting Models

**Multi-Patch Prediction: Adapting Language Models for Time Series Representation Learning** 

*Yuxuan Bian, Xuan Ju, Jiangtong Li, Zhijian Xu, Dawei Cheng, Qiang Xu* 

ICML 2024. [[Paper](https://openreview.net/forum?id=Rx9GMufByc)] | [[Codes](https://github.com/yxbian23/aLLM4TS)]


**LLMFactor: Extracting Profitable Factors through Prompts for Explainable Stock Movement Prediction**

*Meiyun Wang, Kiyoshi Izumi, Hiroki Sakaji*

ACL 2024. [[Paper](https://aclanthology.org/2024.findings-acl.185.pdf)]


**MOMENT: A Family of Open Time-series Foundation Models**

*Mononito Goswami, Konrad Szafer, Arjun Choudhry, Yifu Cai, Shuo Li, Artur Dubrawski*

ICML 2024. [[Paper](https://arxiv.org/abs/2402.03885)] | [[Codes](https://github.com/moment-timeseries-foundation-model/moment)]


**Timer: Transformers for Time Series Analysis at Scale**

*Yong Liu, Haoran Zhang, Chenyu Li, Xiangdong Huang, Jianmin Wang, Mingsheng Long*

ICML 2024. [[Paper](https://arxiv.org/abs/2402.02368)] | [[Codes](https://github.com/thuml/Large-Time-Series-Model)]

**Unified Training of Universal Time Series Forecasting Transformers**

*Gerald Woo, Chenghao Liu, Akshat Kumar, Caiming Xiong, Silvio Savarese, Doyen Sahoo*

ICML 2024. [[Paper](https://arxiv.org/abs/2402.02592)] | [[Codes](https://github.com/redoules/moirai)]

**Are Language Models Actually Useful for Time Series Forecasting?**

*Mingtian Tan, Mike A. Merrill, Vinayak Gupta, Tim Althoff, Thomas Hartvigsen*

Arxiv 2024. [[Paper](https://arxiv.org/abs/2406.16964)]

**TIME-LLM: TIME SERIES FORECASTING BY REPROGRAMMING LARGE LANGUAGE MODELS**

Arxiv 2024. [[Paper](https://arxiv.org/abs/2406.16964)]

*Ming Jin, Shiyu Wang, Lintao Ma, Zhixuan Chu, James Y. Zhang, Xiaoming Shi, Pin-Yu Chen, Yuxuan Liang, Yuan-Fang Li, Shirui Pan, Qingsong Wen*

ICLR 2024. [[Paper](https://arxiv.org/abs/2310.01728v1)] | [[Codes](https://github.com/KimMeen/Time-LLM)]

## Graph Neural Network-based Models

**MDGNN: Multi-Relational Dynamic Graph Neural Network for Comprehensive and Dynamic Stock Investment Prediction**

*Hao Qian, Hongting Zhou, Qian Zhao, Hao Chen, Hongxiang Yao, Jingwei Wang, Ziqi Liu, Fei Yu, Zhiqiang Zhang, Jun Zhou*

AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/29381)]

**ECHO-GL: Earnings Calls-Driven Heterogeneous Graph Learning for Stock Movement Prediction**

*Mengpu Liu, Mengying Zhu, Xiuyuan Wang, Guofang Ma, Jianwei Yin, Xiaolin Zheng*

AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/29305)] | [[Codes](https://github.com/pupu0302/ECHOGL)]

**TCGPN: Temporal-Correlation Graph Pre-trained Network for Stock Forecasting**

*Wenbo Yan, Ying Tan*

[[Paper](https://arxiv.org/abs/2407.18519)]

**Temporal and Heterogeneous Graph Neural Network for Financial Time Series Prediction**

*Sheng Xiang, Dawei Cheng, Chencheng Shang, Ying Zhang, Yuqi Liang*

AAAI 2024. [[Paper](https://arxiv.org/abs/2305.08740)] | [[Codes](https://github.com/finint/THGNN)]

**Hierarchical Adaptive Temporal-Relational Modeling for Stock Trend Prediction**

*Heyuan Wang, Shun Li, Tengjiao Wang, Jiayi Zheng*

IJCAI 2021. [[Paper](https://www.ijcai.org/proceedings/2021/508)] | [[Codes](https://github.com/lixiaojieff/HGTAN)]

**REST: Relational Event-driven Stock Trend Forecasting**

*Wentao Xu, Weiqing Liu, Chang Xu, Jiang Bian, Jian Yin, Tie-Yan Liu*

WWW 2021. [[Paper](https://arxiv.org/abs/2102.07372)]


## Transformer-based Models

**MASTER: Market-Guided Stock Transformer for Stock Price Forecasting**

*Tong Li, Zhaoyang Liu, Yanyan Shen, Xue Wang, Haokun Chen, Sen Huang*

AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27767)] | [[Codes](https://github.com/SJTU-DMTai/MASTER)]

**CI-STHPAN: Pre-trained Attention Network for Stock Selection with Channel-Independent Spatio-Temporal Hypergraph**

*Hongjie Xia, Huijie Ao, Long Li, Yu Liu, Sen Liu, Guangnan Ye, Hongfeng Chai*

AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28770)] | [[Codes](https://github.com/Harryx2019/CI-STHPAN)]

**Learning Multiple Stock Trading Patterns with Temporal Routing Adaptor and Optimal Transport**

*Hengxu Lin, Dong Zhou, Weiqing Liu, Jiang Bian*

KDD 2021. [[Paper](https://arxiv.org/abs/2106.12950)] | [[Codes](https://github.com/microsoft/qlib/tree/main/examples/benchmarks/TRA)]



## Generative Methods based Models

**DiffsFormer: A Diffusion Transformer on Stock Factor Augmentation**

*Yuan Gao, Haokun Chen, Xiang Wang, Zhicai Wang, Xue Wang, Jinyang Gao, Bolin Ding*

[[Paper](https://arxiv.org/abs/2402.06656)]

**FactorVAE: A Probabilistic Dynamic Factor Model Based on Variational Autoencoder for Predicting Cross-Sectional Stock Returns**

*Yitong Duan, Lei Wang, Qizhong Zhang, Jian Li*

AAAI'22. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20369)] | [[Codes](https://github.com/harrishe1999/FactorVAE)]


## Classical Time Series Models

**Learning connections in financial time series**

*Ganeshapillai, Gartheeban, John Guttag, and Andrew Lo.*

ICML 2013. [[Paper](http://proceedings.mlr.press/v28/ganeshapillai13.pdf)] | [[Codes]()]


## Quantitative Open Sourced Framework

**RD-Agent: Autonomous evolving agents for industrial data-drive R&D**

*Microsoft Research Asia*

$2024$. [[Codes](https://github.com/microsoft/RD-Agent)]

**Qlib: An AI-oriented Quantitative Investment Platform**

*Microsoft Research Asia*

$2021$. [[Paper](https://arxiv.org/abs/2009.11189)] | [[Codes](https://github.com/microsoft/qlib)]


## Survey

**Stock Market Prediction via Deep Learning Techniques: A Survey**

*Jinan Zou, Qingying Zhao, Yang Jiao, Haiyao Cao, Yanxi Liu, Qingsen Yan, Ehsan Abbasnejad, Lingqiao Liu, Javen Qinfeng Shi*

$2023$. [[Paper](https://arxiv.org/abs/2212.12717)]



## All Thanks to Our Contributors :

<a href="https://github.com/TongjiFinLab/awesome-financial-time-series-forecasting/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=TongjiFinLab/awesome-financial-time-series-forecasting" />
</a>
