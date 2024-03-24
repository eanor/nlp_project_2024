# Comparing semantic shift detection strategies for Russian

Это репозиторий для финального проекта по NLP-2024.

**Тема проекта**: Сравнение стратегий обнаружения семантического сдвига

**Участники**:

- Анастасия Алексеева
- Павел Астафьев
- Тимофей Дедов
- Светлана Кузнецова

**Золотой стандарт** взят с RuShiftEval \[Kutuzov & Pivovarova 2021\] -- [здесь](https://raw.githubusercontent.com/akutuzov/rushifteval_public/main/annotated_testset.tsv).

## Описание структуры репозитория

- `models_evaluation.ipynb` код оценки корреляции Спирмена по результатам использованных моделей
- В папке `corpus` лежат файлы корпуса (в формате `.txt` и `.json` (`.json` использовался для ELMO))
- В папке `models` лежат файлы кода запуска использованных моделей
- В папке `predictions` лежат косинусные расстояния для каждой пары эпох (Досоветская & Советская, Совесткая & Постсоветская, Досоветская & Постсоветская) для использованных моделей

## Литература

Kutuzov, A. & Pivovarova, L. 2021. Three-part Diachronic Semantic Change Dataset for Russian. In Proc. of the _International Workshop on Computational Approaches to Historical Language Change (LChange)_. Association for Computational Linguistics (ACL). Available at https://arxiv.org/pdf/2106.08294.pdf
