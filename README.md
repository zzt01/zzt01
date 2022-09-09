**Создание GitLab runner для будущего CI/CD компании через Vagrant**

Первым делом скачиваем [Vagrant](https://drive.google.com/drive/u/0/folders/1Ev8N8LijxNR2npEwhoUFlxBuznf--ujP) для него.
А дальше, вооружившись справочной документацией, мы беремся за работу!

**Документация**

  - Установка [VirtualBox, Vagrant+Ubuntu и Vagrantfile](https://www.youtube.com/watch?v=dgm5MtCcIMs&t=5150s)
  - [Установка](https://docs.gitlab.com/runner/install/) и (регистрация)[https://docs.gitlab.com/runner/register/index.html] Gitlab Runner
  - (Установка Docker)[https://docs.docker.com/engine/install/ubuntu/]
  - (Vagrant Provisioning)[https://www.vagrantup.com/docs/provisioning] и (на русском)[https://automation-remarks.com/setting-vagrant/)
  - (Полная документация)[https://www.vagrantup.com/docs] по Vagrant для самоподготовки

**Чекпоинты по уровню сложности:**
  1. Создать vagrant-файл запускающий виртуальную машину с ubuntu 20.04
  2. Установить gitlab runner с docker через репозитории
  3. Создать проект на (gitlab.com)[https://gitlab.com/] и добавить туда собственные раннеры типов shell и docker
  4. Автоматизировать этап 2 через параметры провижининга а Vagrant
  5. Авторматизировать этап 3 через параметры провижининга в Vagrant, используя переменные




