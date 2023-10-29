# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Папушев Роман Олегович
- РИ220947
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | - |
| Задание 2 | * | - |
| Задание 3 | * | - |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- -

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.

- см. [скрипт](https://github.com/LeonKote/DA-in-GameDev-lab1/blob/master/Anaconda/HelloWorld.ipynb).

```py

print('Hello World')

```

## Задание 2
### Написать программу Hello World на C# с запуском на Unity. 

- см. [каталог](https://github.com/LeonKote/DA-in-GameDev-lab1/tree/master/HelloWorld) с проектом.
- см. [скрипт](https://github.com/LeonKote/DA-in-GameDev-lab1/blob/master/HelloWorld/Assets/Scripts/GameManager.cs).

```cs

using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.UI;

public class GameManager : MonoBehaviour
{
    public Text Text;

    // Start is called before the first frame update
    void Start()
    {
        Text.text = "Hello World";
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}

```

## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

- Отчёт оформлен и выложен в одном репозитории с выполненными заданиями.
- см. [репозиторий](https://github.com/LeonKote/DA-in-GameDev-lab1/blob/master/README.md).

## Выводы

В процессе работы я установил необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python, а также рассмотрел процесс установки игрового движка Unity для разработки игр. Я узнал, как написать программу Hello World на Python с запуском в Jupiter Notebook и на C# с запуском на Unity, а также как оформлять отчет в виде документации на github (markdown-разметка).


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
