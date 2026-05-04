# 📝 Reviews Classification Project

Проект по анализу и классификации текстовых отзывов с использованием методов машинного обучения и обработки естественного языка (**NLP**).

Модель обучается определять тональность отзывов (Positive/Negative) на основе текстовых данных, проходя через полный цикл предобработки и векторизации.

---

## 💡 Пример реализации

<table>
  <tr>
    <td><img src="https://github.com/golovanov-andrei/Reviews/blob/main/screens/reviews.png" width="100%"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/golovanov-andrei/Reviews/blob/main/screens/lda.png" width="100%"></td>
  </tr>
</table>

---

## 🚀 Возможности проекта

*   **📊 Предобработка текста:** Очистка от спецсимволов, токенизация, удаление стоп-слов и лемматизация.
*   **🔤 Векторизация:** Преобразование текста в числовые признаки с помощью **TF-IDF** или **CountVectorizer**.
*   **🤖 ML-классификация:** Обучение моделей для предсказания тональности отзыва.
*   **📈 Оценка качества:** Подробный анализ метрик (Accuracy, Precision, Recall, F1-score) и построение Confusion Matrix.
*   **📓 End-to-End Pipeline:** Весь процесс от загрузки данных до инференса реализован в едином рабочем цикле.

---

## 🧠 Технологический стек

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-NLP-4B8BBE)
[📊Dataset on Kaggle](https://www.kaggle.com/datasets/dongrelaxman/amazon-reviews-dataset/data)
---

## 📂 Структура проекта

```bash
.
├── reviews.ipynb          
├── Amazon_Reviews.csv
└── README.md              
```

---

## ⚙️ Установка и запуск

### 1. Клонирование репозитория
```bash
git clone https://github.com
cd reviews-classification
```

### 2. Установка зависимостей
Рекомендуется использовать виртуальное окружение:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk
```

### 3. Запуск
```bash
jupyter notebook reviews.ipynb
```

---

## 📊 Pipeline работы
1. **Загрузка данных:** Импорт датасета с отзывами.
2. **EDA:** Анализ распределения классов.
3. **Preprocessing:** Очистка текста и нормализация.
4. **Vectorization:** Применение TF-IDF трансформации.
5. **Modeling:** Обучение классификатора (например, Logistic Regression или Random Forest).
6. **Evaluation:** Валидация на тестовой выборке.

---

## 👤 Автор

**Андрей Голованов**  
[![GitHub](https://img.shields.io/badge/GitHub-golovanov--andrei-black?logo=github)](https://github.com/golovanov-andrei)
