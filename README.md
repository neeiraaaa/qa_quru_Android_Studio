## Проект Mobile автотестов для приложения Wikipedia

<!-- Технологии -->

### Используемые технологии
<p  align="center">
  <code><img width="5%" title="Pycharm" src="./tests/resources/logo/pycharm.png"></code>
  <code><img width="5%" title="Python" src="./tests/resources/logo/python.png"></code>
  <code><img width="5%" title="Pytest" src="./tests/resources/logo/pytest.png"></code>
  <code><img width="5%" title="Selene" src="./tests/resources/logo/selene.png"></code>
  <code><img width="5%" title="GitHub" src="./tests/resources/logo/github.png"></code>
  <code><img width="5%" title="Browserstack" src="./tests/resources/logo/browserstack.png"></code>
  <code><img width="5%" title="Appium" src="./tests/resources/logo/appium.png"></code>

</p>

### Что выполняет тест:
Навигацию по экранам приложения Wikipedia 
- [x] Проверка стартового экрана
- [x] Проверка перехода к второму экрана
- [x] Проверка перехода к третьему экрану
- [x] Проверка перехода к четвертому экрана

## :computer: Запуск тестов из терминала
```bash
env -S "context=browserstack" pytest .
env -S "context=emulation" pytest .
```

<!-- Browserstack -->

### <img width="3%" title="Browserstack" src="tests/resources/logo/browserstack.png"> Запуск проекта в [Browserstack](https://app-automate.browserstack.com/dashboard/v2/builds/f28c349abaad3f7d39dfcd35456f87613336db26/sessions/5120171442d8f8caa501ddce865892e431122b91)
##### Где в реальном времени можно следить за прохождением теста через логи.

![This is an image](tests/resources/screenshots/browserstack.png)

<!-- Android Studio -->
### Запуск проекта в Android Studio
![This is an image](tests/resources/video/video.gif)