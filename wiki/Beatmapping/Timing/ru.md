# Тайминг

**Тайминг** — процесс определения музыкальной структуры песни. Он заключается в поиске всех [тайминг-секций](/wiki/Client/Beatmap_editor/Timing) песни, их [темпа](/wiki/Music_theory/Tempo) и [тактовых размеров](/wiki/Music_theory/Time_signature).

[Настройки тайминга](/wiki/Client/Beatmap_editor/Timing) в [редакторе карт](/wiki/Client/Beatmap_editor) показаны в виде [расположенной сверху шкалы](/wiki/Client/Beatmap_editor/Timelines#timing), похожей на линейку. Помещённые туда [игровые объекты](/wiki/Gameplay/Hit_object) [привязываются](/wiki/Beatmapping/Snapping) к полоскам (тикам) на шкале, которые обозначают равные интервалы в одном [музыкальном такте](/wiki/Music_theory/Measure) и призваны упростить выравнивание объектов под песню.

Помимо равномерной расстановки нот, тайминг отвечает за следующие вещи:

- Пульсацию [логотипа osu!](/wiki/Client/Interface/Cookie) (англ. *osu! cookie*) в главном меню и на [экране выбора песни](/wiki/Client/Interface#song-select), а также за пульсацию прочих эффектов меню, привязанных к ритму;
- Пульсацию игровых объектов во время [киаи](/wiki/Gameplay/Kiai_time);
- Сэмплы ударных инструментов, добавляемые модом [Nightcore](/wiki/Gameplay/Game_modifier/Nightcore);
- Появление линий начала такта (англ. *barline*) в [osu!taiko](/wiki/Game_mode/osu!taiko) и [osu!mania](/wiki/Game_mode/osu!mania).

Несмотря на прямую зависимость от музыки, на тайминг частично влияют *свойства конкретного аудио*: это значит, что при изменении аудиофайла или после его замены уже настроенный тайминг может «слететь». Чтобы не жалеть о потере, следует сначала проверить аудио на соответствие [критерием ранкинга](/wiki/Ranking_criteria#аудио), а уже только потом настраивать тайминг.

## Структура песни

*Основная статья: [Теория музыки](/wiki/Music_theory)*

Почти у всех песен есть свой темп. Задача тайминга — определить этот темп и зафиксировать, как он меняется со временем на разных участках песни (если меняется вообще). В этом может частично помочь знание основных терминов теории музыки:

- [Доля](/wiki/Music_theory/Beat) — основная единица ритма, обычно равная четвертно́й ноте. Ноты с другими длинами можно выразить через долю, деля её на равные части или умножая в несколько раз.
- [Такт](/wiki/Music_theory/Measure) — фиксированное число долей, которое повторяется в течние всей песни. Первая нота в такте, на которую делается акцент, называется [сильной долей](/wiki/Music_theory/Downbeat).
- [Размер такта](/wiki/Music_theory/Time_signature) — число, показывающее, сколько долей содержится в одном такте.
- [Ритм](/wiki/Music_theory/Rhythm) — определённая последовательность звуков и интервалов между ними.
- [Темп](/wiki/Music_theory/Tempo) — скорость песни, измеряемая в ударах в минуту (BPM).

## Процесс тайминга

*Основная статья: [Настройка тайминга](/wiki/Guides/How_to_time_songs)*\
*См. также: [Редактор карт/Тайминг](/wiki/Client/Beatmap_editor/Timing)*

### Песни с постоянным BPM

Если у песни не меняется темп, то для правильного тайминга достаточно добавить в карту одну-единственную [тайминг-секцию](/wiki/Client/Beatmap_editor/Timing#красные-тайминг-секции). Её необходимо поставить на момент с первой сильной долей песни. Время, прошедшее с начала аудиофайла и до этого момента, также называется оффсетом. На основе поставленной секции osu! автоматически рассчитает положение всех остальных нот. Этого будет достаточно для цифровой музыки или достаточно отредактированых песен, где нет изменений темпа, тактов с разным размером, и отсутствуют сбросы метронома.

Чтобы самостоятельно подобрать примерный темп песни, перейдите на [вкладку настроек тайминга](/wiki/Client/Beatmap_editor/Timing) и начните ритмично нажимать на клавишу `T`, либо кликать по кнопке около метронома в правом верхнем углу. Подобранное число можно вручную менять до тех пор, пока щелчки метронома не начнут совпадать с ритмом музыки. Стоит упомянуть о двух моментах:

- Большинство песен имеют целое число BPM. Если вы вручную подобрали значение более чем с одним знаком после запятой, то, скорее всего, оно неправильное, хотя и выглядит точным.
- Оффсет [должен находиться](/wiki/Guides/Setting_the_offset_on_the_correct_beat) на первой сильной доле песни — этого требуют [критерии ранкинга](/wiki/Ranking_criteria#тайминг).

### Песни с меняющимся BPM

![](img/complex-timing.png "Пример карты со сложным таймингом, «MiddleIsland - Roze» от Lan wings, где на три минуты пианино и скрипки приходится около трёх сотен красных тайминг-секций.")

Для правильного тайминга песни с меняющимся темпом потребуется несколько оффсетов, так как в ней может быть либо несколько участков с разными темпами (англ. *multi-BPM*), либо постоянно меняющийся темп (англ. *variable BPM*). В первом случае оффсетов может быть относительно немного, во втором же — несколько десятков или даже сотен.

Музыка, исполненная без метронома, может содержать самые разные артефакты тайминга, например, произвольные смены темпа или ноты, сыгранные не в ритм. Это может быть сделано как намеренно, ради музыкальной выразительности, так и из-за человеческого фактора. Подобные погрешности необходимо учитывать при тайминге, что может оказаться достаточно сложно — старайтесь не браться за такие песни, если у вас мало терпения или опыта в тайминге.

Маленькие погрешности — например, расхождение в несколько миллисекунд, — можно не таймить, если песня записана под метроном и нормально играется и с более простым таймингом. Альтернативный подход заключается в редактировании аудио в программах типа [Audacity](https://www.audacityteam.org/), чтобы [квантизировать](https://ru.wikipedia.org/wiki/Квантайз) звуки (подвинуть их туда, где они должны быть согласно таймингу).

Иногда нужно добавить новый оффсет, не меняя темп, чтобы отметить сбившийся ритм песни. Это требуется, например, если аудио неровно склеено, и такт в месте склейки длится чуть больше или чуть меньше, чем надо, либо если композитор сам плохо справился с квантизацией нот.

Наконец, новый оффсет нужен при смене музыкального размера, либо при сбросе метронома: например, если песня переходит из обычного «квадратного» размера (4/4) в вальс (3/4), или если очередной такт начинается на одну или несколько долей раньше.

## Отношение к таймингу

Тайминг считается одним из самых сложных для овладевания навыков, поскольку он требует развитого чувства ритма и большого запаса терпения. Как следствие, мапперы часто просят о тайминге других мапперов и [моддеров](/wiki/Modding) — лично, либо в общих [чатах](/wiki/Client/Interface/Chat_console) и [форумах](/wiki/Community/Forum), посвящённых моддингу. В одном из подобных тредов, "[Unable to find the BPM/offset of your map? Post here](https://osu.ppy.sh/community/forums/topics/13795)", за 13 лет скопилось более чем 5 тысяч постов.

Таймингу посвящён [отдельный раздел критериев ранкинга](/wiki/Ranking_criteria#timing), где рассказываются требования к [картам, идущим на ранк](/wiki/Beatmap_ranking_procedure).

## См. также

- *[osu!academy Episode 7-2 - Timing Basics](https://www.youtube.com/watch?v=8nsbrOhLE9w)*, выпуск Youtube-цикла [osu!academy](/wiki/Community/Video_series/osu!academy).
- *[osu!mapping: timing](https://www.youtube.com/watch?v=xauZuMPgiQw)*, выпуск Youtube-цикла [osu!mapping](/wiki/Community/Video_series/osu!mapping).
