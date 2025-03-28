# Space Invaders for Nand

Простая космическая игра, написанная на языке Jack для курса "From Nand to Tetris". В игре игрок управляет ракетой и должен уничтожать падающих пришельцев с помощью пуль.

## Описание игры

В игре вы управляете ракетой в нижней части экрана. Сверху падают пришельцы, которых нужно уничтожать с помощью пуль. Игра заканчивается, если пришелец достигает нижней части экрана или сталкивается с ракетой. За уничтожение пришельцев начисляются очки.

### Особенности
- Система очков
- Уровни сложности
- Управление стрелками
- Стрельба пулями
- Экран Game Over с возможностью перезапуска

## Управление
- Стрелка влево - движение ракеты влево
- Стрелка вправо - движение ракеты вправо
- Пробел - стрельба пулями
- R - перезапуск игры (на экране Game Over)
- Q - выход в главное меню

## Установка и запуск

### Требования
- [n2t-software-suite](https://www.nand2tetris.org/software) (VM Emulator)
- Файлы игры (.jack файлы)

### Шаги по запуску
1. Скачайте и установите n2t-software-suite
2. Склонируйте репозиторий или скачайте файлы игры
3. Запустите VM Emulator
4. Загрузите файлы игры в VM Emulator:
   - Откройте папку с файлами игры
   - Выберите все .jack файлы
   - Нажмите "Load Program"
5. Нажмите "Run" для запуска игры

## Структура проекта
- Game.jack - основной класс игры
- Rocket.jack - класс ракеты игрока
- Alien.jack - класс пришельцев
- Bullet.jack - класс пуль
- Другие вспомогательные классы

## Разработка
Игра разработана в рамках курса "From Nand to Tetris" (часть 2) с использованием языка Jack.
