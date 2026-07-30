# WowVoice — русская озвучка квестов для World of Warcraft

Нейросеть читает текст задания вслух прямо в игре, пока ты играешь.

- 🎙️ **129 уникальных голосов**, обученных на **оригинальных репликах NPC и героев** из игры — звучат близко к оригиналу.
- 👑 **79 именных героев** с собственными голосами: Джайна, Гаррош, Андуин, Малфурион, Кадгар, Король-лич, Алекстраза, Чен и другие.
- 🧬 У **каждой расы и пола — свой голос** (50+ рас и типов существ): орк звучит орком, эльф — эльфом.

🎧 **Демо голосов:** https://www.youtube.com/watch?v=tivX-oaVBW4

Скачать — в разделе [**Releases**](https://github.com/HappyDridex/wowvoice/releases).

## Как установить

1. **Скачай** архив своей игры из [Releases](https://github.com/HappyDridex/wowvoice/releases):
   - Classic (ваниль) → `WowVoice-classic-1.15.zip`
   - Burning Crusade → `WowVoice-bc-2.4.3.zip`
   - Lich King (WotLK) → `WowVoice-wotlk-3.3.5.zip`
   - Пандария (MoP) → скачай **оба**: в `part1of2.zip` — папки `WowVoice` + `WowVoiceSounds` (первая половина озвучки), в `part2of2.zip` — только `WowVoiceSounds` (вторая половина). Оба распаковываются в `Interface\AddOns`, папки `WowVoiceSounds` **сливаются в одну** (Windows спросит «Объединить?» — жми **Да**).
2. **Распакуй.** Внутри — две папки: **WowVoice** и **WowVoiceSounds**.
3. **Скопируй обе папки** — `WowVoice` и `WowVoiceSounds` — в `…\World of Warcraft\…\Interface\AddOns\`.
   Должно получиться так:
   - `…\Interface\AddOns\WowVoice\`
   - `…\Interface\AddOns\WowVoiceSounds\`
4. **Запусти игру.** На экране выбора персонажа → **AddOns** (внизу слева):
   - поставь галочку **«Load out of date AddOns» / «Загружать устаревшие аддоны»** — без неё озвучка не включится;
   - убедись, что оба аддона включены.

Бери квест — озвучка заговорит сама. 🎧

## Поддержать

Новые эпохи и голоса: **https://boosty.to/wowvoice**

## Доступные сборки

| Эпоха | Клиент | Interface |
|---|---|---|
| Classic Era | 1.15.x | 11509 |
| The Burning Crusade | 2.4.3 | 20400 |
| Wrath of the Lich King | 3.3.5a | 30300 |
| Mists of Pandaria | 5.4.8 | 50400 |

> Midnight (retail) — в работе.
