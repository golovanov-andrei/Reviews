# 💳 Credit Risk Classification

Модель машинного обучения для оценки кредитного риска заемщиков.  
Проект реализует полный pipeline: от обработки данных до предсказания вероятности дефолта.

---

## 🚀 Возможности

### 📊 End-to-End Pipeline
- Очистка данных  
- Feature Engineering  
- Масштабирование  
- Предсказание  

### 🤖 ML-модель
- Логистическая регрессия *(или укажи свою модель)*  
- Предсказание вероятности дефолта  
- Интерпретируемый результат  

### 🌐 Веб-интерфейс
- Реализация через Streamlit  
- Удобный ввод данных пользователя  
- Мгновенный результат  

---

## 📁 Структура проекта


.
├── Credit risk.ipynb # Обучение модели
├── app.py # Streamlit-приложение
├── credit_model.pkl # Обученная модель
├── feature_columns.pkl # Список признаков
└── requirements.txt # Зависимости


---

## ⚙️ Установка и запуск

### 1. Клонирование репозитория
```bash
git clone https://github.com/golovanov-andrei/credit-risk-project.git
cd credit-risk-project
2. Установка зависимостей
pip install -r requirements.txt
🧠 Обучение модели

Открой и запусти ноутбук:

Credit risk.ipynb
▶️ Запуск приложения
streamlit run app.py

После запуска открой в браузере:

http://localhost:8501
📊 Пример использования

Пользователь вводит параметры:

доход
возраст
кредитная история
другие признаки

➡️ Модель возвращает вероятность дефолта и уровень риска

🛠️ Стек технологий
Python
Pandas
NumPy
Scikit-learn
Streamlit
📌 Дальнейшие улучшения
Добавить более сложные модели (XGBoost, LightGBM)
Добавить explainability (SHAP)
Подключить базу данных
Деплой (Render / AWS / Docker)
👤 Автор

Андрей Голованов
GitHub: https://github.com/golovanov-andrei
