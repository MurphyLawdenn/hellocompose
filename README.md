# Hello Compose

![Android CI](https://github.com/OWNER/REPO/actions/workflows/android-ci.yml/badge.svg)

Навчальний приклад використання Jetpack Compose — лабораторна робота №1 з дисципліни «Розробка мобільних застосунків».

## Опис
Простий застосунок, який демонструє базові концепції Jetpack Compose:
- декларативний UI
- стан компонента через `remember` + `mutableStateOf`
- обробку подій (натискання кнопки)
- Material 3 темізацію

## Як запустити
1. Встановіть Android Studio та SDK (API 26+).
2. Клонуйте репозиторій:
   ```bash
   git clone https://github.com/OWNER/REPO.git
   cd REPO
   ```
3. Відкрийте проект у Android Studio → дочекайтеся Gradle Sync → Run на AVD або реальному пристрої.

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
