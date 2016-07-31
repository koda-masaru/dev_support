# Developer Support Tools

- Support tools for developers
- It use on local or webservice on docker


## Local use

1. Checkout this project code to your pc.
2. Click index.html


## Webservice on Docker

1. Checkout this project code to your pc.
2. Start webserver(Nginx) on Docker

   ```
   $ docker pull nginx:stable
   $ docker run --name dev_support -v $PWD:/usr/share/nginx/html:ro -d  -p 80:80 nginx:stable
   ```

3. Access to tools service

   - http://localhost








