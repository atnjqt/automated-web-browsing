## Docker setup

- DRAFT 12/07/2020

### Install Docker

More info on downloading & installing Docker [here](https://docs.docker.com/get-docker/)

### Browsing w/ Docker Selenium

- You can run the following to launch your container:

``` bash
docker run -d -p 4444:4444 -v --shm-mem=4G selenium/standalone-chrome
```

- To check on your container via http://localhost:4444/wd/hub/
_________
