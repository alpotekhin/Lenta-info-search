* Данные -- ![новости Ленты](https://www.kaggle.com/datasets/yutkin/corpus-of-russian-news-articles-from-lenta)
* SnowBall стеммер
* Score основывается на cosine similarity Tdidf запроса и заголовка статьи
* Инвертированный индекс основан на алгоритме с указателями для поиска пересечений
* Датасет отсортирован по дате как оффлайн-признаку, так как у нас новости (к каждой новости также дописывается дата)
* В качестве метрики была подсчитана nDCG для небольшой выборки запрос-документ

![sample](https://github.com/alpotekhin/Sample-ML-Repo/blob/hw-infosearch/12.%20Info%20Search/inf_search_hw/gif/search%20sample.gif)
