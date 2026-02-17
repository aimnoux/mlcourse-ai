# mlcourse.ai

Открытый курс машинного обучения от сообщества OpenDataScience (mlcourse.ai).

## Содержание курса

1. **Pandas и первичный анализ данных**
   - [Лекция](https://www.youtube.com/watch?v=OAy96yiWohk&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=1) + [Статья](https://habr.com/ru/companies/ods/articles/322626/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework1-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework1-solution.ipynb)

2. **Визуализация данных**
   - [Лекция](https://www.youtube.com/watch?v=uwQat1TV0JM&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=2) + [Статья](https://habr.com/ru/companies/ods/articles/323210/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework2-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework2-solution.ipynb)

3. **Классификация, деревья решений**
   - [Лекция](https://www.youtube.com/watch?v=crerhGu3j-8&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=3) + [Статья](https://habr.com/ru/companies/ods/articles/322534/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework3-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework3-solution.ipynb)

4. **Логистическая регрессия**
   - [Лекция](https://www.youtube.com/watch?v=NO4KSNbsXZE&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=4) + [Статья](https://habr.com/ru/companies/ods/articles/323890/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework4-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework4-solution.ipynb)

5. **Случайный лес и ансамблевые методы**
   - [Лекция](https://www.youtube.com/watch?v=_XKQY62NJus&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=5) + [Статья](https://habr.com/ru/companies/ods/articles/324402/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework5-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework5-solution.ipynb)

6. **Регрессия и регуляризация**
   - [Лекция](https://www.youtube.com/watch?v=70WsnE4ep1Y&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=6) + [Статья](https://habr.com/ru/companies/ods/articles/325422/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework6-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework6-solution.ipynb)

7. **Обучение без учителя**
   - [Лекция](https://www.youtube.com/watch?v=u6_b0I4fGgc&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=7) + [Статья](https://habr.com/ru/companies/ods/articles/325654/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework7-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework7-solution.ipynb)

8. **Обучение на больших выборках, Vowpal Wabbit**
   - [Лекция](https://www.youtube.com/watch?v=_bRb7LYeOp4&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=8) + [Статья](https://habr.com/ru/companies/ods/articles/326418/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework8-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework8-solution.ipynb)

9. **Временные ряды**
   - [Лекция](https://www.youtube.com/watch?v=vZueTTJGec4&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=9) + [Статья](https://habr.com/ru/companies/ods/articles/327242/)
   - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework9-todo.ipynb) + [Решение](https://github.com/aimnoux/mlcourse-ai/tree/main/solutions/homework9-solution.ipynb)

10. **Градиентный бустинг**
    - [Лекция](https://www.youtube.com/watch?v=ow5LdsjzfL0&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=10) + [Статья](https://habr.com/ru/companies/ods/articles/327250/)
    - [Домашнее задание](https://github.com/aimnoux/mlcourse-ai/tree/main/homeworks/homework10-todo.ipynb)

## Настройка окружения

Требуется Python 3.11+. Выберите один из двух вариантов:

### Вариант 1: conda

```bash
conda create -n mlcourse python=3.11 -y
conda activate mlcourse
pip install -r requirements.txt
```

### Вариант 2: venv

```bash
python3 -m venv .venv
source .venv/bin/activate   # Linux/macOS
# .venv\Scripts\activate    # Windows
pip install -r requirements.txt
```

### macOS: дополнительная настройка

Для работы xgboost требуется OpenMP:

```bash
brew install libomp
```