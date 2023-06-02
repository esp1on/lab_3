**Лабораторная работа 3**

**Задание 1**

Установим cmake (brew install cmake)

Создадим для удобства отдельную папку (mkdir lab03)

Скопируем туда репозиторий с гитхаба (git clone https://github.com/tp-labs/lab03)

Перейдем в директорию formatter_lib и создадим файл CMake (> CMakeLists.txt)

С помощью редактора nano откроем файл (nano CMakeLists.txt) и произведем изменения

<img width="682" alt="Снимок экрана 2023-05-27 в 14 44 58" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/ca06f287-3050-4861-bc48-1f956df7e19b">

Сделаем отдельную папку для build

mkdir build

Генерируем: cmake /Users/admin/lab03/formatter_lib

Билдим: cmake --build . --config Release

<img width="682" alt="Снимок экрана 2023-05-27 в 14 51 49" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/e1e567f6-e8a8-4cd3-85d5-72a1cbe4dbe6">

**Задание 2**

Перейдем в директорию formatter_ex_lib

Создадим файл Cmake (> CMakeLists.txt)

Откроем файл в редакторе nano (nano CMakeLists.txt) и произведем изменения

<img width="682" alt="Снимок экрана 2023-05-27 в 15 10 26" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/c9c7d917-dcf6-4875-926b-0689952e2466">

Сделаем отдельную папку для build

mkdir build

Генерируем: cmake /Users/admin/lab03/formatter_ex_lib

Билдим: cmake --build . --config Release

<img width="682" alt="Снимок экрана 2023-05-27 в 15 16 24" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/4beabbd9-5fe6-4551-b66c-645ed23fc075">

**Задание 3**

**Для Hello World!**

Перейдем в директорию hello_world_application

Создадим файл CMakeLists.txt (> CMakeLists.txt)

Откроем файл CMakeLists и внесем изменения

<img width="682" alt="Снимок экрана 2023-05-30 в 20 44 04" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/93b76a3b-d291-47e3-9db8-cee737649ac5">

mkdir build 

cd build

Генерируем: cmake /Users/admin/lab03/hello_world_application 

Билдим: cmake --build . --config Release

<img width="682" alt="Снимок экрана 2023-05-30 в 20 48 05" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/4428eb46-c837-4839-9444-af5273b97f98">

**Для Solver**

Перейдем в директорию solver_application

Создадим файл CMakeLists.txt

Откроем файл и внесем изменения

<img width="682" alt="Снимок экрана 2023-05-30 в 21 07 04" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/804e1ca5-c54e-485c-9242-618cb3c24049">

Исправим ошибки в solver.cpp
 
<img width="642" alt="Снимок экрана 2023-05-30 в 21 21 16" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/2aeefe53-d281-48cc-843a-64985d3fe9e0">
 
mkdir build

cd build

Генерируем: cmake /Users/admin/lab03/solver_application

Билдим: cmake --build . --config Release

<img width="682" alt="Снимок экрана 2023-05-30 в 21 23 50" src="https://github.com/FUR1OUSS/TIMP_lab3/assets/82472327/bba41b58-b441-4c1d-95ab-ba3ab14bd266">
