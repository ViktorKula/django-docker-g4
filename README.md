<div id="header" align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-plain-wordmark.svg" width="200"/>
</div>

### Задача
Как системному администратору данной организации вам поставлена задача собрать на докер образ Django (Linux, nginx, Django, Postgres, Gunicorn) сервера, который можно было бы выложить в публичный доступ на Docker Hub, предоставляя кандидату только ссылку на образ и команду для установки. Все нужные сервисы должны быть проброшены на хост по стандартным портам, реализация HTTPS не требуется, версии Django, nginx и Postgres не имеют значения, как и версия ядра Linux. В проекте просто должна работать админка с заранее прописанным логином и паролем.

### Установка:

1. Клонирование репозитория 

```
git clone [https://github.com/OkulusDev/Oxygen.git](https://github.com/ViktorKula/django-docker-g4/edit/main/README.md)
cd django-docker-g4
```
2. Создайте и настройте виртуальное окружение (опционально)

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
3. Запустите Docker Compose
   
```
docker-compose up -d
```
4. Проверьте состояние контейнеров

```
docker-compose ps
```
5. Выполните миграции базы данных

```
docker-compose exec web python manage.py migrate
```
6. Создайте суперпользователя (если необходимо)

```
docker-compose exec web python manage.py createsuperuser
```
7. Соберите статические файлы

```
docker-compose exec web python manage.py collectstatic --noinput
```



- ***Сборка***
`npm run build` - ***создает оптимизированную сборку в директории*** build/

---

### Логины и Пароли для входа находятся в файле password

---

### :hammer_and_wrench: Languages and Tools :
<div>  
  <img src="https://github.com/devicons/devicon/blob/master/icons/django/django-plain-wordmark.svg" title="dgango" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-plain-wordmark.svg" title="Docker" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp; 
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;  
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/webstorm/webstorm-original.svg" title="WebStorm" **alt="Git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/webpack/webpack-original.svg" title="Webpack"  **alt="Git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="npm"  **alt="Git" width="40" height="40"/>
</div>


---

### :fire: My Stats :

<a href="https://git.io/streak-stats"><img src="https://github-readme-streak-stats.herokuapp.com?user=ViktorKula&theme=react" alt="GitHub Streak" /></a>

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ViktorKula&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)


<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
<div id="badges">
  <a href="https://www.instagram.com/ve.aesir?igsh=bmoxeWMxc200enZo&utm_source=qr">
    <img src="https://img.shields.io/badge/Instagram-red?style=flat&logo=Instagram&logoColor=blue&style=for-the-badge" alt="Youtube Badge"/>
  </a>  
</div>
  <img src="https://komarev.com/ghpvc/?username=ViktorKula&style=flat-square&color=blue" alt=""/>
</div>
