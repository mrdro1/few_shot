# few_shot

Описание задач:

<strong>1. Эксперимент 1 - Английский язык - Дедлайн: 8 апреля</strong>
	- построить график зависимости roc_auc/количество примеров для класса
	- повторить эксперимент для разных эмбедеров

РЕЗУЛЬТАТЫ: 
- датасет: 20newsgroups
- эмбедеры: BERT, ELMO, universal-sentence-encoder
- метрика: средний roc_auc по классам 

Все реализации в папке eng

![alt text](https://github.com/mrdro1/few_shot/blob/master/plots/all.png)


<strong>2. Эксперимент 2 - Русский язык - Дедлайн: 22 апреля</strong>
	- реализовать ULMFIT для классификациии
	- построить график зависимости roc_auc/количество примеров для класса
	
РЕЗУЛЬТАТЫ: 
- датасет для LM: ria_news_dataset (https://github.com/RossiyaSegodnya/ria_news_dataset)
- датасет для классификации: Lenta.Ru-News-Dataset (https://github.com/yutkin/Lenta.Ru-News-Dataset)
- модель для классификации: bpe_30k->embedding->GRU_250->dense_100->dense_18
- метрика: средний roc_auc по классам 

Все реализации в папке rus

![alt text](https://github.com/mrdro1/few_shot/blob/master/plots/ulmfit.png)
