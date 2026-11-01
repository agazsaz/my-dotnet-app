# my-dotnet-app

Лабораторная работа: настройка пайплайна CI/CD для приложения на C# (.NET) с использованием GitHub Actions и Docker.

## 1. Локальная сборка Docker
Приложение успешно собирается и запускается в контейнере.
**<img width="814" height="209" alt="изображение" src="https://github.com/user-attachments/assets/55d88a86-7e5f-4641-9458-3b9fdeee08f9" />
**

## 2. Успешный запуск пайплайна (GitHub Actions)
Пайплайн автоматически собирает проект на C# и проверяет сборку Docker-образа. Все этапы завершились успешно.
**<img width="1201" height="101" alt="изображение" src="https://github.com/user-attachments/assets/eb9de399-1661-4aa2-abc1-10df08a2a332" />**

## 3. Логи сборки Docker-образа
Джоб `build` успешно собрал Docker-образ приложения в среде CI.
**<img width="1159" height="644" alt="изображение" src="https://github.com/user-attachments/assets/6309b0d0-f567-47f1-9eb9-6c28a2f23cf8" />
**

## Вывод
В ходе работы был настроен полный цикл CI для .NET-приложения. Автоматизированы сборка C#-проекта и его контейнеризация. Все задачи выполнены.

