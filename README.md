Хакатон «Лидеры цифровой трансформации» по задаче Департамента финансов Москвы

## Стек технологий

* Язык: Kotlin
* UI: Jetpack Compose (Material 3)
* Архитектура: MVI, StateFlow
* База данных: SQLite
* Графика: Canvas (без тяжелых картинок)
* Платформа: Android 8.0+ (API 26+)
* Без рекламы, без интернета, без встроенных покупок за реальные деньги.

---

## Как собрать и запустить

Нужна Android Studio и JDK 17.

Сборка apk через терминал:

```powershell
# Windows
.\gradlew.bat assembleDebug

# Linux / macOS
./gradlew assembleDebug
```

Готовый файл появится здесь:  
`app/build/outputs/apk/debug/app-debug.apk`

---

## Структура папок

```text
app/src/main/java/ru/finpet/app/
├── audio/          # фоновая музыка и звуки
├── data/           # репозиторий, состояния и локальная база данных
├── model/          # модели данных (питомец, квесты, бюджет, задания)
└── ui/
    ├── components/ # кнопки, банки, сцена комнаты, аватар
    ├── screens/    # экраны приложения
    └── theme/      # цвета, темы и шрифты
```
