**Лабораторная работа 3**

**Задание 1**

Установим cmake (brew install cmake)

Создадим для удобства отдельную папку (mkdir lab03)

Скопируем туда репозиторий с гитхаба (git clone https://github.com/tp-labs/lab03)

Перейдем в директорию formatter_lib и создадим файл CMake (> CMakeLists.txt)

С помощью редактора nano откроем файл (nano CMakeLists.txt) и произведем изменения

Сделаем отдельную папку для build

mkdir build

Генерируем: cmake /Users/admin/lab03/formatter_lib

Билдим: cmake --build . --config Release

**Задание 2**

Перейдем в директорию formatter_ex_lib

Создадим файл Cmake (> CMakeLists.txt)

Откроем файл в редакторе nano (nano CMakeLists.txt) и произведем изменения

Сделаем отдельную папку для build

mkdir build

Генерируем: cmake /Users/admin/lab03/formatter_ex_lib

Билдим: cmake --build . --config Release

**Задание 3**

**Для Hello World!**

Перейдем в директорию hello_world_application

Создадим файл CMakeLists.txt (> CMakeLists.txt)

Откроем файл CMakeLists и внесем изменения

mkdir build 

cd build

Генерируем: cmake /Users/admin/lab03/hello_world_application 

Билдим: cmake --build . --config Release

**Для Solver**

Перейдем в директорию solver_application

Создадим файл CMakeLists.txt

Откроем файл и внесем изменения

Исправим ошибки в solver.cpp
 
mkdir build

cd build

Генерируем: cmake /Users/admin/lab03/solver_application

Билдим: cmake --build . --config Release
