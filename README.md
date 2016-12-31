# SetupHomeWebServer
1. Install Apache on server
2. install mysql on server
3. install php on server
4. get account at http://freedns.afraid.org/
5. add your domain (get one if you need it)
6. follow instructions there
7. setup router port forwarding (mine is a two step with router/modem to router)
   -port forwarding on modem to the router
   -port forwarding to server on router to the ip of the web server
8. create subdomain (freedns.afraid.org)
9. create the subfolder on the web server where the subdomain should get redirected
10.  configure .htaccess to redirect subdomain requests to the subfolder
11. configure the apache default config file to allow redirects
