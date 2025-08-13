# Yandex MapKit Lite Initializer (FlutterFlow-friendly)

Плагин инициализирует Yandex MapKit Lite на **Android** через ContentProvider,
чтобы не требовался `MainApplication.kt`. Подходит для проектов FlutterFlow.

## Установка (в FlutterFlow)
1. Опубликуйте этот репозиторий на GitHub/GitLab.
2. В FlutterFlow → **Project Dependencies → Custom Pub Dependencies → Add**:
   ```yaml
   yandex_mapkit_lite: ^2.0.2
   yandex_mapkit_lite_initializer:
     git:
       url: https://github.com/<you>/yandex_mapkit_lite_initializer.git
       ref: main
