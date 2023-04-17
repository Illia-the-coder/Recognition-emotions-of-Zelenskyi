# Recognition-emotions-of-Zelenskyi
![image](https://user-images.githubusercontent.com/101904816/232555517-113c3f09-15c2-4dc8-a709-f7cb7445e180.png)

# 📷 Розпізнавання емоцій на мініатюрах відео

Цей код виконує розпізнавання емоцій на наборі зображень мініатюр відео з офіційного каналу YouTube [Zelenskyi](https://www.youtube.com/@Zelenskyy_President) з використанням заздалегідь навченої сверточної нейронної мережі VGG-16. Потім створюється кілька візуалізацій результатів.

## 🎓Використання

Для використання цього коду вам необхідно мати необхідні файли даних та встановлені залежності. Повний код та документація можуть бути знайдені в файлі **Jupyter Notebook**.

## Використані бібліотеки

| Бібліотека | Опис | Документація |
| --- | --- | --- |
| numpy | Бібліотека чисельного обчислення | https://numpy.org/doc/stable/ |
| pandas | Бібліотека маніпулювання даними | https://pandas.pydata.org/docs/ |
| os | Інтерфейс операційної системи | https://docs.python.org/3/library/os.html |
| IPython | Інтерактивне обчислення в Python | https://ipython.readthedocs.io/en/stable/ |
| cv2 | Бібліотека комп'ютерного зору | https://docs.opencv.org/4.5.4/ |
| matplotlib | Бібліотека візуалізації даних | https://matplotlib.org/stable/contents.html |
| tensorflow | Бібліотека машинного навчання | https://www.tensorflow.org/api_docs |
| seaborn | Бібліотека візуалізації даних | https://seaborn.pydata.org/ |
| ast | Бібліотека абстрактного синтаксичного дерева | https://docs.python.org/3/library/ast.html |

## План коду:

- Імпортування бібліотек 📚
- Завантаження даних 📂
- Фільтрація даних 🔍
- Вилучення дня з назви 📅
- Вилучення URL мініатюри 🖼️
- Завантаження мініатюр ⬇️
- Завантаження заздалегідь навченої моделі VGG-16 🧠
- Попередня обробка зображень ⚙️
- Функція передбачення 🔮
- Прогнозування емоцій ✨
- Створення візуалізацій емоцій 📈
![IMAGE 2023-04-17 19:12:09](https://user-images.githubusercontent.com/101904816/232559841-1981d915-affe-4485-8b9d-3015e2a4738e.jpg)
![IMAGE 2023-04-17 19:12:30](https://user-images.githubusercontent.com/101904816/232559914-a10ccb69-6a63-47eb-a6c0-b2c5821270ee.jpg)
![IMAGE 2023-04-17 19:12:46](https://user-images.githubusercontent.com/101904816/232559977-5f25166a-239f-4918-9bfe-a929c0ded349.jpg)
![IMAGE 2023-04-17 19:12:51](https://user-images.githubusercontent.com/101904816/232559990-efefa0b2-6cd8-4930-bf86-03c24ff298d9.jpg)
![IMAGE 2023-04-17 19:12:57](https://user-images.githubusercontent.com/101904816/232560005-04121a84-a052-4f06-b476-d9140233a3b7.jpg)
![IMAGE 2023-04-17 19:13:01](https://user-images.githubusercontent.com/101904816/232560026-85a07d63-b848-4462-90bb-fabef391788a.jpg)

## 🚀 Майбутня робота

Цей аналіз може включати додаткові набори відео та різні моделі розпізнавання емоцій для порівняння.
