
# Spotibar
<a href="https://github.com/avenom/spotibar/releases/tag/v0.3"><img src="https://img.shields.io/github/v/release/avenom/spotibar?color=1&label=Release"></a> <a href="https://rainmeter.net"><img src="https://img.shields.io/badge/Rainmeter-4.4-brightgreen"></a> <img src="https://img.shields.io/badge/Windows-7%2B-brightgreen"> <img src="https://img.shields.io/github/downloads/avenom/spotibar/total?color=1&label=Downloads">

<img src="https://raw.githubusercontent.com/avenom/Spotibar/main/%40Resources/Images/Spotibartest.gif">

## Spotibar Mini

* Запуск Spotify по иконке, сворачивается обратно в иконку, когда Spotify не запущен
* Клик по текущему треку и исполнителю открывает окно Spotify*
* Кнопки управления:  `Предыдущий трек` `Плей/Пауза` `Следующий трек`
* Регулировка громкости колесом мыши при наведении на плеер, правый клик выключает звук

## Spotibar Max

* Запуск Spotify по иконке, сворачивается обратно в иконку, когда Spotify не запущен
* Клик по текущему треку и исполнителю открывает окно Spotify*
* Кнопки управления:  `Предыдущий трек` `Плей/Пауза` `Следующий трек`
* Кнопки управления при наведении на обложку:  `Лайк` `Повторять трек` `Перемешать треки`
* Прогресс трека и версия с фоном адаптируются под цвет обложки
* Регулировка громкости колесом мыши при наведении на плеер, правый клик выключает звук

###### * Для правильной работы сворачивайте окно Spotify, а не закрывайте.

## Установка

1. Установите клиент [Spotify](https://spotify.com/ru-ru/download/windows)
2. Установите [Rainmeter 4.4](https://rainmeter.net)
3. Установите скин [Spotibar](https://github.com/avenom/spotibar/releases/tag/v0.3), перезапустите Rainmeter и активируйте скин

#### Для работы Spotibar Max требуется установка Spicetify**:

В поиске Windows 10 наберите PowerShell и запустите Windows PoweShell. В открывшемся окне терминала выполните по порядку следующие команды:

``` Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression ```

``` spicetify ```

``` spicetify config extensions webnowplaying.js ```

``` spicetify config inject_css 0 replace_colors 0 ```

``` spicetify backup apply ```

###### ** Предупреждение: Spicetify использует предыдущий интерфейс Spotify, после установки он откатит новый интерфейс Spotify к предыдущей версии. Восстановить Spotify можно только после удаления Spicetify командой `spicetify restore`, но Spotibar Max работать не будет

## Настройка

Закройте в Rainmeter все стандартные скины illustro и выберите Spotibar.
* [x] Всегда поверх окон
* [x] Перетаскивание
* [ ] Некликабельно

Можете в Rainmeter включить игровой режим, чтобы скин выключался в полноэкранном режиме.
