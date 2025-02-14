# Unity Портфолио
Здесь представлены проекты разработанные мной в процессе изучения Unity. За 1.5 года разработки в Unity я успел пополнить свое портфолио как простыми проектами по типу match3, так и более серьезными работами с применением  различных фреймворков. Проекты расположены в порядке от новых к старым.
## Проекты

### Tower Defense (DOTS)
Игра в жанре Tower Defense.

Игра сделана с использованием DOTS (ECS, burst compiler, job system). Основные механики, такие как перемещение юнитов, поиск цели, стрельба и способности персонажа сделаны при помощи unity DOTS. Анимация была реализована гибридным методом, при котором для каждой сущности (entity), создавался отдельный игровой объект (GameObject), который анимирован стандартными средствами unity.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Tower_Defense
- Игра (Itch.io) - https://syraxwell.itch.io/tower-defense
- Видео геймплея (Google drive) - [Tower Defense](https://drive.google.com/drive/folders/1J7130aYnUCOBfoNorDcSgei3h1UOVZbV?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Tower-defense/tower_defense_gameplay.png" alt="tower_defense_gameplay" width ="70%" />
  <img src="resources/Tower-defense/tower_defense_skill_selection.png" width ="70%" />
  </p>
</details>

### Pong (multiplayer)
Классический Pong.

Игра поддерживает одиночную игру против бота и мультиплеер на одном устройстве и по сети. Мультиплеер реализован при помощи Netcode for GameObjects и сервисов unity Lobby и unity Relay. Netcode for GameObjects использовался для синхронизации данных между клиентом и хостом. При помощи unity Lobby было реализовано создание лобби для поиска и подключения других игроков. Unity Relay использовался для создания пиринговой сети для подключения игроков без необходимости выделения отдельных серверов.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Pong
- Игра (Itch.io) - https://syraxwell.itch.io/pong
- Видео геймплея (Google drive) - [Pong](https://drive.google.com/drive/folders/1oDt7UoVqRb7oo28arcphwQL7S1op4AK9?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Pong/pong_title_screen.png" width ="49%" />
  <img src="resources/Pong/pong_lobby.png" width ="49%" />
  <img src="resources/Pong/pong_gameplay_screen.png" width ="49%" />
  <img src="resources/Pong/pong_game_over_screen.png" width ="49%" />
  </p>
</details>

###  Match 3
Браузерная игра в жанре три в ряд.

В игру интегрирована Yandex SDK, игра была выложена на платформу Яндекс Игры. При помощи Yandex SDK в игру была интегрирована реклама и лидерборды. Для игры был также написан редактор уровней и бот для тестирования уровней. Анимации были реализованы при помощи DOTween.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Match3
- Игра (Itch.io) - https://syraxwell.itch.io/fruits-and-berries-match3
- Видео геймплея (Google drive) - [Match3](https://drive.google.com/drive/folders/1aaWxEXOGQUpS75rD5PsctHtdOfAP2Q69?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Match3/match3_example_level_2.png" width ="70%" />
  </p>
</details>

###  Bubble Shooter
Браузерная аркадная игра головоломка в жанре Bubble shooter.

В игру интегрирована Yandex SDK. При помощи Yandex SDK была интегрирована реклама и лидерборды. Анимации реализованы при помощи DOTween.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Bubble_shooter
- Игра (Itch.io) - https://syraxwell.itch.io/bubble-shooter
- Видео геймплея (Google drive) - [Bubble Shooter](https://drive.google.com/drive/folders/16heVq02oC7uD-TXfX5NN7lACBD-TIgbk?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Bubble-shooter/bubble_shooter_gameplay.png" width ="70%" />
  </p>
</details>

### Pop The Balls
Браузерная аркадная игра головоломка в жанре tile-matching video game.

В игру интегрирована Yandex SDK. При помощи Yandex SDK была интегрирована реклама и лидерборды. Анимации реализованы при помощи DOTween.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Pop_the_balls
- Игра (Itch.io) - https://syraxwell.itch.io/pop-the-balls
- Видео геймплея (Google drive) - [Pop The Ball](https://drive.google.com/drive/folders/1jYY6AiTwjFy4dbO5RK678M8FVj3P6ISW?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Pop-the-balls/pop_the_balls_gameplay.png" width ="70%" />
  </p>
</details>

### Simple Platformer
Браузерный минималистичный платформер.

В проект интегрирована Yndex SDK. В игре реализована система достижений и магазин для покупки скинов. Игра состоит из 40 уровней. Сохранения сделаны через json файлы.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Simple-Platformer
- Игра (Itch.io) - https://syraxwell.itch.io/simple-platformer
- Видео геймплея (Google drive) - [Simple Platformer](https://drive.google.com/drive/folders/1XfgMrgbTj0pYuBTurQglvVNkptBu6d-v?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Simple-platformer/simple_platformer_gameplay.gif" width ="49%" />
  <img src="resources/Simple-platformer/simple_platformer_title_screen.png" width ="49%" />
  <img src="resources/Simple-platformer/simple_platformer_skins.png" width ="49%" />
  <img src="resources/Simple-platformer/simple_platformer_achievements.png" width ="49%" />
  </p>
</details>

### Red-heat-gift-rescue (Gamega Game Jam)
Аркадная игра сделанная в рамках Gamega Game Jam.

Это бесконечная аркадная игра на максимальный счет. Бегай по ледяному лабиринту, собирай подарки и уворачивайся от огненных лучей.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Gamega-Jam-Game
- Игра (Itch.io) - https://syraxwell.itch.io/red-heat-gift-rescue
- Видео геймплея (Google drive) - [Red Heat Gift Rescue (Gamega Jam Game)](https://drive.google.com/drive/folders/1ccD8FGzR6hX4KIpn7fNeMjrkMdphnPIO?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Red-heat-gift-rescue/red_heat_gift_rescue.png" width ="70%" />
  </p>
</details>

### Space Shooter
Вертикальный космический shoot ’em up. 

В игре имеются 3 персонажа с различными умениями. В игре реализована система "апгрейдов" и система "реликвий" для повышения характеристик персонажей. Цель игры - продержаться 20 волн и победить финального босса.

Ссылки:
- Код (GitHub) - https://github.com/CyrAXwell/Space-Shooter
- Игра (Itch.io) - https://syraxwell.itch.io/spase-shooter
- Видео геймплея (Google drive) - [Space Shooter](https://drive.google.com/drive/folders/1JqAwmG_DeqGJhjPIbi4bmkRBFo72pUc4?usp=drive_link)

<details open>
  <summary>Скриншоты: </summary>
  <p align="left">
  <img src="resources/Space-shooter/space_shooter_demo_gameplay.gif" width ="70%" />
  <img src="resources/Space-shooter/space_shooter_characters.png" width ="70%" />
  <img src="resources/Space-shooter/space_shooter_upgrades.png" width ="70%" />
  <img src="resources/Space-shooter/space_shooter_gems.png" width ="70%" />
  </p>
</details>
