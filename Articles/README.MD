# Articles — Методы из научных статей

## Описание

Данная папка содержит эксперименты по воспроизведению и адаптации методов отбора признаков из современных научных публикаций в области uplift-моделирования.

## Содержимое

| Файл | Описание |
|------|----------|
| `Эксперименты_из_статей_dip.ipynb` | Воспроизведение методов из научных статей с адаптацией под датасет fetch_lenta |
| `Лит. Обзор.xlsx` | Литературный обзор: сводная таблица изученных статей |

## Исследованные методы

В ноутбуке рассмотрены следующие подходы из публикаций:

### 1. Customer feature selection from high-dimensional bank direct marketing data for uplift modeling
Метод отбора признаков для uplift-моделирования на высокоразмерных данных банковского маркетинга.

### 2. Doubly Robust Adaptive LASSO for Effect
Использование адаптивного LASSO с двойно-робастной оценкой эффекта для отбора признаков.

### 3. A Non-parametric Bayesian Approach for Uplift Discretization and Feature Selection
Непараметрический байесовский подход к дискретизации uplift и отбору признаков.

### 4. Robustness-enhanced Uplift Modeling with Adversarial Feature Desensitization
Повышение робастности uplift-моделирования с помощью адверсариальной десенсибилизации признаков.

### 5. Multihead Causal Distilling Weighting Is All You Need for Uplift Modeling
Многоголовая причинная дистилляция с взвешиванием для uplift-моделирования.

## Метрика качества

Для оценки качества используется метрика **AUUC** (Area Under the Uplift Curve) и **PUC** (Principle Uplift Curve). Для каждого метода проводится оптимизация гиперпараметров с помощью `optuna`.

## Ссылка на ноутбук в Google Colab

[Открыть в Colab](https://colab.research.google.com/drive/1aTZQAxjFoXyEhmIOYtfm5k1HH470Radk?usp=sharing)
