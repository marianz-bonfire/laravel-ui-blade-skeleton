## Laravel UI Blade Skeleton

A simple Laravel boilerplate repository to create simple demo-project. It uses the Starter Kit [Laravel UI](https://github.com/laravel/ui) based on Bootstrap framework. And it allows to quickly add new routes/pages, and has examples of a table page, and a form page.


-----

### How to use

Clone this project to your local computer.

Navigate to the project folder.

```ps
cd laravel-ui-blade-skeleton
```

Install required packages.

```ps
composer install
```

create new .env file and edit database credentials there.

```ps
cp .env.example .env
```

Generate new app key.

```ps
php artisan key:generate
```

Run migrations. (it has some seeded data for your testing)

```ps
php artisan migrate --seed
```

Launch the main URL (e.g [http://localhost:8000](http://localhost:8000))

---

