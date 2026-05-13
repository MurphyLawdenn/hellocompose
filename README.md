# Hello Compose

![Android CI](https://github.com/MurphyLawdenn/hellocompose/actions/workflows/android-ci.yml/badge.svg?branch=develop)

Навчальний приклад використання Jetpack Compose — лабораторна робота №1 з дисципліни «Розробка мобільних застосунків».

## Опис
Простий застосунок, який демонструє базові концепції Jetpack Compose:
- декларативний UI
- стан компонента через `remember` + `mutableStateOf`
- обробку подій (натискання кнопки)
- Material 3 темізацію

## Скріншоти
<p align="center">
  <img src="screenshots/app_main.png" width="400" alt="Початковий стан">
  <img src="screenshots/app_after_click.png" width="400" alt="Стан після натискання">
</p>
<p align="center">
  <img src="screenshots/app_dark.png" width="400" alt="Темна тема">
  <img src="screenshots/app_studio.png" width="400" alt="Android Studio Preview">
</p>

## Як запустити
1. Встановіть Android Studio (версия Hedgehog або новіша).
2. Клонуйте репозиторій:
   ```bash
   git clone https://github.com/MurphyLawdenn/hellocompose.git
   cd hellocompose
   ```
3. Відкрийте проект у Android Studio.
4. Дочекайтеся синхронізації Gradle.
5. Запустіть додаток на эмуляторі або реальному пристрої через кнопку **Run** або командою:
   ```bash
   ./gradlew assembleDebug
   ```

## Перевірка проекту
Для запуску лінтера та тестів використовуйте:
```bash
./gradlew lintDebug
./gradlew test
```

## Структура проекту
```
HelloCompose/
├── app/
│   └── src/main/
│       ├── java/com/example/hellocompose/MainActivity.kt
│       └── res/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── workflows/android-ci.yml
└── .gitignore
```

## GitFlow
Проект використовує модель GitFlow з гілками:
- `main` — продакшн-релізи
- `develop` — основна гілка розробки
- `feature/*` — нові фічі
- `release/*` — підготовка до релізу
- `hotfix/*` — термінові виправлення

## Автор
Білоус Владислав, група К-31, Ірпінський фаховий коледж економіки та права.
