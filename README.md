# web_app
A sample web app create in Express framework by using docker-compose

### Abstract

Using nginx, mysql, Redis container.
In nginx container, I use https. So it can be used https://localhost to see your own web app.
And I use dummy ssl key to realize it.
And also I use EntryKit to render different .conf file in order to different ##nvironment.

### Step to use

- Install the docker (I use docker for mac)
- docker-compose up
- https://localhost
