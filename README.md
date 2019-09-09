# kit-starter-symfony-4-docker
🏁 The perfect kit starter for a Symfony 4 project with Docker and PHP 7.2
+ SEE: https://medium.com/@romaricp/the-perfect-kit-starter-for-a-symfony-4-project-with-docker-and-php-7-2-fda447b6bca1

# Build
+ docker-compose build

# Run
+ docker-compose up -d

# Install symfony
+ Run: docker exec -it -u dev sf4_php bash
+ composer create-project symfony/skeleton my-temp-folder
+ cp -Rf /home/wwwroot/sf4/my-temp-folder/. .
+ rm -Rf /home/wwwroot/sf4/my-temp-folder
+ Open localhost in your browser!
