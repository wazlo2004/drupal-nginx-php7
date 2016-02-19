# drupal-nginx-dockerfil
1.Download and go to Folder

2.nano Dockerfil Write your MYSQLPASSWORD

3.build your docker image

docker build -t wazlo2004/nginx-php7:tag .

docker run -ti --name YOURCONTAINERNAME wazlo2004/nginx-php7:tag /bin/bash

