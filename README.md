<h3>Data Fusion Contest 2024 - Задача 2 «Отток». Публичное решение на Xgboost (Survival COX).</h3>
Еще один подход для решения задач Time-to-Event основанный на библиотеке Xgboost.<br>
Параметры:<br>
objective - survival:cox<br>
eval_metric - cox-nloglik и/или gamma-nloglik<br>
На LB данное решение дает > 0.77.<br><br>
Решение на  <a href='https://github.com/gogvan/dfc2024_task2' target='_blank'>RandomSurvivalForest</a><br>
Задача <a href='https://ods.ai/competitions/data-fusion2024-churn' target='_blank'>«Отток»</a><br><br>
PS. Дополнительные признаки дают на LB > 0.78<br>
