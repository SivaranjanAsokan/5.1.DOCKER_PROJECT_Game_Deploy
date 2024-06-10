# 2048
[LinkedIn ](https://www.linkedin.com/posts/sivaranjandevopscloud_docker-gamedevelopment-devops-activity-7206000655151353856-A8xf?utm_source=share&utm_medium=member_desktop
)


A small clone of [1024](https://play.google.com/store/apps/details?id=com.veewo.a1024), based on [Saming's 2048](http://saming.fr/p/2048/) (also a clone).

Made just for fun. [Play it here!](http://gabrielecirulli.github.io/2048/)

The official app can also be found on the [Play Store](https://play.google.com/store/apps/details?id=com.gabrielecirulli.app2048) and [App Store!](https://itunes.apple.com/us/app/2048-by-gabriele-cirulli/id868076805)

### Contributions

[Anna Harren](https://github.com/iirelu/) and [sigod](https://github.com/sigod) are maintainers for this repository.

Other notable contributors:

 - [TimPetricola](https://github.com/TimPetricola) added best score storage
 - [chrisprice](https://github.com/chrisprice) added custom code for swipe handling on mobile
 - [marcingajda](https://github.com/marcingajda) made swipes work on Windows Phone
 - [mgarciaisaia](https://github.com/mgarciaisaia) added support for Android 2.3

Many thanks to [rayhaanj](https://github.com/rayhaanj), [Mechazawa](https://github.com/Mechazawa), [grant](https://github.com/grant), [remram44](https://github.com/remram44) and [ghoullier](https://github.com/ghoullier) for the many other good contributions.

### Screenshot

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/1175750/8614312/280e5dc2-26f1-11e5-9f1f-5891c3ca8b26.png" alt="Screenshot"/>
</p>

That screenshot is fake, by the way. I never reached 2048 :smile:

## Contributing
Changes and improvements are more than welcome! Feel free to fork and open a pull request. Please make your changes in a specific branch and request to pull into `master`! If you can, please make sure the game fully works before sending the PR, as that will help speed up the process.

You can find the same information in the [contributing guide.](https://github.com/gabrielecirulli/2048/blob/master/CONTRIBUTING.md)

## License & Code Credit
2048 is licensed under the [MIT license.](https://github.com/gabrielecirulli/2048/blob/master/LICENSE.txt)





















<!--FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install -y nginx zip unzip  curl
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
RUN curl -o /var/www/html/master.zip -L https://github.com/gabrielecirulli/2048/archive/refs/heads/master.zip
# Extract the zip file
RUN unzip /var/www/html/master.zip -d /var/www/html/

# Move the contents to the web root and clean up
RUN mv /var/www/html/2048-master/* /var/www/html/ && rm -rf /var/www/html/2048-master /var/www/html/master.zip


EXPOSE 80

CMD ["/usr/sbin/nginx", "-c", "/etc/nginx/nginx.conf"] -->
