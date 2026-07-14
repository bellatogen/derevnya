# Пятиречье

Изометрический мистический хоррор. Разработка на Unreal Engine 5.3.

## Команда

| Роль | Участник | Зона ответственности |
|---|---|---|
| Гейм-дизайн, UE5, бинарный контент | Костя | `Village/Content/`, `Village/Config/` |
| Концепт-арт | Коля | `art/` |
| Нарратив, диалоги | Павел | `narrative/`, оператор Claude, единственный, кто мержит PR |

## Требования

- Unreal Engine 5.3
- Git
- [Git LFS](https://git-lfs.com/)

## Быстрый старт

```bash
# 1. Установить Git LFS ДО клонирования
git lfs install

# 2. Склонировать репозиторий
git clone https://github.com/bellatogen/derevnya.git
cd derevnya

# 3. Открыть проект
# Дважды кликнуть Village/Village.uproject (или открыть через Epic Games Launcher /
# Unreal Editor 5.3)
```

## Важно

`Village/Saved/` и `Village/Intermediate/` — генерируемые UE-каталоги (кэш, логи,
автосейвы, краш-дампы). Они в `.gitignore` — **не коммитить**, даже если редактор
их пересоздаёт при каждом запуске.

## Документация

- Правила работы Claude Code в этом репозитории — [`CLAUDE.md`](./CLAUDE.md)
- Документация проекта — [`docs/`](./docs/)
- Спецификации фич — [`specs/`](./specs/)
