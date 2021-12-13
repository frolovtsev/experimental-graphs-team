# experimental-graphs-team
Задание по обработке МНК на командную работу

Ранее вы сделали задание по обработке экспериментальных данных.
Сейчас задача собрать ваши варианты решения задач в один гибкий код,
позволяющий загружать файлы с разным форматом (.xls, .xlsx, .txt),
обрабатывать данные с помощью МНК различными способами (МНК с весами и без весов),
также нужно добавить МНК для нелинейной функции.
После обработки данных их нужно вывести на экран. График должен быть настраиваемый "снаружи".

Есть следующие задачи: 1) загрузка файлов, 2) обработка данных, 3)вывод графика, сохранение данных и графиков,
4) создание проверочных функций, которые проверяют, что на вход подаются правильные данные (формат аргументов;
привильное количество столбцов; все ли строки полностью указаны и тп)
а также организационная работа (для Лидера) -- 5) договориться, как будут взаимодействовать части программы,
создание документации на программу и отдельные её части (кто что принимает, как работать с программой),
предварительное тестирование, а также сборка частей в единое целое.
Итого -- 5 задач.
Разделитесь на группы по 5 человек, распределите эти задачи между собой задачи (о том, кто и что делает, напишет Лидер 
в отчете).

Лидер создаёт у себя репозиторий, в который остальные участники добавляют код (делают pull request).
Затем Лидер добавляет к себе код (merge).

Для того, чтобы задача была принята, программа будет подвергнута следующим тестам:
1. Загрузка данных из файлов различного формата
2. Проверка поведения при некорректных входных данных

Для проведения тестов потребуются образци файлов  (.xls, .xlsx, .txt) с данными
