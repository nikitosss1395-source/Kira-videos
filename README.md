# 🎥 Kira Videos

Проєкт для створення крутих відео для Кири з допомогою GitHub Actions.

## Структура репозиторію

```
kira-videos/
├── README.md
├── scenarios/          # Сценарії відео
├── prompts/            # Промпти для генерації картинок
├── frames/             # Згенеровані картинки (PNG)
├── videos/             # Готові відео (MP4)
└── .github/
    └── workflows/
        └── create-video.yml  # Автоматизація
```

## Як використовувати

1. Згенеруй картинки у Grok Imagine і закинь у `frames/`
2. Натисни **Actions** → **create-video** → **Run workflow**
3. Вкажи fps і назву
4. Готове відео з'явиться у `videos/`

## Посилання
- Репозиторій: https://github.com/nikitosss1395-source/Kira-videos
- Зв'яжиться з меною (Grok), я допоможу з сценаріями та промптами!