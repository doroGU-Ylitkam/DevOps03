# DevOps03
### Пайплайн для сборки приложения 1 (с созданием тега и релиза в github)
Для запуска Pipeline (app1-pipeline) необходимо указать в repository url (в Jenkins):
```shell
https://github.com/doroGU-Ylitkam/DevOps03.git
```

Script Path, который необходимо указать в Pipeline
```shell
app1-pipeline/Jenkinsfile
```
Изменение версий (тэгов) можно посмотреть тут
```shell
https://github.com/doroGU-Ylitkam/DevOps01
```
_____
### Пайплайн для сборки приложения 2 (с созданием тега и релиза в github)
Для запуска Pipeline (app2-pipeline) необходимо указать в repository url (в Jenkins):
```shell
https://github.com/doroGU-Ylitkam/DevOps03.git
```

Script Path, который необходимо указать в Pipeline
```shell
app2-pipeline/Jenkinsfile
```

Изменение версий (тэгов) можно посмотреть тут
```shell
https://github.com/doroGU-Ylitkam/DevOps03-forkForRelease-
```
_____
### Пайплайн для запуска обоих приложений (1 и 2)
Для запуска Pipeline (pullApps) необходимо указать в repository url (в Jenkins):
```shell
https://github.com/doroGU-Ylitkam/DevOps03.git
```
Script Path, который необходимо указать в Pipeline
```shell
pullApps/Jenkinsfile
```
_____
В папке config можно найти конфигурации для приложений
