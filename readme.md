# Initialisation

## Generer une nouvelle cle du nouveau projet

'''
php artisan key:generate
'''


# Les Presets

* L' echafaudage de l'Auth a ete generer
* Echaffaudage pour react et vue et restructuration de dossier <b>resources/assets/js<b>
* Ajout et configuation du Captcha sur la page d'inscription


# Les vendors

- [Carbon, les dates](https://github.com/briannesbitt/Carbon).
- [Debugbar, la barre de deboggae et de trace](https://github.com/barryvdh/laravel-debugbar).
- [Laravel UUID, generateur de uuid](https://github.com/webpatser/laravel-uuid).
- [reCaptcha for Laravel, generateur de uuid](https://github.com/greggilbert/recaptcha).
- [Guzzle, requetes http serveur/serveur](https://github.com/guzzle/guzzle).
- [JWT, travail avec les Json Web Token](https://github.com/lcobucci/jwt).

# TODO

- run php artisan vendor:publish --provider="Greggilbert\Recaptcha\RecaptchaServiceProvider".
- Ajouter les libraries suivantes:
	- [Intervention Image, travailler les images uploader](https://github.com/Intervention/image).
	- [Laradrop, travailler les images uploader](https://github.com/jasekz/laradrop).
	- [Voyager, admin pour laravel](https://github.com/the-control-group/voyager).
	*	


```json

{
    "require": {
       "barryvdh/laravel-translation-manager": "^0.4.2",
       "creativeorange/gravatar": "^1.0",
       "davejamesmiller/laravel-breadcrumbs": "4.*",
       "elasticsearch/elasticsearch": "^6.0",
       "hieu-le/active": "^3.5",
       "laravel/browser-kit-testing": "1.*",
       "laravel/socialite": "^3.0",
       "laravelcollective/html": "^5.4.0",
       "mercuryseries/flashy": "^1.0",
       "predis/predis": "^1.1",
       "rap2hpoutre/laravel-log-viewer": "^0.13.0",
       "spatie/laravel-activitylog": "^2.5",
       "yajra/laravel-datatables-oracle": "^8.4",
       "zizaco/entrust": "5.2.x-dev"
    }
}
```



<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of any modern web application framework, making it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 1100 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.