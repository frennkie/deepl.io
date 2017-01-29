# Deepl.io

A simple yet powerful PHP tool to catch Git webhooks from GitLab and GitHub and deploy your projects to your server after pushing.

#### [Current Release: 0.9.0](https://github.com/noelboss/deepl.io/archive/0.9.0.zip)

## Features

* Catch webhooks from GitLab & GitHub
* Configure multiple repositories
* Configure multiple branches per repository
* Use your own deploy scripts, either PHP, shell or both
* Sends confirmation emails

## Setup Apache2.4

```
    DocumentRoot /var/www/deploy
    <Directory "/var/www/deploy/">
      Options FollowSymLinks
      AllowOverride All
    </Directory>
```

## Configure Gitlab Hook

https://deploy.example.com/app/deeplio/Deeplio.php/your-very-long-secret-token-make-that-more-than-30-chars

#### [Visit the official website for instructions and more information »](http://deepl.io)

© 2015 [Noël Bossart](http://noelboss.com). Made in Switzerland.
