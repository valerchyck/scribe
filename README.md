# Scribe

> https://scribe.readthedocs.io/en/latest/ - оригинальная документация

## Изменения в файлах:
- добавлены новые параметры в конфиг [#commit](https://gitlab.ittour.com.ua/root/scribe_api_doc/commit/cf5dc16c9c34dfec9923dc96e5330a1a3bb5d4ae)
- удален хардкодный "Content-Type" из параметров запроса.
[#commit](https://gitlab.ittour.com.ua/root/scribe_api_doc/commit/d3004d90443bb7e32645cd3ab9d063fd72857bd9)
- добавлено документирование входящих параметров запроса основываясь на валидацию через метод "**$this->validate()**". 
[#commit](https://gitlab.ittour.com.ua/root/scribe_api_doc/commit/5b37b941377d038b06863b5c8a48639f9dc116c4)
- добавленно общее описание документации для всех сервисов и возможность установки нескольких серверов **API**.
[#commit](https://gitlab.ittour.com.ua/root/scribe_api_doc/commit/0cec1bd3bd43c118449b81ac955aeb56f87cbc20)
- удалена проверка параметров конфига (потому-что мы внесли новые). удалена запись кэша при генерации доки (тормозит генерацию). добавлена генерация приватного yaml (для внутреннего пользования) [#commit](https://gitlab.ittour.com.ua/root/scribe_api_doc/commit/f4ca11e3939f0ebe20952b3dc37049afa4a1332b)