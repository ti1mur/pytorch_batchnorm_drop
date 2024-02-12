# pytorch_batchnorm_drop
Данный репозиторий является выполнением семинара на курсе от МФТИ: 

https://www.youtube.com/watch?v=Y9a5EfqM7RM&list=PL0Ks75aof3Tiru-UvOvYmXzD1tU0NrR8V&index=42

Представлены несколько моделей с разными видами регуляризации: Batchnorm, Dropout, LR scheduling.

Реализованы:
  1. def get_loaders - загрузка данных.
  2. def fit - train loop.
  3. class Model, class ModelBatchNorm, class ModelDropout - различные модели с разными видами регуляризации.
