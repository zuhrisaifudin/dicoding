# A387-Jarkom-Labs

Untuk menjalankan project ini, pastikan `npm` sudah terinstall pada komputer/laptop Anda.

---

Tata cara menjalankan project:

1. Install node modules

```
npm install
```

2. Jalankan project

```
npm run start
```

# install nginx pada MacBook Anda
Step 1: Download Homebrew
``````
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
``````

step 2: Update the Homebrew repository index
``````
brew update  
``````

Step 3: Install Nginx
``````
brew install nginx 
``````

The Nginx server will install on the location /usr/local/cellar. The entire executable services related to starting and stopping Nginx are stored inside the bin folder of the installation directory.

The web server will listen by default on port number 8080. To start the Nginx, use the following command:


Add configs in -> /usr/local/etc/nginx/servers/
Default config -> /usr/local/etc/nginx/nginx.conf
Logs will be in -> /usr/local/var/log/nginx/
Default webroot is -> /usr/local/var/www/
Default listen address -> http://localhost:8080
