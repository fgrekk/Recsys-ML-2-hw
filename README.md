# HW Recsys ML-2

В работе я проверил User2User, LFM(ALS и SGD), бустинговые модели(СatBoostClassifier, CatBoostRanker) на метрике MAP@20. Также я перебирал гиперпараметры для каждой модели

|Качество| Valid MAP@20| Test MAP@20|
|---|---|---|
|User2User|0.001813|0.000240|
|LFM|0.000226|0.001228|
|СatBoostClassifier|0.007520|0.006699|
|CatBoostRanker|0.005660|0.006343|
