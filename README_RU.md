> [!IMPORTANT]
> **[ТЕСТИРОВАНИЕ И ОБСУЖДЕНИЕ · FLAT2VR DISCORD](https://discord.gg/P4q9zt7ek)**
> Тестирование, запрос сборок, отзывы и обсуждение проходят в **Flat2VR Modding Discord**. Перейди на сервер и найди тему **Titanfall 1 VR**.

![Titanfall 1 VR — Monsterdeadwood VR mods](assets/vr-banner.svg)

# Titanfall 1 VR

[English](README.md) · [Русский](README_RU.md) · [Flat2VR Discord](https://discord.gg/P4q9zt7ek) · [All projects](PORTFOLIO.md)

![Project status](assets/vr-status.svg)

VR-ветка Titanfall 1 для поддерживаемых сборок R1Delta: стереообзор, прицеливание пилота и работа с кабинами титанов. Спасибо команде [R1Delta](https://r1delta.net/) за общественную платформу.

**Текущая описанная ветка: R1Delta VR development branch.**

## Установка

1. Возьми совместимую тестовую сборку **Titanfall 1 VR / R1Delta** в теме игры на Flat2VR. Сначала проверь обычный запуск R1Delta.
2. Сохрани структуру пакета: полная папка мода размещается внутри **t1**, рядом с **bin**, **r1** и **vpk**.
3. Подключи PC VR, выбери OpenXR runtime и запусти **RUN_TITANFALL_VR.bat**. Оставь консоль открытой.
4. Используй CONTROLS.txt из сборки и проверь её требования к версии R1Delta и игры.

Доступность актуальных тестовых пакетов уточняется в Discord. Нужен полный пакет для поддерживаемой версии игры; страница проекта сама по себе не является скачиваемым релизом.

## Что есть в проекте

- Стерео и трекинг камеры пилота/титана в экспериментальной ветке.
- Прицеливание от контроллера с сохранением родного поведения оружия.
- Отдельная работа над согласованием родного направления выстрела клиента и сервера.
- Последняя контролируемая проверка охватила 16 классов оружия, включая оружие титанов.

<details>
<summary><b>Краткое управление</b></summary>

| Действие / кнопка | Назначение |
| --- | --- |
| RUN_TITANFALL_VR.bat | Запустить сборку |
| CONTROLS.txt in the package | Раскладка действий для конкретной версии |
| Ctrl+C in the launcher | Закрыть собственный тестовый сеанс |

Полная инструкция управления в конкретной сборке учитывает её версию и профиль контроллеров.

</details>

## Текущий статус

**Экспериментальная сборка.** Кандидат нативного направления оружия проверен в настоящей игре через XR Sim и собственный приватный сервер: движение и прыжки пилота, 16 классов оружия.

- Последние проверки прицеливания не подтверждают принятие в физическом шлеме и совместимость публичного PvP с людьми.
- В последнем кандидате серверная точка выстрела остаётся штатной, от игрока. Совпадение конечных попаданий, всё оружие и способности ещё требуют проверки.

Родное предсказание выстрела, кабины и расширение арсенала развиваются в отдельных контролируемых кандидатах.

[Подробный статус и область проверки](docs/PROJECT_STATUS.md)

## Тестирование и отзывы

Напиши в [тему игры на Flat2VR](https://discord.gg/P4q9zt7ek): укажи **версию мода, игру/магазин, шлем, OpenXR runtime, GPU, шаги воспроизведения и диагностический ZIP сборки**. Для проблем изображения или управления полезно короткое видео.

## Другие мои VR-моды

| Игра / проект | Направление | Доступ |
| --- | --- | --- |
| [Battlefield 3 VR](https://github.com/Monsterdeadwood/BF3VR) | Кампания, оружие и руки | Закрытый |
| [Assassin’s Creed VR](https://github.com/Monsterdeadwood/AC1VR) | Обзор от первого лица, лазание и меч | Закрытый |
| [Crysis 2 VR](https://github.com/Monsterdeadwood/C2VR) | Нанокостюм, физическое взаимодействие и интерфейс | Закрытый |
| [NOVA · CS:GO Legacy VR](https://github.com/Monsterdeadwood/CSGOVR) | Локальные матчи CS:GO Legacy с VR-управлением | Закрытый |
| [TimeShift VR](https://github.com/Monsterdeadwood/TimeShiftVR) | Управление временем, девять видов оружия и позы | Закрытый |
| [You Are Empty: Absolute Edition VR](https://github.com/Monsterdeadwood/YouAreEmptyAEVR) | Absolute Edition в VR, оружие и взаимодействие | Открытый |
| [Alone in the Dark 2008 VR](https://github.com/Monsterdeadwood/AloneInTheDark2008VR) | VR-хоррор и взаимодействие с предметами | Открытый |
| [Rainbow Six Siege VR](https://github.com/Monsterdeadwood/SiegeVR) | Стерео и оружие от контроллеров в старой Siege | Открытый |
| [Burnout Paradise Remastered VR](https://github.com/Monsterdeadwood/BUrnOutPvr) | Стереовождение, меню автомобилей и эффекты | Закрытый |
| [Metro 2033 VR](https://github.com/Monsterdeadwood/Metro2033VR) | Оригинальная Metro в VR и нативная физика | Открытый |
| [Insurgency VR](https://github.com/Monsterdeadwood/InsurgencyVR) | Начальная подготовка VR-интеграции | Закрытый |
| [Counter-Strike: Source VR](https://github.com/Monsterdeadwood/CSSVR) | Разработка VR для Counter-Strike: Source | Закрытый |

Ссылки на закрытые репозитории доступны приглашённым участникам. Открытые страницы отмечены в таблице.

## Авторство и заметки разработки

Проект ведёт [Monsterdeadwood](https://github.com/Monsterdeadwood). Это независимый фанатский VR-проект; нужна собственная поддерживаемая копия оригинальной игры.

Общественная платформа: команда [R1Delta](https://r1delta.net/).

[Прежний обзор репозитория, сохранённый как история](README_RESEARCH_ARCHIVE.md).

Описание сверено: **14 ноября 2026 года**.
