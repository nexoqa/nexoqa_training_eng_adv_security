# nexoqa_training_eng_adv_security
Course Eng_Adv

# bWAPP

This is just an instance of the OWASP [bWAPP project](http://www.itsecgames.com/) as a docker container.

The container is based on [tutum/lamp](https://hub.docker.com/r/tutum/lamp/)

Start bWAPP
```
docker-compose up -d
```

To configure bWAPP
```
#Open you browser and go to this url
http://localhost:8001/install.php
```

Now open the login page
```
#Open you browser and go to this url
http://localhost:8001/login.php
```

Install ZAP
```
https://www.zaproxy.org/download/
```

Run OWASP Juice Shop
```
docker run -d -p 3000:3000 bkimminich/juice-shop
```

