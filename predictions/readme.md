В этой папке лежат получившиеся у моделей предсказания степени семантического сдвига целевых слов для каждой пары эпох (мы использовали меру **косинусного расстояния**):

1. Досоветская VS Советская
2. Совесткая VS Постсоветская
3. Досоветская VS Постсоветская

- `prediction_bert.tsv` -- предсказания "большого" BERT `DeepPavlov/rubert-base-cased`
- `prediction_bert_tiny.tsv` -- предсказания "маленького" BERT `cointegrated/rubert-tiny2`
- `prediction_chat.tsv` -- предсказания GigaChat
- `prediction_ensemble.tsv` -- предсказания Word2Vec, совмещенные с "большим" BERT `DeepPavlov/rubert-base-cased`
- `prediction_w2v.tsv` -- предсказания Word2Vec

  
