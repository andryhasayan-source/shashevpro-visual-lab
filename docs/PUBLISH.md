# Публикация витрины на GitHub

Репозиторий содержит только описание, скриншоты и лицензию.
Исходный код не публикуется.

## Название

```
shashevpro-visual-lab
```

## Описание (поле About)

> Визуализатор музыки для Windows: живое поле светящихся узлов, 34 объёмные структуры, режим для OBS с хромакеем и прозрачным фоном. Коммерческий продукт.

English:

> Music visualiser for Windows: a living field of glowing nodes, 34 volumetric structures, OBS-ready broadcast mode with chroma key and true transparency. Commercial product.

## Темы

```
music-visualizer  audio-visualization  obs  streaming  windows
visualizer  generative-art  vj-software  audio-reactive
```

## Команды для Git Bash

Выполнять из папки витрины — НЕ из папки с исходниками.

```bash
git init
git add .
git commit -m "ShashevPro Visual Lab 3.9.5"
git branch -M main
git remote add origin https://github.com/ВАШ_ЛОГИН/shashevpro-visual-lab.git
git push -u origin main
```

## Перед первым push

```bash
git status --short
```

В списке должны быть только: `README.md`, `README.en.md`, `LICENSE`,
`CHANGELOG.md`, `.gitignore`, `docs/PUBLISH.md` и файлы из
`docs/screenshots/`. Если видите что-то из `resonance/` или `tests/` —
остановитесь: `.gitignore` не сработал, значит в папку попали исходники.

## Выкладка сборки

1. Releases → Draft a new release.
2. Tag `v3.9.5`, заголовок `ShashevPro Visual Lab 3.9.5`.
3. Прикрепить установщик и портативный архив.
4. В описание — раздел из `CHANGELOG.md`.

## Что заполнить перед публикацией

- В обоих README заменить `→ ссылка на кворк` на настоящую ссылку.
- Добавить демонстрационное видео: без него в этой категории почти
  не покупают.
