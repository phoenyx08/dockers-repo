# Dockers Repo

My docker containers and setups

*In progress by now... To be continue...*

**Please, note that this setup was only tested on MacOSX**

## How to use it (as a dev-container)

1. Clone this repository

2. cd to the repository folder

3. Create MySQL root password at dev/nginx-php-mysql-dev/access by renaming and changing password.example, or creating new file named "password"

4. cd to dev/nginx-php-mysql-dev

5. run "docker-compose up"

6. Place your site files at ~/projects/ or it's subdirectory

7. To configure mysql connections from your site use host mysql, user root and password, configured on step 3

8. Create nginx config for the site and name give it extension .conf and place it in dev/nginx-php-mysql-dev/conf.d/sites. Please note, that your host's documents folder ~/projects will be mapped to /usr/share/nginx/html of nginx container and /var/www/html of php container.

9. Configure your host's /etc/hosts to direct development domain to 127.0.0.1

10. Restart nginx container

11. Check that all works well

12. Report ussues [here](https://github.com/phoenyx08/dockers-repo/issues)
